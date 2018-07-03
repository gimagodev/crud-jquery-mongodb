npm Para executar a aplicação siga os passos:

Passo 1) Levantar o MongoDB
    O server MongoDB é carregado automaticamente no boot da máquina. 
    Caso necessitar levantá-lo executar o comando abaixo:
        > c:\mongodb\server\3.6\bin\mongod  --dbpath c:\mongodb\data  (server)
        > c:\mongodb\server\3.6\bin\mongo  (cliente)    

Passo 2) executar webapi onde estão as APIs que acessam os dados no MongoDB
    > cd webapi
    > node app.js

Passo 3) Executar a crud-jquery-mongodb (exemplojquery)
    > C:\wamp64\www\Node\crud-jquery-mongodb\index.html
    ou no localhost:porta\Node\crud-jquery-mongodb\index.html
Para utilizar este projeto:

No diretorio raiz da aplicacao:
 - npm install
 - node ace generate:key
 - duplicar o arquivo .env.example e nomea-lo .env
 - alterar o arquivo .env com a nova chave gerada
 - node ace migration:run 
 - node ace serve
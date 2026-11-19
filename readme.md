comandos para iniciar inciar este projeto

NPM INIT -Y
NPM INSTALL EXPRESS DOTENV
npm i typescript tsx @types/node @types/express @types/dotenv -D
npx tsc -- init


aquivos criados no inicio do projeto:
.gitignore -> contend: node_modules & .env e dist
.env

pasta criadas no inicio do projeto:
dist
src

------------------------------------------------

Para rodar um script criado no packege.json usar o comando:
npm run DEV // Nome do arquivo 
ao invés de escrever tsx watch src/server.ts
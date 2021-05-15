# Desafio Celso Lisboa para FullStack

### STACK -  NodeJs - Express - Sequelize - Mysql - Vue2

### Cenário

**Como** Coordenador Acadêmico de uma Instituição de Ensino  
**Eu preciso** realizar a gestão dos cursos oferecidos pela Instituição, com seus respectivos professores, salas e horários  
**Para** que o setor de Marketing possa vender os cursos online.

### Segue instruções para realizar o setup do projeto
entre no diretorio /app e rode os seguintes comandos
1. $ npm install
2. Altere as variaveis do banco no arquivo config/config.json
3. Crie o banco nomeado como no ambiente 'liga_mendex' pelo mysql cli -> $ mysql -uroot -p após inserir a senha rode $ create table liga_mendex
2. $ node server.js
   

### Rodando Seeders

1. $ npx sequelize db:seed:all

# My Todo List!

<img src="https://nodejs.org/static/images/logo.svg" height="50">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://angular.io/assets/images/logos/angular/logo-nav@2x.png" height="50">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://labs.mysql.com/common/logos/mysql-logo.svg?v2" height="50">

Esta aplicação é um gerenciador de tarefas desenvolvido com as seguintes tecnologias:

 - Api com NodeJs
 - Front Ent com Angular10
 - Banco de dados com Mysql

## Instrunções

O projeto está dividido em sub módulos, sendo necessário clonar e inicializar seus sub módulos, sendo assim, após clonar este repositório, também é necessário configurar o projeto do backend e do frontend, que são os sub módulos desse projeto.

**Obs.:** O arquivo / estrutura do banco de dados está disponível na raiz desse repositório (https://github.com/dernando/todo-list/blob/main/todo.sql).

Clone este projeto, e siga os passos a seguir:

 1. Inicialize os submódulos com o comando **`git submodule init`**
 2. Atualize os submódulos com o comando **`git submodule update`**
 3. Siga os passos a seguir para fazer o back end e back end da aplicação funcionar

### Fazendo o Back End funcionar

 1. Entre no diretório **todo-list-back**
 2. Execute o comando **`npm install`**
 3. Execute o comando **`npm start`**
 4. Assim que estiver disponível, deverá aparecer a mensagem **aplicação ok** no console.
 5. A aplicação estará disponível na url http://localhost:4000
 
**Obs.:** Para que o Back end funcione perfeitamente, é necessário importar o arquivo que contém a estrutura do banco de dados. As credenciais deverão ser configuradas no arquivo index.js 

### Fazendo o Front end funcionar

1. Entre no diretório **todo-list-front`**
 2. Execute o comando **`npm install`**
 3. Execute o comando **`npm start`**
 4. Assim que estiver disponível, deverá aparecer a mensagem **Compiled successfully**,
 5. A aplicação estará disponível no navegador pela url `http://localhost:4200`
 
**Obs** Para que a aplicação Front End funcione, é necessário que a aplicação back end também esteja funcionando.

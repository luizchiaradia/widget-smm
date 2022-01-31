# Widget SMM
Projeto visual do para criar uma busca no SMM e alimentar um conteúdo estruturado do Opencms.

## Pré-requisitos
- [Node.js](https://nodejs.org/en/download/ "Node Js")
-  NPM (Comes with Node.js)
- [Gulp 4](https://gulpjs.com/ "Gulp")

Instale o Gulp

     $ npm install --global gulp-cli
     

## Iniciando o projeto

1. Clone repository:
`git clone https://github.com/luizchiaradia/widget-smm.git`

    
2. Instale todas as dependências do projeto:
   `npm install`

4. Rode as tarefas do Gulp:
  - `gulp`      - Para compilar scss para css, minify css e js e criar os arquivos de produção na pasta **dist**.

  - `gulp dev`  - Inicia o servidor local com browserSync para reload quando ocorrem mudanças em arquivos da pasta **src** (HTML, SCSS, JS).

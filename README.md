## Objetivo <img src="https://d33wubrfki0l68.cloudfront.net/49c2be6f2607b5c12dd27f8ecc8521723447975d/f05c5/logo-small.cbbeba89.svg" alt="NestJs" width="30px" height="30px">

O objetivo deste projeto é documentar e servir de referência para criação de novos projetos rest que utilizem o framework NestJS. A ideia é manter esse projeto sempre atualizado com as bibliotecas que utilizo.

- NestJS
- Rest;
- TypeScript;
- Jest (teste automatizados);
- Login JWT;
- TypeORM (ORM);
- Postgres (banco de dados);

## NestJS (https://docs.nestjs.com/)

Nest é um framework escalável com suporte total ao TypeScript. Nest usa um sistema de módulos muito parecido com o do Angular, o que torna seu uso facilitado por quem conhece esse framework. Além disso, Nest usa o express como seu framework HTTP padrão, mas pode ser configurado o Fastify e oferece um CLI que facilita a criação do projeto, modulos, controles etc.

Já tive experiencia com Nest em outros projetos e no geral, me atendeu muito bem. Nest traz um padrão de organização e uma série de ferramentas que facilitam a implementação e a padronização de código.

## Instalação

Instalação do CLI do Nest

`npm i -g @nestjs/cli`

Criação do projeto

`nest new nest_reference_project`

## Outras bibliotecas

**As bibliotecas globais ficam configuradas em main.ts configurações dessas bibliotecas**

**compression** -> diminui consideravelmente o tamanho do corpo das respostas.

`npm i --save compression`

**helmet** -> pode ajudar a proteger seu aplicativo de algumas vulnerabilidades conhecidas da W

`npm i --save helmet`

**CSRF** -> tem por função mitigar ataques de solicitação entre sites (conhecida como CSRF ou XSRF) é um tipo de exploração mal-intencionada de um site em que comandos não autorizados

`npm i --save csurf`

**express-rate-limit** -> protege contra ataques de força bruta,

`npm i --save express-rate-limit`

`npm i --save class-validator class-transformer`

**Swagger**

`npm install --save @nestjs/swagger swagger-ui-express`

**TypeORM** -> ORM (Object Relational Mapper) totalmente escrito em TypeScript e funciona muito bem com nestjs
https://typeorm.io/#/

`npm install --save typeorm mysql`

**PG** -> drive do postgres

`npm install pg --save`

dev:
nyc

## Extensões VsCode

**settings-sync** -> sincroniza as configurações do VSCode em todas as maquinas

1. Upload Key : Shift + Alt + U
2. Download Key : Shift + Alt + D

`https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync`

**prettier** -> formata automaticamente o código (use format a file on save)

`https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode`

**tslint** -> indica falhas de formatação

`https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin`

**npm-intellisense** -> autocompleta bibliotecas npm instaladas

`https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense`

**material-icon-theme** -> conjunto de icones

`https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme`

**import-cost** -> informa o tamanho dos pacotes importados

`https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost`

**Bracket-Pair-Colorizer-2** -> colore abertura e fechamento de blocos facilitando a leitura do código

`https://github.com/CoenraadS/Bracket-Pair-Colorizer-2`

**gitlens** -> carregas algumas informações do git, como quem commitou determinada linha ou bloco de código

`https://gitlens.amod.io/`

**todo-highlight** -> Highlight TODO, FIXME and other annotations within your code.

`https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight`

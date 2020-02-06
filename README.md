O objetivo deste projeto é documentar e servir de referência para criação de novos projetos rest que utilizem o framework nest.

Principais cracterísticas:

- Rest;
- TypeScript;
- Jest (teste automatizados);
- Login JWT;
- TypeORM (ORM);
- Postgres (banco de dados);

## NestJS

(https://docs.nestjs.com/)

Nest é um framework escalável com suporte total ao TypeScript. Nest usa um sistema de módulos muito parecido com o do Angular, o que torna seu uso facilitado por quem conhece esse framework. Além disso, Nest usa o express como seu framework HTTP padrão, mas pode ser configurado o Fastify e oferece um CLI que facilita a criação do projeto, modulos, controles etc.

Já tive experiencia com nest em outros projetos, sendo um relativamente grande e, no geral, me atendeu muito bem. Nest tras um padrão de organização e uma série de ferramentas que facilitam a implementação e a padronização de código.

## Instalação

Instalação do CLI do Nest

`npm i -g @nestjs/cli`

Criação do projeto

`nest new nest_reference_project`

## Outras bibliotecas

**As bibliotecas globais ficam configuradas em main.ts configurações dessas bibliotecas**

compression -> diminui consideravelmente o tamanho do corpo das respostas.

`npm i --save compression`

helmet -> pode ajudar a proteger seu aplicativo de algumas vulnerabilidades conhecidas da W

`npm i --save helmet`

CSRF -> tem por função mitigar ataques de solicitação entre sites (conhecida como CSRF ou XSRF) é um tipo de exploração mal-intencionada de um site em que comandos não autorizados

`npm i --save csurf`

express-rate-limit -> protege contra ataques de força bruta,

`npm i --save express-rate-limit`

`npm i --save class-validator class-transformer`

Swagger

`npm install --save @nestjs/swagger swagger-ui-express`

TypeORM -> ORM (Object Relational Mapper) totalmente escrito em TypeScript e funciona muito bem com nestjs
https://typeorm.io/#/

`npm install --save typeorm mysql`

PG -> drive do postgres

`npm install pg --save`

dev:
nyc

## Configurando VsCode

https://desenvolvimentoparaweb.com/javascript/visual-studio-code-javascript-extensoes-plugins/
https://tableless.com.br/10-extensoes-essenciais-para-vs-code/
https://programathor.com.br/blog/top-extensoes-para-vs-code/

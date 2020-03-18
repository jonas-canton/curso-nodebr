# curso-nodebr
Tudo o que foi feito no curso da NodeBR.

O que não é o Node.js?
--> Não é uma linguagem de programação. A linguagem que roda na plataforma é o JavaScript.
--> Não é uma ferramenta para criação de sites simples.
--> Não é um framework JavaScript.
--> Não é uma ferramenta para aplicações no frontend.

O que é o Node.js?
--> Plataforma para criação de aplicações robustas no backend.
--> Ferramenta inicialmente criada para resolver o problema de upload de imagens em 2009 por Ryan Dahl.
--> Usada também para construção de ferramentas de linha de comando.

NPM?
--> Usado para gerenciar as dependências de JavaScript.
--> Identifica as dependências a partir do arquivo package.json.
--> Usado também para executar scripts bash a partir de seu projeto.

https://www.npmjs.com

Comandos

<!-- Para iniciar um projeto -->
npm init
<!-- Para criar com todas configurações padrões -->
npm init -y
<!-- Para rodar um arquivo via Node -->
node <nome do arquivo>.js
<!-- Para rodar o arquivo padrão do "main" descrito no package.json -->
node .

<!-- Podemos criar scripts no package.json. Para rodá-los, basta digitar -->
npm run <nome do script>

Cicli de vida de Promises
--> Pending: Estado inicial, ainda não terminou ou ainda não foi rejeitado.
--> Fulfilled: Quando executou todas as operações com sucesso.
--> Rejected: Quando a operação falhou.

Promises - Async/Await
--> Facilita a visualização do fluxo de funções.
--> Não altera a performance de sua aplicação.
--> Veio do C#.
--> Usar apenas quando necessitar tratar a resposta da chamada.

Event Emitter
--> Usado para ações contínuas.
--> Node.js usa para quase tudo em seu ecossitema.
--> Bastante usado também nos browsers (.onClick).
--> Trabalha sob o Design Pattern Observer/PubSub.
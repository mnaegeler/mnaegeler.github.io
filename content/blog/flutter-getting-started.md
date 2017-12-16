---
title: "Flutter: criando sua primeira tela"
date: 2017-12-14T23:17:00-02:00
draft: false
---

> Flutter para desenvolvedores web

## Starting up

Removido todo o conteúdo do arquivo, insira o conteúdo abaixo:

<script src="https://gist.github.com/mnaegeler/acff78c01d5d436cdd5fa93a4fe6d1ce.js"></script>

Você pode rodar o projeto no emulador Android ou iOS (Control + r).

O primeiro `import` do código, irá importar os Widgets já com estilos Material Design, mais para a frente aprenderemos a modificar os estilos para terem a cara do iOS.

Perceba que no Flutter **tudo é widget**, ou seja, tudo com o que você  trabalhará serão componentes.

Logo abaixo temos a função `main`, que é onde inicia nossa aplicação, juntamente com a chamada `runApp`. São padrões para todas as aplicações.

`MaterialApp` é um Widget também padrão do Flutter que cria a aplicação e também é onde irão as configurações de rotas, páginas, etc. Ali temos declaradas as propriedades `title` e `home`.

A propriedade `home` é usada como uma rota inicial (`/`), caso não haja setada em `routes` (as rotas são declaradas como na web, separadas por `/`). Já a propriedade `title` é somente um título para descrever a aplicação.

Dentro de `home`, assim como nas outras rotas, você poderá começar a construir sua tela. No exemplo temos a chamada do `Scaffold`, que é literalmente o esqueleto, a armação da tela, cada rota poderá ter o seu Scaffold. Dentro do Scaffold é possível colocar os itens fixos da tela, como navegações e botões flutuantes. Ali dentro temos uma `AppBar` que formará a barra superior do aplicativo com o título.

No Scaffold ainda é possível acrescentar outros itens como no exemplo abaixo (**divirta-se!**):

<script src="https://gist.github.com/mnaegeler/19539fa78aa38264728b7f7eaa771d71.js"></script>

Bom, até aqui eu me surpreendi com a facilidade de adicionar esses Widgets na tela e vê-los funcionar sem crise alguma.

Se você vem do Ionic, como eu, verá algumas diferenças de comportamento da `ion-tabs`, que aqui é chamada de `BottomNavigationBar` e não é tomada como navegação principal (não altera o rota) como você verá mais para a frente.

Perceba que os ícones também são widgets, assim como os textos.

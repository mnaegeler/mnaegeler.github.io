---
title: "Flutter: uma introdução ao Flutter framework"
date: 2017-12-12T08:51:13-02:00
draft: false
---

> Flutter para desenvolvedores web

O [Flutter](https://flutter.io) é um framework desenvolvido pela Google e a linguagem usada para desenvolver é o [Dart](https://dartlang.org).

O objetivo desse texto é descobrir a linguagem Dart e o framework, já que vindo do ambiente web fiquei um tanto perdido.

Meu primeiro contato com o Flutter (e com Dart) foi quando estava buscando alternativas para aplicativos mobile, que atualmente uso Ionic. Nessa busca por novas linguagens e ferramentas encontrei React Native, NativeScript e Quasar. Mesmo gostando muito de Vue.js, Quasar foi uma alternativa por pouco tempo, logo percebi que não queria mais trabalhar com híbridos, gosto muito de PWAs, porém num aplicativo eu vou por performance. Já NativeScript e React Native exigem uma curva de aprendizado um tanto grande e muitas vezes as builds quebravam seguindo os tutoriais (sim, os getting started quebravam).

O que mais me chamou atenção desde o início foi que dentro do framework Flutter não é usada nenhuma linguagem de marcação como nos híbridos, React Native e NativeScript, ou seja, você só precisa aprender Dart.

## Instalação

A instalação do Flutter é bastante simples, se seguir o [tutorial deles](https://flutter.io/setup/) você conseguirá ter sua máquina pronta para desenvolver sem crise alguma. Não é necessário usar o Android Studio porém eu indico que use por conta de algumas automações que ele traz para você no início, mas tudo funciona muito bem através da linha de comando se preferir.

## Criando o projeto

Ao abrir o Android Studio (já com os plugins instalados) você poderá iniciar um novo projeto clicando em "Start a new Flutter project".

![Android Studio](/img/android-studio.png)

No próximo menu selecione "Flutter Application" e após configure com o nome do projeto e local a salvar.

## Iniciando

No projeto, os arquivos que iremos desenvolver ficarão na pasta `lib`. Dentro desta pasta você pode ver que já existe um arquivo `main.dart` que é onde nossa aplicação inicia.

Para começarmos, remova todo o conteúdo de exemplo fornecido pelo framework, pois aqui irei te apresentar passo a passo o que acontece em cada parte do código, na melhor forma que encontrei para aprender.

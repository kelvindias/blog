---
title: Aprenda O Basico Sobre Hugo
date: 2021-08-23T04:31:01.544Z
description: Inicie agora mesmo seu site simples com HUGO!
tags:
  - hugo
  - site
  - markdown
---
Hugo, de maneira bem resumida, é um framework para gerar sites estáticos. Bora aprender a criar um site simples e rápido?

<!--more-->

- - -

**INSTALAÇÃO**

Baixar o hugo:

> $ sudo apt install hugo -y

Criar uma pasta para colocar os projetos. Nesse caso eu criei uma pasta chamada "SItes". Logo em seguida, entrar na pasta criada

> $ sudo mkdir Sites
>
> $ cd Sites/

Criando o primeiro projeto de site. Aqui eu chamei de hello-word. Logo em seguida entrar na pasta:

> $ sudo hugo new site hello-world
>
> $ cd hello-world

Baixei um tema para o site diretamente do site do HUGO. Eu escolhi nesse caso o LoveIt.
Para conhecer outros temas, clique [aqui.](https://themes.gohugo.io/)

> $ sudo git clone https://github.com/dillonzq/LoveIt.git

Para criar um novo post

> $ sudo hugo new posts/novo-post.md

Pronto, agora você consegue criar um site estático bonito, moderno e de maneira muito simples. Dentro da pasta onde está o site, navegue para entender qual página você edita. Por exemplo, dentro da pasta *content/posts/* é onde ficam seus posts. O Hugo cria uma página de post vazia e você precisa editar depois.
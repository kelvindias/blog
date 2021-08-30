---
title: “Error Kernel Driver Not Installed (Rc=-1908)” - Virtualbox no ElementaryOS
date: 2021-08-30T16:05:55.625Z
description: Saiba como corrigir o erro “Error Kernel Driver Not Installed
  (Rc=-1908)” do Virtualbox no ElementarOS
tags:
  - erro
  - linux
  - virtualbox
categories:
  - Linux
---
Esses dias instalando o Virtualbox na minha máquina, fui instalar importar o HD da máquina Metasploitable para um laboratório e recebi o seguinte erro “Error Kernel Driver Not Installed (Rc=-1908)”. Vamos resolver ele. 

<!--more-->

Metasploitable, de maneira resumida, é uma máquina linux cheia de vulnerabilidades, colocadas de maneira proposital, para que estudantes a usem como laboratório. 

Eu atualmente tenho testado o Elementary OS 6 e venho gostando. Ainda faltavam algumas coisas para eu poder bater o martelo na decisão de deixar o EOS como definitivo em minha máquina e por isso ainda não tinha instalado algumas aplicações, como o Virtualbox. Mas decidido, fiz a instalação e fui subir um laboratório usando a máquina Metasploitable. Entretanto, ao importar o HD recebi um erro igual a da imagem abaixo:

![“Error Kernel Driver Not Installed (Rc=-1908)”](https://i.stack.imgur.com/zqEoq.png "“Error Kernel Driver Not Installed (Rc=-1908)”")

Fazendo algumas pesquisas, achei a seguinte solução:

> $ sudo apt install build-essential module-assistant
>
> $ sudo m-a prepare
>
> $ sudo /sbin/vboxconfig

Após isso, eu consegui importar o HD e subir meu laboratório. 

Esse post foi bem simples e resumido para que tenham a resolução logo. A causa do problema e sua explicação, ficam para uma próxima talvez. rsrs. Obrigado pela leitura e pela visita ao site.
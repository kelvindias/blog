---
title: Como saber seu IP público via terminal
date: 2021-08-24T22:09:55.006Z
description: "Também é possível saber seu IP público via terminal. "
tags:
  - Linux
  - terminal
categories:
  - Linux
---
Para quem gosta de terminais linux, é muito fácil saber qual o IP da sua interface. Basta um comando e a informação vem prontamente. Mas e quando você quer saber seu IP público, como faz?

<!--more-->

A resposta é muito simples e vou ser direto, para que você já possa usar/testar agora mesmo. A coisa acontece com uma ferramenta chamada ```curl```. Curl é uma ferramenta usada para transferir dados de ou para um servidor. Geralmente é usado com o protocolo HTTP que é um dos que a ferramenta suporta.

Tendo o ```curl``` instalado na máquina, basta usar com algum dos endereços abaixo. O ifconfig.me é o mais conhecido e fácil de executar.

> $ curl ifconfig.me
>
> $ curl icanhazip.com
>
> $ curl ident.me
>
> $ curl ipecho.net/plain
>
> $ curl whatismyip.akamai.com

Pronto. Agora é possível saber seu IP público sem precisar abrir o navegador web. Para quem tem IP fixo é fácil decorar, mas para quem tem IP dinâmico não tem como e vez ou outra precisamos saber nosso endereço público. 

Espero que tenham gostado. Até a próxima.
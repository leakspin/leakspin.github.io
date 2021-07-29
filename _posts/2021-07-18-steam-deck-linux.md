---
title: Steam Deck, Linux y el ecosistema de videojuegos
image: "/assets/images/blog/header_steam_deck.jpg"
layout: post
date: '2021-07-17 02:01:00'
category: blog
author: amora
headerImage: true
hidden: true
tag:
- linux
- noticias
- steam
---

<p style="color: red; font-weight: bold;">
No te olvides de poner mas imagenes y corregir las tildes. Tambien esta puesto el hidden.
</p>

## La Noticia

Hace unos días relativamente, Steam anunció una nueva pieza de hardware totalmente distinta a lo que estamos acostumbrados: el [Steam Deck](https://steamdeck.com){:target="_blank"}.  
Este dispositivo es una mezcla de conceptos, ya que es un dispositivo similar a una GPD Win o una AYA Neo (un PC portatil con forma de consola) pero a un precio competitivo similar al de una Nintendo Switch o una consola de nueva generacion (420€ el precio mas bajo para la zona euro).

<video controls="true" allowfullscreen="true" loop poster="https://cdn.cloudflare.steamstatic.com/steamdeck/images/hero-banner-sequence-cover-spanish.jpg">
    <source src="https://cdn.cloudflare.steamstatic.com/steamdeck/images/video/hero-banner-sequence-spanish.mp4" type="video/mp4">
</video>

## Visión general

Personalmente, estas maquinas me parecen una maravilla. En concreto, esta lo es aun mas, ya que introducir un chip similar al que disponen las consolas de la generación actual (PS5/Xbox Series) en un aparato de 30cm x 12cm, me parece una hazaña increible. Si, va a rendir como una PS4/Xbox One.  
Somos conscientes de la magnitud de la frase anterior? En una **portatil** vas a poder a jugar a juegos como Control o Death Stranding relativamente bien, en bateria, en el transporte publico.

Tambien, para poder hacer eso, vamos a tener un señor *big chungus* entre manos. Es algo mas grande que una Nintendo Switch (OLED o no) y pesa 200g mas que ella... Y se va a notar, porque sera portatil pero mientras la usamos, haremos pesas. Pero mas alla de la proeza de hardware ante la que estamos, queria reenfocar este anuncio sobre algo que se esta fraguando a fuego lento durante muchos años: el ecosistema del videojuego dentro de GNU/Linux. Y, para ello, vamos a tener que ver a los principales actores

## Los Actores del Software

### VALVe

![Gabe Newell en la entrevista con IGN sobre Steam Deck](/assets/images/blog/gabe_newell_steam_deck.jpg)
[via IGN](https://youtu.be/4FXgDAF6QpM)

VALVe ha sido una empresa que desde el principio ha sorprendido con todas las decisiones que ha tomado. Ninguna de las decisiones que ha ido tomando han sido regladas o predecidas en gran medida por nadie. El lanzamiento de una saga tan grande como Half Life le dio muchas alas para crear algo que nadie se esperaba: un alojamiento para tantas desarrolladoras y poder centralizar una tienda para la venta de videojuegos. La revolucion online habia empezado y Steam se habia establecido ya como la plataforma alternativa a las consolas y la venta offline.

Poco despues, el desarrollo de videojuegos vimos que se vio mermado y ya no habia ninguna famosa tercera entrega, si no que simplemente se encargaban de hacer distintos mantenimientos a distintos juegos: DotA2 cambio de sus parches bianuales a anuales con el cambio de temporada (y una revision de fixes durante el año, pero minima en comparacion con el parche gordo), CSGO dejo de tener nuevos desarrollos grandes a simplemente ir introduciendo operaciones, lootboxes y poco mas... De Artifact no hablamos.

Pero, por otro lado, Steam habia empezado a desarrollar hardware: Steam Link, Steam Controller y las Steam Machines. No eran productos normales tampoco: una maquina *tonta* que se conectaba con tu Steam para jugar en remoto, un mando *adaptado* a jugar en PC y el sello de calidad de Steam dentro de PCs reconvertidos en consolas. Muchos fallos ya señalados tuvieron todas estas ideas pero por el camino, se pudo vislumbrar un poco el camino que VALVe queria para su ecosistema: la universalidad.

Que tu tengas un PC te da la libertad de poder instalar y hacer con el lo que te de la gana. Instalar Windows o una distribucion de GNU/Linux esta ahora mismo a golpe de unos pocos clicks, sin mayores dolores de cabeza. Y, como tal, VALVe siempre ha querido aprovecharse de ello. Ademas, desarrollar su propio hardware hace que pueda usar su propio software y poder ahorrarse las costosas licencias de Windows y que luego no puedas modificar su sistema operativo sin que te den dolores de cabeza.

### Steam OS

![Gabe Newell en la entrevista con IGN sobre Steam Deck](/assets/images/blog/SteamOS_Logo.png)   
[via Wikipedia](https://en.wikipedia.org/wiki/SteamOS)

Asi nace Steam OS, una distribucion basada en Debian focalizada en que puedas jugar a todos tus juegos de Steam sin ningun problema. Sus dos primeras versiones han sido... Malas. La salida con las Steam Machines no le dio mucha publicidad, pero es que el SO tampoco ha sido optimizado lo suficiente como para exprimir al maximo. Por experiencia propia.

Que ha cambiado? Sobre todo, el tiempo y la optimizacion del kernel Linux. Eso, unido a que la siguiente version de Steam OS va a estar basada en Arch (muchisimo mas rapido y liviano que Debian), creo que va a ser el golpe de acierto para que Steam Deck pueda funcionar bien.

Un sistema operativo que solo trae problemas y tardanza en actualizaciones oficiales solo hace que no quieras volver a usarlo. Y en un mundo en el que se esta evolucionando bastante, como es el videojuego en Linux, es muy importante ir actualizando con regularidad.

### Vulkan
Mientras Steam desarrollaba e innovaba a partes iguales, las empresas de graficas estaban viendo que hacer con OpenGL. OpenGL es un estandar abierto en el cual se basan las empresas de hardware para que las empresas de software puedan usar APIs comunes y puedan desarrollar para todas las plataformas por igual. El mayor problema es que nadie queria a OpenGL.

![OpenGL odiado por todos](/assets/images/blog/opengl.gif)

**Seguir desarrollando Vulkan sobre OpenGL y las mejoras que trae**

## La union hace la fuerza: Proton

## Steam Deck mola, si, pero tener la posibilidad de jugar en Linux mas

## Que viene en el futuro
# Light/Dark Theme Switcher

This is a simple web application that allows you to switch between a light and a dark theme, using a toggle button.

## Features

- Two different themes: Light and Dark
- Smooth transition between themes, with CSS gradients
- Clouds animation in the background, using CSS animations
- Toggle switch to change between themes



## About the clouds animation

The clouds animation is achieved with a series of cloud images that are positioned absolutely on top of the background. The animation is done with CSS keyframes, and consists of four stages:

- At 0%, the cloud is not visible and is at its normal size.
- At 25%, the cloud becomes visible.
- At 90%, the cloud grows to four times its original size.
- At 100%, the cloud disappears and stays at four times its original size.

The `calc(3s * var(--i))` expression in the animation property is used to delay the start of the animation for each cloud, so that they don't all start at the same time.

## Preview
<p align="center">
  <img src="https://github.com/rafaimn/LIGHT-DARK-Theme-Switch/blob/main/preview/preview.gif" alt="Preview do projeto" />
</p>

<p align="center">
  <a href="https://rafaimn.github.io/LIGHT-DARK-Theme-Switch//">Check it out!</a>
</p>

<hr>


# Mudança de Tema Light/Dark

Este é um aplicativo web simples que permite alternar entre um tema claro e um tema escuro, usando um botão de alternância.

## Funcionalidades

- Dois temas diferentes: Light e Dark
- Transição suave entre temas, com gradientes CSS
- Animação de nuvens em segundo plano, usando animações CSS
- Botão de alternância para mudar entre temas

## Como usar

Para usar este aplicativo, basta abrir o arquivo index.html em um navegador da web.

Clique no botão de alternância no canto superior direito para alternar entre os temas.

## Sobre a animação de nuvens

A animação de nuvens é realizada com uma série de imagens de nuvem que são posicionadas absolutamente sobre o plano de fundo. A animação é feita com keyframes CSS e consiste em quatro estágios:

- A 0%, a nuvem não é visível e está em seu tamanho normal.
- Aos 25%, a nuvem se torna visível.
- Aos 90%, a nuvem cresce quatro vezes seu tamanho original.
- Aos 100%, a nuvem desaparece e permanece com quatro vezes seu tamanho original.

A expressão `calc(3s * var(--i))` na propriedade de animação é usada para atrasar o início da animação para cada nuvem, para que elas não comecem todas ao mesmo tempo.

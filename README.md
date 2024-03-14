# HTML I

No HTML, elementos inline e block são diferentes em termos de como são exibidos na página e como interagem com outros elementos.

### Elementos Inline
Elementos inline, como `<span>` e `<a>`, são exibidos na mesma linha do conteúdo ao qual estão relacionados, ocupando somente o espaço necessário para exibir seu conteúdo. Eles podem ser agrupados juntos e aparecerem em sequência. Elementos inline não quebram a linha automaticamente e não podem ter largura e altura definidas.

### Elementos Block
Por outro lado, elementos block, como `<p>` e `<div>`, são exibidos em uma nova linha e geralmente ocupam toda a largura disponível na sua área de conteúdo pai. Eles podem ter largura e altura definidas e podem ser usados para criar blocos de conteúdo, separando-os visualmente de outros conteúdos. Elementos block são separados uns dos outros verticalmente.

Os elementos block podem conter outros elementos block ou inline, mas elementos inline só podem conter outros elementos inline ou texto. Além disso, elementos block são usados para criar elementos estruturais como seções, artigos, cabeçalhos, rodapés, etc., enquanto elementos inline são usados para destacar partes específicas de um texto, como negrito ou itálico.

### Tags de Mídia
Além das tags apresentadas anteriormente, abaixo estão algumas tags de mídia:

#### Imagem

# Tags de Mídia em HTML

## Imagem

```html
<img src="logoifba.png" alt="Logo do IFBA">

```
A tag <img> é usada para inserir uma imagem na página. O atributo src especifica o URL da imagem e o atributo alt fornece um texto alternativo para a imagem, útil para acessibilidade.

Âncora (Anchor)

```html
<a href="https://www.google.com" target="_blank">Visitar o Google.com</a>

```
## Áudio
A tag <a> é usada para criar links. O atributo href especifica o URL para o qual o link aponta, e o atributo target="_blank" faz com que o link seja aberto em uma nova aba ou janela do navegador.
```html 
<audio controls loop>
    <source src="exemplo-audio.mp3" type="audio/mp3">
    Seu navegador não suporta o elemento de áudio.
</audio>
```

A tag <audio> é usada para incorporar conteúdo de áudio em uma página. O atributo controls adiciona controles de reprodução para o áudio, e o atributo loop faz com que o áudio seja reproduzido em um loop. A tag <source> especifica o URL do arquivo de áudio e seu tipo MIME.

## Vídeo

```html 
<video controls loop>
    <source src="exemplo-video.mp4" type="video/mp4">
    Seu navegador não suporta o elemento de vídeo.
</video>
```
A tag ```html <video> ``` é usada para incorporar conteúdo de vídeo em uma página. Os atributos controls e loop funcionam da mesma forma que para a tag <audio>. A tag <source> especifica o URL do arquivo de vídeo e seu tipo MIME.

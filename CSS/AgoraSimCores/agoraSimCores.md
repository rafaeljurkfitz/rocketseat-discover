# Agora sim, cores.

## Cores

Usamos CSS para alterar cores do nosso documento.

### Tipos

* `background-color` (para caixas);
* `color` (para textos);
* `border-color` (para-caixas);
* outros...

### Valores

Podemos definir os valores por:

* Palavra-chave (`blue`, `transparent`)
* Hexadecimal (`#990011`)
* Funções: `rgb`, `rgba`, `hsl` e `hsla`.

### Exemplos:
```css
element {
    /* Keyword values */
    color: currentcolor;

    /* <named-color> values */
    color: red;
    color: orange;
    color: tan;
    color: rebeccapurple;

    /* <hex-color> values 0-F */
    color: #090;
    color: #009900;
    color: #090a;
    color: #009900aa;

    /* <rgb()> values */
    color: rgb(34, 12, 64, 0.6); /* 0-255 */
    color: rgba(34, 12, 64, 0.6);
    color: rgb(34 12 64 / 0.6);
    color: rgba(34 12 64 / 0.3);
    color: rgb(34.0 12 64 / 60%);
    color: rgba(34.0 12 64 / 30%);

    /* <hsl()> values */
    color: hsl(30, 100%, 50%, 0.6); /* Hue - Saturation - Lumiance */
    color: hsla(30, 100%, 50%, 0.6);
    color: hsl(30 100% 50% / 0.6);
    color: hsla(30 100% 50% / 0.6);
    color: hsl(30.0 100% 50% / 60%);
    color: hsla(30.2 100% 50% / 60%);

    /* Global values */
    color: inherit;
    color: initial;
    color: unset;
}
```
### Referência:
https://developer.mozilla.org/pt-BR/docs/Web/CSS/color_value


## Background

- Define um fundo para o nosso elemento;
- Sua área de atuação e a caixa toda;
- Por padrão, é transparente.

### Exemplos

- Usar cores sólidas;
- Usar imagens;
- Controlar:
    - A posição das imagens;
    - Se elas se repetem ou não;
    - O tamanho delas na caixa.
- Usar cor e imagem juntas;
- Usar cor gradiente.


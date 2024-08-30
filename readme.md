# Projeto de Cartão Interativo com Mudança de Idioma

Este projeto é um exemplo de um cartão interativo que pode girar para mostrar um conteúdo em dois idiomas (Português e Inglês). O cartão pode ser girado de duas maneiras: ao passar o mouse sobre ele (card_hover.html) ou ao clicar nele (card_click.html).

## Funcionalidades

### Português

1. **Giro ao Passar o Mouse (card_hover.html)**
   - Na versão card_hover.html, o cartão girava automaticamente ao passar o mouse sobre ele. Esse comportamento era gerado através do seletor `:hover` no CSS.
   - Ao passar o mouse sobre o cartão, ele rotacionava em 180 graus no eixo Y, revelando o conteúdo do outro lado, que estava em inglês.
   
2. **Giro ao Clicar (card_click.html)**
   - Na versão card_click.html, o comportamento foi modificado para que o cartão gire quando o usuário clicar nele. 
   - O evento de clique é tratado por uma função JavaScript chamada `flipCard()`, que alterna a rotação do cartão entre 0 graus e 180 graus.
   - Quando o cartão gira, ele revela o conteúdo em inglês. Ao clicar novamente, o cartão retorna ao conteúdo em português.

### Inglês

1. **Hover to Flip (card_hover.html)**
   - In the card_hover.html, the card would automatically flip when the mouse hovered over it. This behavior was triggered by the `:hover` CSS selector.
   - When the mouse hovered over the card, it rotated 180 degrees on the Y-axis, revealing the content on the other side, which was in English.

2. **Click to Flip (card_click.html)**
   - In the card_click.html, the behavior was modified so that the card flips when the user clicks on it.
   - The click event is handled by a JavaScript function called `flipCard()`, which toggles the card's rotation between 0 degrees and 180 degrees.
   - When the card flips, it reveals the content in English. Clicking again flips the card back to the content in Portuguese.

## Como Funciona

1. **HTML e CSS**: O layout básico do cartão é feito em HTML e estilizado em CSS. O efeito de rotação é conseguido utilizando `transform` e `perspective`, que criam a ilusão de profundidade.
2. **JavaScript**: A função `flipCard()` controla a rotação do cartão através de uma classe CSS que altera a propriedade `transform`. Isso permite que o cartão gire ao clicar, alternando entre os dois conteúdos de idioma.
3. **Efeito de Transição**: Uma transição suave é aplicada para que o giro do cartão ocorra de maneira fluida, oferecendo uma experiência visual agradável.

**Nota**: Esse exemplo pode ser facilmente modificado para outros idiomas ou para diferentes tipos de conteúdo.

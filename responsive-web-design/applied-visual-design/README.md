# (🔥) Applied Visual Design

- [x] Introduction to the Applied Visual Design Challenges
- [x] Create Visual Balance Using the text-align Property
- [x] Adjust the Width of an Element Using the width Property
- [x] Use the strong Tag to Make Text Bold
- [x] Use the u Tag to Underline Text
- [x] Use the em Tag to Italicize Text
- [x] Use the s Tag to Strikethrough Text
- [x] Create a Horizontal Line Using the hr Element
- [x] Adjust the background-color Property of Text
- [x] Adjust the Size of a Header Versus a Paragraph Tag
- [x] Add a box-shadow to a Card-like Element
- [x] Decrease the Opacity of an Element
- [x] Use the text-transform Property to Make Text Uppercase
- [x] Set the font-size for Multiple Heading Elements
- [x] Set the font-weight for Multiple Heading Elements
- [x] Set the font-size of Paragraph Text
- [x] Set the line-height of Paragraphs
- [x] Adjust the Hover State of an Anchor Tag
- [x] Change an Element's Relative Position
- [x] Move a Relatively Positioned Element with CSS Offsets
- [x] Lock an Element to its Parent with Absolute Positioning
- [x] Lock an Element to the Browser Window with Fixed Positioning
- [x] Push Elements Left or Right with the float Property
- [x] Change the Position of Overlapping Elements with the z-index Property
- [x] Center an Element Horizontally Using the margin Property
- [x] Learn about Complementary Colors
- [x] Learn about Tertiary Colors
- [x] Adjust the Color of Various Elements to Complementary Colors
- [x] Adjust the Hue of a Color
- [x] Adjust the Tone of a Color
- [x] Create a Gradual CSS Linear Gradient
- [x] Use a CSS Linear Gradient to Create a Striped Element
- [x] Create Texture by Adding a Subtle Pattern as a Background Image
- [x] Use the CSS Transform scale Property to Change the Size of an Element
- [x] Use the CSS Transform scale Property to Scale an Element on Hover
- [x] Use the CSS Transform Property skewX to Skew an Element Along the X-Axis
- [x] Use the CSS Transform Property skewY to Skew an Element Along the Y-Axis
- [x] Create a Graphic Using CSS
- [x] Create a More Complex Shape Using CSS and HTML
- [x] Learn How the CSS @keyframes and animation Properties Work
- [x] Use CSS Animation to Change the Hover State of a Button
- [x] Modify Fill Mode of an Animation
- [x] Create Movement Using CSS Animation
- [x] Create Visual Direction by Fading an Element from Left to Right
- [x] Animate Elements Continually Using an Infinite Animation Count
- [x] Make a CSS Heartbeat using an Infinite Animation Count
- [x] Animate Elements at Variable Rates
- [x] Animate Multiple Elements at Variable Rates
- [x] Change Animation Timing with Keywords
- [x] Learn How Bezier Curves Work
- [x] Use a Bezier Curve to Move a Graphic
- [x] Make Motion More Natural Using a Bezier Curve

---

### Propriedade :hover

- O estilo de uma marca de âncora pode ser alterado para seu estado de foco, usando o :hoverseletor de pseudo-classe. Aqui está o CSS para alterar a colormarca de âncora para vermelho durante seu estado de foco:

```
a:hover {
  color: red;
}
```

---

### Cores

As cores têm várias características, incluindo matiz, saturação e luminosidade. O CSS3 introduziu a hsl()propriedade como uma maneira alternativa de escolher uma cor, indicando diretamente essas características.

Matiz é o que as pessoas geralmente pensam como 'cor'. Se você visualizar um espectro de cores começando com vermelho à esquerda, passando pelo verde no meio e azul na direita, o matiz é onde a cor se encaixa nessa linha. Em hsl(), o matiz usa um conceito de roda de cores em vez do espectro, em que o ângulo da cor no círculo é dado como um valor entre 0 e 360.

Saturação é a quantidade de cinza em uma cor. Uma cor totalmente saturada não possui cinza e uma cor minimamente saturada é quase completamente cinza. Isso é dado como uma porcentagem, com 100% de saturação total.

Luminosidade é a quantidade de branco ou preto em uma cor. É fornecida uma porcentagem que varia de 0% (preto) a 100% (branco), onde 50% é a cor normal.

Aqui estão alguns exemplos de uso hsl()com cores de luz normais totalmente saturadas:

Cor	HSL
vermelho	hsl (0, 100%, 50%)
amarelo	hsl (60, 100%, 50%)
verde	hsl (120, 100%, 50%)
ciano	hsl (180, 100%, 50%)
azul	hsl (240, 100%, 50%)
magenta	hsl (300, 100%, 50%)

- `box-shadow` propriedade tem valores para `offset-x`, `offset-y`, `blur-radius`, `spread-radiuse` um valor de cor nessa ordem. Os valores `blur-radius` e `spread-radius` são opcionais.


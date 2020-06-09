# (🔥) Basic CSS

- [x] Introduction to Basic CSS
- [x] Change the Color of Text
- [x] Use CSS Selectors to Style Elements
- [x] Use a CSS Class to Style an Element
- [x] Style Multiple Elements with a CSS Class
- [x] Change the Font Size of an Element
- [x] Set the Font Family of an Element
- [x] Import a Google Font
- [x] Specify How Fonts Should Degrade
- [x] Size Your Images
- [x] Add Borders Around Your Elements
- [x] Add Rounded Corners with border-radius
- [x] Make Circular Images with a border-radius
- [x] Give a Background Color to a div Element
- [x] Set the id of an Element
- [x] Use an id Attribute to Style an Element
- [x] Adjust the Padding of an Element
- [x] Adjust the Margin of an Element
- [x] Add a Negative Margin to an Element
- [x] Add Different Padding to Each Side of an Element
- [x] Add Different Margins to Each Side of an Element
- [x] Use Clockwise Notation to Specify the Padding of an Element
- [x] Use Clockwise Notation to Specify the Margin of an Element
- [x] Use Attribute Selectors to Style Elements
- [x] Understand Absolute versus Relative Units
- [x] Style the HTML Body Element
- [x] Inherit Styles from the Body Element
- [x] Prioritize One Style Over Another
- [x] Override Styles in Subsequent CSS
- [ ] Override Class Declarations by Styling ID Attributes
- [ ] Override Class Declarations with Inline Styles
- [ ] Override All Other Styles by using Important
- [ ] Use Hex Code for Specific Colors
- [ ] Use Hex Code to Mix Colors
- [ ] Use Abbreviated Hex Code
- [ ] Use RGB values to Color Elements
- [ ] Use RGB to Mix Colors
- [ ] Use CSS Variables to change several elements at once
- [ ] Create a custom CSS Variable
- [ ] Use a custom CSS Variable
- [ ] Attach a Fallback value to a CSS Variable
- [ ] Improve Compatibility with Browser Fallbacks
- [ ] Inherit CSS Variables
- [ ] Change a variable for a specific area
- [ ] Use a media query to change a variable

---

### Propriedades de elementos:

- Três propriedades importantes controlar o espaço que rodeia cada elemento HTML: `padding`, `margin`, e `border`.
- Um elemento `padding` controla a quantidade de espaço entre o conteúdo do elemento e o seu border.
- Um elemento `margin` controla a quantidade de espaço entre um elemento `border`e os elementos circundantes.

![Margin and Padding](./imgs/margin-padding.png)

- Seletor de atributos exemplos:

```
[type='radio'] {
  margin: 20px 0px 20px 0px;
}
```

- Pixels `px` são um tipo de unidade de comprimento, que é o que informa ao navegador como dimensionar ou espaçar um item. 
- Os dois principais tipos de unidades de comprimento são absolutos e relativos.
- As unidades absolutas estão vinculadas às unidades físicas de comprimento. Por exemplo, `in` e `mm` consulte polegadas e milímetros, respectivamente.
- Unidades relativas, como `em` ou `rem`, são relativas a outro valor de comprimento. Por exemplo, `em` é baseado no tamanho da fonte de um elemento.


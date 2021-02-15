# CSS Box Model

Every element on a web page is treated a s a box by css.

## Every element has the following

1. **content** : This is the actual text or image or whatever you want to display.

2. **Padding** : It is the internal space between the content and the border for an element. Its the inner fat!

3. **Border** : it surronds an element and is like the skin and its around padding.

4. **Margin** : The space between the elements its the outer most covering of an element.

## Margin Collapsing

In CSS if two adjacennt block elements have  margings they are collapsed and the bigger margin wins. To over-ride this behaviour just explicitly declare `margin-top` or `margin-botton`. More on Margin collapsing here on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing)


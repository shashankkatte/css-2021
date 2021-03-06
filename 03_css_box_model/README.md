# CSS Box Model

Every element on a web page is treated a s a box by css.

## Every element has the following

1. **content** : This is the actual text or image or whatever you want to display.

2. **Padding** : It is the internal space between the content and the border for an element. Its the inner fat!

3. **Border** : it surronds an element and is like the skin and its around padding.

4. **Margin** : The space between the elements its the outer most covering of an element.

## Margin Collapsing

In CSS if two adjacennt block elements have margings they are collapsed and the bigger margin wins. To over-ride this behaviour just explicitly declare `margin-top` or `margin-botton`.

> More on Margin collapsing here on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing)

## Block Level elements

Block elevel elements always take the full available width by default.

The width and height is the width and height avaialble of its coantainer / parent element.

## Box sizing

When you set the width and height of an element, it is only the content height and width. The padding margin border all add up on top of it.

`box-sizing: border-box` is very useful to counter this.

## Strange behaviour of inline-block

Its absolutely dumb but look at the code block here

````html
</div>
      <nav class="main-nav">
        
````

The white space between div and nav is considered an element which causes the nav element to jump to another line

## Pseudo Classes `:`

Pseudo classes help define style of a special state of an element.

## Pseudo Elements `::`

Pseudo elements help define the style for specific part of an element.

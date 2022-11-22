# Positions in CSS

While creating a web page through HTML, we either use a block-level element or an inline-element and by default they are displayed on a web page according to this feature only. We can change the positions of these elements for the purpose of designing or beautifying our web page. To do so we have to use a property of CSS, called as position.

## What exactly is Position in CSS ?
The ```
position
``` property of CSS is used to specify the location/position of the element on the web page. This property helps us to manipulate the location of the element. The ```
top
```, ```
right
```, ```
bottom
```, and ```
left
``` properties determine the final location of positioned elements.

## Types of CSS position
- ### static
Each and every element which we use in HTML has static position by default. If we use ```
position: static;
``` on any element then the location of that element will be according to the normal flow of the page. The position of the element having static value will **not** be affected by ```
top
```, ```
bottom
```, ```
left
``` or ```
right
``` property.

```
/* Syntax */
position: static;
```

- ### relative
Just like static, in this also element will be positioned according to the normal flow of the page. But, for relative ```
top
```, ```
right
```, ```
bottom
``` and ```
left
``` properties will work. When we give some value to any or all of these properties then the position of the element having ```
relative
``` value will change from it's **original position** as per the values of ```
top
```, ```
right
```, ```
bottom
```, and ```
left
```.

```
/* Syntax */
position: relative;
```

- ### absolute
The element having ```
absolute
``` value is removed from the flow of the document. When we give the value absolute to an element then it will be positioned **relative to it's parent**. The final position of the element having value as absolute will be determined by the values of ```
top
```, ```
right
```, ```
bottom
```, and ```
left```.

```
/* Syntax */
position: absolute;
```

- ### fixed
This```
fixed
``` value is similar to ```
absolute
``` position type. Only difference is that when we give ```
fixed
``` position value to any element then the element will be positioned relative to the **document** not the parent. Position of fixed will not change even after scrolling.

```
/* Syntax */
position: fixed;
```

- ### sticky
The element having a ```
sticky
``` value will behave like ```
relative
``` value until the scroll location of the viewport reaches a specified threshold i.e., specified value of ```
top
```, ```
right
```, ```
bottom
```, and ```
left``` and at that point the element will behave as ```
fixed
```.

```
/* Syntax */
position: fixed;
```
Have a look at the below codepen example which consists of all the types of CSS position.
[<iframe height="300" style="width: 100%;" scrolling="no" title="CSS Position" src="https://codepen.io/imbeshat7/embed/ExRQywR?default-tab=result&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/ExRQywR">
  CSS Position</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

Thanks for reading. Happy Learning 🙂





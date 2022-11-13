# CSS Selectors

Let us understand what CSS selector is.
But, before jumping into CSS selector we have to know what exactly CSS is.
## CSS
**CSS (Cascading Style Sheets)** is a stylesheet language which we use to style an HTML document. With the help of CSS we can describe how each element should render on the web page.
## CSS Selectors
Now let's move to CSS Selectors.
First and the most important step of learning & understanding CSS is **targeting** and if we know how to target an element in the HTML file then our job of beautifying/styling our web page becomes easy. And for targeting we need to know about selectors.
### Universal Selector
- Universal Selector is used to select all the elements. Same CSS properties are applied to all the tags when we use this selector. " ```
*
``` " is used to select all the elements of the document.
- Please have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Universal Selector" src="https://codepen.io/imbeshat7/embed/gOKWQzd?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/gOKWQzd">
  Universal Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Individual Selector
- With the help of Individual Selector we can address or select any individual tag of the HTML document.
- It is used when we want to target all the tag of the same type on the web page.
- Please have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Individual Selector" src="https://codepen.io/imbeshat7/embed/QWxvzwb?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/QWxvzwb">
  Individual Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Class and Id Selector
- Class selector is used to select a particular class and id selector is used to select a particular tag having the id mentioned in CSS file.
- " ```
.
``` " is used in CSS before class name for selecting a class and " ```
#
```" is used before id for selecting the desired id.
- Have a look at the below example.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Class and Id Selector" src="https://codepen.io/imbeshat7/embed/poKPqyb?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/poKPqyb">
  Class and Id Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### And Selector (chained)
- And selector or chained selector is used to select a tag which has two or more classes.
- Have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="And Selector" src="https://codepen.io/imbeshat7/embed/bGKWOWd?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/bGKWOWd">
  And Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Combined Selector
- Combined Selector is used when we want to give the same CSS property to more than one tag.
- Have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Combined Selector" src="https://codepen.io/imbeshat7/embed/BaVRvdy?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/BaVRvdy">
  Combined Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Inside an element Selector
- It is used to select a tag which is inside an other element. Space is used between the tags.
- Have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/imbeshat7/embed/zYawyPR?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/zYawyPR">
  Untitled</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Direct Child Selector
- It is used to select tags that are direct children of the first element. " ```
>
``` " is used between the parent tag and child tag.
- Have a look at below example for better understanding.
<iframe height="300" style="width: 100%;" scrolling="no" title="Direct Child Selector" src="https://codepen.io/imbeshat7/embed/bGKWOvp?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/bGKWOvp">
  Direct Child Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

### Sibling  ~ or + Selector
- This selector is used when we want to select sibling of a tag for using CSS property. " ```
+
``` " is used to select an element that is directly after another specific element where as " ```
~
``` " is used to select all elements that are next siblings of a specified element.
- Have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Sibling  ~ or + Selector" src="https://codepen.io/imbeshat7/embed/gOKWZBb?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/gOKWZBb">
  Sibling  ~ or + Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

### Before and After Pseudo Selector
- The ```
:: before
``` pseudo-element is used to insert some content before the content of an element.
- he ```
:: after
``` pseudo-element is used to insert some content after the content of an element.
- Have a look at below example for better understanding.
[<iframe height="300" style="width: 100%;" scrolling="no" title="Pseudo before and after Selector" src="https://codepen.io/imbeshat7/embed/mdKmaYy?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/mdKmaYy">
  Pseudo before and after Selector</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

Thanks for reading. Happy Learning!!





















 
 






# Grid in CSS

## What is Grid?
Grid is a ```
layout module
``` which allows us to create a two dimensional layout system with rows and columns. By using grid layout module we can easily design web pages without using floats and positioning. A grid layout consists of a parent element, with one or more child elements.

## Properties for the Parent (Grid Container)

- ```
display
```: It is used to define the element as grid container.

```
/* Syntax */
.container{
  display: grid;
}
```
[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(display)" src="https://codepen.io/imbeshat7/embed/KKeoNvL?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/KKeoNvL">
  Grid(display)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-template-rows
```: It is used to specify the size of the rows in a grid layout.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-template-rows)" src="https://codepen.io/imbeshat7/embed/eYKMgXy?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/eYKMgXy">
  Grid(grid-template-rows)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-template-columns
```: It is used to specify the size of the columns in a grid layout.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-template-columns)" src="https://codepen.io/imbeshat7/embed/poKLeoW?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/poKLeoW">
  Grid(grid-template-columns)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-template-areas
```: It is used to specify how to display columns and rows, using named grid items.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-template-areas)" src="https://codepen.io/imbeshat7/embed/abKYJEr?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/abKYJEr">
  Grid(grid-template-areas)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-template
```: It is a shorthand property for the grid-template-rows, grid-template-columns and grid-areas properties.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-template)" src="https://codepen.io/imbeshat7/embed/vYrRxPy?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/vYrRxPy">
  Grid(grid-template)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-column-gap
```: It is used to specify the gap between the columns.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-column-gap)" src="https://codepen.io/imbeshat7/embed/zYaWZVg?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/zYaWZVg">
  Grid(grid-column-gap)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-row-gap
```: It is used to specify the gap between the rows.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-row-gap)" src="https://codepen.io/imbeshat7/embed/GRGxmKv?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/GRGxmKv">
  Grid(grid-row-gap)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-gap
```: It is a shorthand property for the row-gap and the column-gap properties.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-gap)" src="https://codepen.io/imbeshat7/embed/MWXVmKR?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/MWXVmKR">
  Grid(grid-gap)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
justify-items
```: Its is used to align grid items in a row. start, end, center and stretch are the possible values for this property.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(justify-items)" src="https://codepen.io/imbeshat7/embed/gOKeWoz?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/gOKeWoz">
  Grid(justify-items)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
align-items
```: Its is used to align grid items in a column. start, end, center, stretch and baseline are the possible values for this property.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(align-items)" src="https://codepen.io/imbeshat7/embed/oNyqWye?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/oNyqWye">
  Grid(align-items)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
justify-content
```: This property is used to align the grid in a row. start, end, center, stretch, space-around, space-between, space-evenly are the possible values of this property.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(justify-content)" src="https://codepen.io/imbeshat7/embed/XWYERxK?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/XWYERxK">
  Grid(justify-content)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
align-content
```: This property is used to align the grid in a column. start, end, center, stretch, space-around, space-between, space-evenly are the possible values of this property.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(align-content)" src="https://codepen.io/imbeshat7/embed/LYrdyXj?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/LYrdyXj">
  Grid(align-content)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-auto-columns
```: It is used to specify a default column size.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-auto-columns)" src="https://codepen.io/imbeshat7/embed/MWXVmda?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/MWXVmda">
  Grid(grid-auto-columns)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-auto-rows
```: It is used to specify a default row size.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-auto-rows)" src="https://codepen.io/imbeshat7/embed/mdKxmZG?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/mdKxmZG">
  Grid(grid-auto-rows)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid-auto-flow
```: It is used to specify how auto-placed items are inserted in the grid.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-auto-flow)" src="https://codepen.io/imbeshat7/embed/zYaWzYZ?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/zYaWzYZ">
  Grid(grid-auto-flow)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


- ```
grid
```: It is a shorthand property for the grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns, and the grid-auto-flow properties.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid)" src="https://codepen.io/imbeshat7/embed/NWzYgGK?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/NWzYgGK">
  Grid(grid)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

## Properties for the Children (Grid Items)
- ```
grid-column-start
```: It is used to specify where to start the grid item.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-column-start)" src="https://codepen.io/imbeshat7/embed/gOKeegE?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/gOKeegE">
  Grid(grid-column-start)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-column-end
```: It is used to specify where to end the grid item.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-column-end)" src="https://codepen.io/imbeshat7/embed/ZERxxKL?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/ZERxxKL">
  Grid(grid-column-end)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-row-start
```: It is used to specify where to start the grid item.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-row-start)" src="https://codepen.io/imbeshat7/embed/oNyqqwy?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/oNyqqwy">
  Grid(grid-row-start)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-row-end
```: It is used to specify where to end the grid item.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/imbeshat7/embed/rNKddzw?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/rNKddzw">
  Untitled</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-column
```: It is a shorthand property for the grid-column-start and the grid-column-end properties.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-column)" src="https://codepen.io/imbeshat7/embed/LYrddOr?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/LYrddOr">
  Grid(grid-column)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-row
```: It is a shorthand property for the grid-row-start and the grid-row-end properties.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-row)" src="https://codepen.io/imbeshat7/embed/KKeooQg?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/KKeooQg">
  Grid(grid-row)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)

- ```
grid-area
```: It	either specifies a name for the grid item, or this property is a shorthand.

[<iframe height="300" style="width: 100%;" scrolling="no" title="Grid(grid-area)" src="https://codepen.io/imbeshat7/embed/gOKeezV?default-tab=css%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/imbeshat7/pen/gOKeezV">
  Grid(grid-area)</a> by Imbeshat Aslam (<a href="https://codepen.io/imbeshat7">@imbeshat7</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>](Link)


Thanks for reading. Happy Learning 🙂


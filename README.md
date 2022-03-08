# REPORT ON CSS FLEXBOX AND GRID

### CSS Grid Layout :

It essentially allows us to create a layout for our page in which we can position HTML elements. Such a layout is created by defining columns and rows, hence the CSS Grid is working with a two-dimensional space.



Sample Code <body> grid-container :
``` 
<body>

<div class="grid-container">
  <div class="grid-item">One</div>
  <div class="grid-item">Two</div>
  <div class="grid-item">Three</div>  
  <div class="grid-item">Four</div>
  <div class="grid-item">Five</div>
  <div class="grid-item">Six</div>  
  <div class="grid-item">Seven</div>
  <div class="grid-item">Eight</div>
</div>

</body>
```
![alt text](https://static.javatpoint.com/csspages/images/what-is-a-css-grid.png)

Row-Gap : The horizontal lines of grid items are called rows.

```
.grid-container {
  display: grid;
  row-gap: 50px;
```

Column-Gap : The vertical lines of grid items are called columns.

```
.grid-container {
  display: grid;
  column-gap: 50px;
```



Basic Grid Layout Patterns :

Format\
Margin\
Flowlines\
Modules\
Spatial zones\
Columns\
Rows\
Markers


### CSS Flexbox Layout :

Flexbox is a one-dimensional layout method for arranging items in rows or columns. Items flex (expand) to fill additional space or shrink to fit into smaller spaces.


Sample Code Flexbox<body>container:
```

<body>

<div class="flex-container">
  <div>a</div>
  <div>b</div>
  <div>c</div>  
</div>
</body>

```

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS21F3qSnb43M6Q_Xdmc9O-Kp0qjQvXpGJTPQ&usqp=CAU)


Basic Flexbox Layout Patterns:

Stretch all\
Stretch middle\
Alternating grid \
3x3 grid\
Vertical bars\
Horizontal bars\
Vertical stack

Flex Properties :

Flex Direction Property : 

The flex-direction property defines in which direction the container wants to stack the flex items.

Flex direction - Column
```
.flex-container {
  display: flex;
  flex-direction: column;
}
```
FLex Direction - Row
```
flex-container {
  display: flex;
  flex-direction: row;
}
```

Flex Wrap Property : 

The flex-wrap property specifies whether the flex items should wrap or not.
```
.flex-container {
  display: flex;
  flex-wrap: wrap;
}

```
Flex Flow Property : 

The flex-flow property is a shorthand property for setting both the flex-direction and flex-wrap properties.

```
.flex-container {
  display: flex;
  flex-flow: row wrap;
}
```

### Grid and Flexbox :

The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time. 


### Uniqueness In Grid And Flexbox:

One Vs Two Dimension:

Grid is made for two-dimensional layout while Flexbox is for one. This means Flexbox can work on either row or columns at a time, but Grids can work on both.\
Flexbox, gives you more flexibility while working on either element (row or column). HTML markup and CSS will be easy to manage in this type of scenario.\
GRID gives you more flexibility to move around the blocks irrespective of your HTML markup.
  
Content-First vs Layout-First:

Major Uniqueness between Flexbox and Grids is that the former works on content while the latter is based on the layout.\
The Flexbox layout is best suited to application components and small-scale layouts, while the Grid layout is designed for larger-scale layouts that are not linear in design.

### Difference Between Grid and Flexbox:

1. Dimensionality and Flexibility:

Flexbox offers greater control over alignment and space distribution between items. Being one-dimensional, Flexbox only deals with either columns or rows.\
Grid has two-dimension layout capabilities which allow flexible widths as a unit of length. This compensates for the limitations in Flex.
  
2. Alignment:

Flex Direction allows developers to align elements vertically or horizontally, which is used when developers create and reverse rows or columns.\
CSS Grid deploys fractional measure units for grid fluidity and auto-keyword functionality to automatically adjust columns or rows.
  
3. Item Management

Flex Container is the parent element while Flex Item represents the children. The Flex Container can ensure balanced representation by adjusting item dimensions. This allows developers to design for fluctuating screen sizes.\
Grid supports both implicit and explicit content placement. Its inbuilt automation allows it to automatically extend line items and copy values into the new creation from the preceding item.

### Conclusion

CSS Grids helps you create the outer layout of the webpage. You can build complex as well responsive design with this. This is why it is called ‘layout first’.
Flexbox mostly helps align content & move blocks.
CSS grids are for 2D layouts. It works with both rows and columns.
Flexbox works better in one dimension only (either rows OR columns).
It will be more time saving and helpful if you use both at the same time.

## References

https://www.w3schools.com/css/css_grid.asp

https://www.w3schools.com/css/css3_flexbox.asp

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout

https://www.youtube.com/watch?v=JJSoEo8JSnc


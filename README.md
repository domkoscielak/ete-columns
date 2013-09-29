Edge To Edge Columns
================

This is a simple solution for a real life problem - inserting an ad hoc (or not only ad hoc) set of columns, which:
* take all available space (100% width of parent)
* each have equal width 
* all have equal space between each other
* first column and last column start / end exactly on the edge of the parent 

###Usage
1. Import the module 

```html
@import 'modules/eteColumns';
```

2. Include the mixin
3. Pass fraction of parent for the column width and percentage for spacing between columns

example 

```html

@include eteColumn(1/3, 2%);

'''
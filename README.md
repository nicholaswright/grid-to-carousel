# grid-to-carousel

A jQuery plugin for transitioning between a Bootstrap grid and carousel.

## Demo

https://nicholaswright.github.io/grid-to-carousel/

## How does it work?

1. Clicking a grid item creates a clone directly on top of it.
2. The clone then expands to cover the grid.
3. The clone is then removed, the grid hidden and the carousel displayed.
4. The carousel's 'active' class is assigned to the slide and indicator with the same index as the grid element so that the correct slide is displayed.  
5. On closing the carousel the close button's index is used to determine the grid item to be targeted.
6. The grid item is cloned, exanded to cover the grid and the carousel hidden and the grid displayed.
7. The clone is then shrunk down to the size and location of the grid item before being removed.

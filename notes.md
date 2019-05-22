# Materialize notes from lecture

## Basic Text Styles

- Default Styles
    1. Container class keeps everything in a central column; determines max-width and width based on screen size. Used with the app <div>
    2. Font is calculated by rem based on the root html element.
    3. Flow text is a special paragraph class used for introductions to paragraph or the first couple of lines to a blog.
        - Font size is increased a bit from the tradition <p>.
        - Based on rem; traditional <p> is a static px.

## Hiding Content

- Classes
    1. Hide: removes display from all screen sizes
    2. Hide-on-small-only: displays on large and medium screens
    3. Hide-on-med-only: displays on large and small screens
    4. Hide-on-large-only: displays on small and medium screens
    5. Hide-on-med-and-down: displays only on large
    6. Hide-on-med-and-up: displays on small


## Colors

- https://materializecss.com/color.html

## Text Formatting

- Classes
    1. Center-align
    2. Left-align
    3. Right-align
    4. Valign-wrapper: aligns text vertically
    5. Truncate


## Buttons

- Classes
    1. btn
        - btn-small
        - btn-large
        - btn disabled
        - bth-floating
            1. pulse
        - waves-effect
        - waves-light
    
- Default color is teal; color can be changed by naming color as the class.


## Icons

- Icons come from the Google API linked in the html
- Classes
    1. material-icons
- Name of icon goes between the <i>
- Icons can be used with button class
    1. Icons on buttons script
        <a href="#" class="btn indigo">
            <span>Send</span>
            <i class="material-icons right">send</i>
        </a>
     2. Icons on floating button script
        <a href="#" class="btn-floating light-blue pulse">
            <i class="material-icons">add</i>
        </a>


## Grids

- Classes
    1. Row
    2. Col: for column width
    3. s(number): how many columns per small screen and up
    4. s(number) m(number) l(number) x(number): number determines width of the column, letter determines screen size 

- Every grid has to be surrounded by the row class
- Every grid defaults to 12 columns

## Depth and Shadows

- Depth is controlled by using z-depth class with a number. Number determines how far from the screen the shadow appears. 
    1. script example
        class="z-depth-2"


## Modals

- jQuery needed
- d
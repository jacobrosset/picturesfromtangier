<h1 style = "color:blue"> Syled Heading </h1>

selector {
    property:value;
}

selector
    p
    h1
    Id
    Class



Internal style sheet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style> 
        
    </style>



External style sheet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">

!important

properties:
    color
    font
    font-family: Helvetica, Courier, Verdana, 'Comic Sans MS'
    font-style: normal, italic, oblique
    font-variant:normal, small-caps
    font-size: xx-small, x-small, small, smaller, medium, larger, x-large, xx-large, large, Use pixel(20px, 35px, 80px), percentages(from default)
    text-align: left, right, center, justify(tries to use as much space as possible)

    color: 
    background color: 

    alignment

    line-height

Serif font - bad 
Sans Serif font - good

@font-face{
    font-family: mySpecialFont
    src: url('Colleen.ttf);
}

h1{
    font-family:mySpecialFont;
}


float
clear

block - take up as much height as needed 
in-line - take up as much width and height as needed
in-line block
none

Using overflow:
visible
hidden
scroll
auto


Table
Grid
Flexbox

display:Table
display:table-cell


display:
visible
hidden
collapse(only for table elements)






Inspect element

Use contrast checker for the color blind peeps

h1 background-color(entire width of the page)
span background-color(only the element)



div - block
p - block

Display: grid;
grid-template-columns:500 px;

Parent Element > Set it to Grid

display: grid;
grid-tempalte: 200 px, 200px, 200 px;
grid-tempalte: 30%, 30%, 30%;
grid-column-start:
grid-column-end:


grid-template-rows
align-items
row-gap
column-gap


display: flex;
flex-direction: column;
Flex-wrap: wrap-reverse, wrap;


height: 600 px;

flex-flow:
row-gap
align-items
shrink
grow
order
display
font-weight
widthpassing
text-decoration

a:link
a:visited
a:hover
a:focus
a:active

There is a bit of an error on this slide. The precedence of rules listed on this slide are correct for a:link and a:active. However, they are incorrect for a:visited. The correct precedence of rules is listed below: 

a:hover MUST come after a:link and a:visited

a:active MUST come after a:hover

list-style-type
list-style-image
list-style-position
list-style


CSS selectors that follow the Document
Descendant selectors
Child selectors
Adjacent sibling(same level and follow each other)

ID selectors #
class selectors .



Which of these rules will only style images that are in the footer?


Universal selector * 
Attribute selector
pseudo classes
pseudo elements


Using operators:
^ = match the beginning exactly
$ = match the end exactly
* = wildcard

nav a {
    text-decoration: none;
}

justify-content: space between

skip to main content

.current {
text-transform: uppercase;
}

padding
margin
border

body {
    background: lightblue url("shadows.gif") 100% no-repeat;
}

Browser prefixes

column-count
border-radius
gradient
caniuse.com

Default sytle sheets

background-repeat, background-position, and background-size (to name a few). You can use these properties to position your image.

Opacity

background-image
background-size
background position





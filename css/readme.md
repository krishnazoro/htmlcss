# Css basics

## Providing css

1. There are three types of styles

- Inline style

- Internal style

- External style

### Inline style

1. Inline style means applies style directly applies to the element in the program.

2. example:

```
<h1 style = "color:blue";>Hi Krishna</h1>

```

### Internal style

1. Internal style means applies style to the element by class or open style tag in the head tag and mention element and applies the styles.

2. Example

```
<head>
<style>

p{
    color: red;
}
</style>
</head>

```

### External style

1. External style means applies style to the element by external file.

2. The current file and external file is linked together by hypertext link at header.

```

<head>
<a href="link">

```

## Normalize css

1.  Normalize.css is a customisable CSS file that helps browsers render all elements more consistently and in line with modern standards.

## Selectors

1. Selectors is used to style the element by using

- Type

- Id

- Class

- Attribute

### Type

1. We can style an element by type.

2. like an example

```

body{
    color: blue;

}

```

### Id

1. we can style an element by using id.

2. We use a # symbol for tag Id.

3. We can use id name in program for a style.

4. example #idname.

5. In id we can give name for at one time, we can't repeat it.

```

#product{

 color: green

}

```

### Class

1. we can style an element by using class.

2. We use a . symbol for tag class.

3. We can use class name in program for a style.

4. example .className.

5. In class we can repeat name many times.

```
.product{

    color: red;
}

```

### Attribute

1. We can style an element by using attribute.

2. Example

```
a[href = "link"][target_blank]{

}

```

## Relational selector

1. In relational operator means in the operator will use >, +, ~ at relational selector

- Greaterthan symbol(>) selector

1. This symbol highlight or color the paragraph by using this but it just we can color the 1st paragraph in the section.

```
css

# idname > p{
    color:red;
}
```

- Additional symbol(+)

1. This symbol highlight or color the paragraph after the end of section but only the first paragraph.

```
css

# idname + p{
    color:red;
}
```

- Tick symbol(~)

1. This symnol highlight or color the paragraph after the end of the section.

```
css

# idname ~ p{
    color:red;
}
```

## Pseudo-class selector

1. Pseudo class selector is used to style part a part of web page based on certain condition.

2. USe single colon : for style particular thing in web page.

3. Here there are certain condition for style the webpage.

- Hover

- Focus

- nth-child()

- first child() and last child()

### Hover

1. When we keep cursor on content it has some changes like changing font color, background color etc..

2. like example:

```

p:hover{
    background-color: cadetblue;
    color: cornsilk;
}

```

### Focus

1. When you click the content it has some chages like font color,background color etc...

2. like example

```

p:focus{

    color: darksalmon;
    border-color: blue;
    background-color: yellow;
    outline: none;

}

```

### nth-child()

1. In web page they have n no.of content like table cells, paragraph we can style it by using this selector we can choose it by even nunbers and odd numbers.

2. like example

```

 article > p:nth-child(odd){

    font-size: 16px;
    color: black;
    font-style: italic;

}

```

### First child and last child

1.  In web page they have content like table cells, paragraph we can style it by using this selector at first and last.

2.  like example

```

 article > p:first-child{

    font-size: 16px;
    color: black;
    font-style: italic;

}

article > p:last-child{

    font-size: 16px;
    color: black;
    font-style: italic;

}

```

### first-of-type

1.This element is style the first content of the webpage.

2. Like example

```

 article > :first-of-type{

    font-size: 16px;
    color: black;
    font-style: italic;

}

```

### Last-of-type

1. This element is style the last content of the webpage.

```
article > :last-of-type{

    font-size: 16px;
    color: black;
    font-style: italic;

}

```

## pseudo element selector

1. Pseudo element is used to style the first letter.

2. In pseudo element double colon :: has been used.

- First-letter

- First line

### First letter

1. It style only first letter in paragraph.

2. like example.

```

p::first-letter{
    font-weight: bold;
    font-style: italic;
}


```

### First-line

1. It style only the first line.

2. Like example

```

p::first-letter{

    font-weight: bold;

}

```

### Selection

1. When you select the content we can change the by using the selection.

2. Like example

```

::selection{
    background-color: darkgreen;

}

```

### Before

1. When you want to add a any symbols before content use this before element .

2. like example

```
p::before{
    content: "...";
    dispaly: block;
<!-- Block means block level starts at new line -->
}

```

### After

1. When you want to add a any symbols after content use this after element .

2. Like example.

```
p::after{
    content: "...";
    dispaly: block;

    <!-- Block means block level starts at new line -->
}

```

## Selector specificty

1. If i repeating style in different methods it apply consider the weight of the method

2. They are 3 types of selector specificty

- Id selector

- class and atribute selector

- Element selector

### Id selector

1. It has high weightage in styling in coding and it uses id tag for styling.

2. Example

```

#super{
    color: coral;
}

```

### Class and atribute selector

1. It has less weightage then id selector it has second preference and it uses class and atribute for styling.

2. Like example

```

.superman{
    color: cadetblue;
}

```

### Element selector

1. It has less weightage then id and class and it has third preference for coding and it uses element for styling.

2. Example

```

h1{
    color: green ;
}

```

### ! Important

It is a attribute it gives first preference in styling.

```

h1{
    color: green !important;
}

```

## Inheritance

1. If there is a sentence and apply any attribute in middle of the sentence and if i apply a style to the paragraph it will not apply to the attribute.

2. Example

```

<p>Lorem ipsum <strong>dolor</strong>  sit amet.</p>

<css>

p{
    color: yellow;
    border: solid blueviolet;
    font-size: larger;
}

strong{
    color: initial;
    border: inherit;
}

```

## Color

1. The color is used to decrote a words and background and highlight.

2. There are four types

- Named color

- Rbg

- Hsl

- Hexadecimel

### RGB

1. The rgb is abbrevation of red,green,blue.

2. The rgb has some value that is start at zero to 255.

3. For example: "130,205,124" each number reperesent the the value of color.

4. And then there will be a Rgba, "a" defines alpha and this value can be zero and one.

5. Zero defines transparent and one defines opacity.

```

css
Rgb(130,205,124)

or

Rgba(130,205,124)

```

### Hexadecimel

1. It contain values (0-9,a-f) it does not has transparent.

2. For example
```
css
 #e6cd10

```

### HSL

1. HSL is a abreviation of hue saturation lightness.

2. Even it has three value start from zero to hundred, the first value start at degree and then the two more value is use percentage.

3. Like example:Hsl(25deg,45%,87%)

4. H defines the value of the color and s defines saturation of the color and finally l defines lightness of the color.

5. Even it has Hsla "a" defines alpha the value alpha is decimel number zero and one.

6. Zero for transparent and one for opacity.

7. Like example:

```

css
 Hsl(25deg,45%,87%,)

 or

 Hsla(130,205,124,0.6)

```
## Gradients

1. Gradients we can beautiful transition with two or more color it is techincally image.

2. We can use at background 

```

css
background: linear gradient(white,yellow)

```

## Border

1. Border is used to decorate the box at the end corners.

2. There are many types dotted,dashed,solid etc..

3. We can decorate it we can give border at any sides.

```

css
border: 20px;

```
---
# Layout

## Box model

1. The box model is more important topic Whenever give the content it was placed at invisible at content area.

2. And the content area was sorrounded by padding and it covered by border and it is covered by margin.

## Sizing elements

1. Sizing elements in web development is like deciding how big or small you want the boxes, pictures, or other parts of your webpage to be

## Overflow

1. If a box has 150px height and width the content has more than a box capacity then the content will overflow.

2. There are some solution 

- Hidden

- scroll

- auto

- auto hidden

### Hidden 

1. If the content is overflow in the box if use hidden property the exrtra content will hidden.

```

css
  overflow:hidden ;

 ```

 ### Scroll

 1. If the content is overflow in the box if use scroll property the exrtra content will come to the box we can see it buy scrolling.

 ```

css
  overflow: scroll;

```

### Auto

1. If the content is overflow in the box if use auto property the exrtra content will come to the box we can see it buy scrolling.

```

css
  overflow: auto;

```

### Auto hidden

1.  If the content is overflow in the box if use auto hidden property the exrtra content will hidden.

```

css
  overflow: auto hidden;

```

## Measurement units

1. Measurement units used measure the pictures,boxes,margin and border etc...

2. There are two types of measurement units 

- Absolute

- Relative

### Absolute

1. It is fixed measurement and it cannot changable it is fixed at any screen size.

2. There are many absolute measurements units

- Pixel(px)

- Point(pt)

- Inch(in)

- Centimeter(cm)

- Millimeter(mm)

### Relative

1. It is not fixed type it changable like screen size.

2. There are many relative measurements units.

- Percentage(%)

- Relative to the viewport (vw)

- Relative to the viewport (vh)

- relative to the font size (em)

- relative to the font size (rem)

## position

1. Positioning is used to position the container.

2. The "rem" measurement units is used for position the container.

3. There are three position

- Relative

- Absolute

- Fixed

### Realative

1. Relative to the element's normal position.

### Absolute

1. Relative to the parent.

### Fixed 

1. Relative to the viewport.

## Floating element

1. A floating element in web design is a way to position an element to the left or right of its container, allowing other content to wrap around it.

2. This is done using the CSS float property

3. Example program in css

```

float: left;
clear: both;

```

## Flex box

1. Flex means it arrange the container in one direction like in horizontal or vertical direction.

2. We can control the direction by flex-direction attribute.

3. To align item we need to learn about axes flex.

4. There are two types of alignment

- Main(primary)

1. In row main will be horizontal axes.

2. In coloumn main will be vertical axes.


- Cross(secondary)

1. In row main will be vertical axes.

2. In coloumn main will be horizontal axes.


### Aligning items

1. There 2 types of align items

- Justify-content(along the main axis)

- align item (along the cross axis)

- align content 

2. Using for spacing and align perfectly.

### Align wrap

1. In Wrap the items will keep original size and extra item cannot be fixed it keep the item perfectly.

### Align self 

1. It align the container to start part or end part.

### Sizing items 

1. There are four types in sizzing items.

- Flex-basis(the initial size of a flex item)

- Flex-grow(the growth factor)

- Flex-shrink(the shrink factor)

- Flex (it is a shortend method)


6. Like example css

```
css

Display: flex;

```      

## Grid

1. It arrange the content in both rows and coloumns most it was in tables, pictures.

2. Like example

```

Css

Display: grid;

Grid-template: repeat(4,100px) / (3,100px)


```

3. In grid template repeat(4,100px) for rows and (3,100px) for column.

### Alignment items

1. In grid aligning items was used there are two types.

- justify item

- align item

### Gap

1. The gap three types 

- Row gap

1. This gap is used in row.

- Column gap

1. This gap is used in column.

- Gap

1. This is a short hand method this applicable for rows and column.

### Placing items

- Grid row

- Grid columns

- Grid area

## Hiding element

1. The hidding element means hide the visiblity of the content.

2. There are two attribite are used in hiding element 

- display: none;

- visiblity: hidden;

## Media queries

1. Media queries there are many media's like moblie media, desktop media,tab media.

2. The website is changes like what the display size it is called as responsive web sites.


## Styling fonts

1. The fonts is used to style the content like paragraph.

2. There are three types of fonts

## Serif

1. Serif has sharp edges in the first letter 

- Georgia

- Times new roman

2. Like example: Georgia, Times new roman, serif;

### San-serif

1. San serif has no sharp edges

- Avenir

- Arial

- Futura

2. Avenir, Arial, san-serif; 

### Monospace

1. Monospace it has one space at letter and width of ever letters is exactly same.

- Consoles

- Courier

- Ubuntu

2. Like example: Consoles, Courier, Monospace;

## System Font stack

1. The advantage of the system font stack.

- Can boost performance

- Native look

- No flash of unstyled text (FOUT)

- Overall: better experience

2. Disadvantage of the system font stack

- Default font vary 

## Vertical spacing

1. The vertical spacing also called as vertical rthym.

2. There are two properities

- Margin

- line-height

### Margin

1. Margin is used at top, left, right, bottom gap between the sentence.

### Line-height

1. Line height is used at gap between the first sentence and second sentence.

2. Don't use px in line height use rem.

## Horizontal spacing

1. There are three properities in the horizontal spacing

- Letter spacing

- Word spacing

- Width

### Letter spacing

1. Letter spacing is defined space between each characters in the word.

2. Use px in the letter spacing don't use rem.

### Word spacing

1. word spacing is defined as space between set of character in the sentence.

### Width 

1. Width is defined as relative to the zeros (space between each words to another words).

## Formating text

There are few properities in the formating text

- Text align 

1. most left side in text align

- Text indent: 

1. A space will appear in the first paragraph first sentence 

- Text decoration

1. we can use underline or line through in the paragraph

- Text transform

1. we can change font style in the the transformation

- White space

In White space there is nowrap will be used there is no next line, it finish the sentence in the single line.

- column

we can seperate the column 

- Direction

we can change the direction like right to left etc...
 







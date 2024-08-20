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

1. Internal style means applies  style  to the element by class or open style tag in the head tag and mention element and applies the styles.

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

1. This symbol highlight or color the  paragraph after the end of section but only the first paragraph.

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

1. Pseudo class selector is used to style part a part of web apge based on certain condition.

2. USe single colon : for style particular thing in web page.

2. Here there are certain condition for style the webpage.

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

2. like example

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

1.This element is  style the first content of the webpage.

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




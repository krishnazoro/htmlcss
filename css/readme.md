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
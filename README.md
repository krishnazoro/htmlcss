# Part - 1        

# Web development fundamentals

## Introduction

You learn

1. The languages and tools of web development.

2. And key concepts(eg URL,HTTP,DOM,etc).

3. How websites works.

4. Inspect network traffic using Devtools.

5. Bascis of html and css.

6. Validating webpages.

## Languages and tools of web development

1. Web development has two parts

- Front end

- Back end

## Front end

1. In browser page we can visualy see icons and the page is front end.

2. The front end development use

- Html(Hyper text markup language)

- Css(cascading stylesheets)

- Javascript

### Html

1. It has set of content and image, symbols and some buttons like bell, likes, comment, dislike for a website.

### CSS

1. It allign the content, images, symbols and buttons in a formate.

2. It can change the font style, image shape and change the color of the font.

### Javascript

1. It is a behavior language if uou touch the buttons like bell button it make some sound and if touch the likes button it make that any colors

### Framework

1. Frameworks or library come with a lot of code that can reuse in a websites so that can get jobs done faster.

- React js (library)

- Angular js (Framework)

- Vue js (Framework)

### Library

1. Library does not contain everything like framework.

2. If we need anything we can create a library.
    eg: React js (it most popular languge used)

### Version control system

1. we use version control system to keep track on our project history work collaborative with others

2.  They are many version of the version control system

- Git (70% of the company using git)

- Subversion

- Mercurial

## Back end

1. It store the data and database for front end and it stored at server.

2. The back end development use

- java

- Node js

## Full stack

1. The combination of front end and back end.

## How the web works

1. For example: http://www.codewithmosh.com

2. The address are stored in the browser address bar is called URL (uniform resource locator).

3. Resource is locate on the internet.

4. Resource can be

- Webpage (also can Html document)

- Images

- Video

- Fonts

5. when you type the url in browser and hit enter there are two pieces works.

- The browser and also called as client 

- Server

6. Client request a service and server provide the service.

7. HTTP is used to talk client to server and this not a programming language plain text communicating on internet.

8. We know the HTTPS which is HTTP + encryption so the client and server messagesare encrypted.

9. Example of HTTP message with this messages,the browser tells server what look'ing for "Get /index.html HTTP/1.1".

10. It says get file or page name of index.html by using HTTP version 1.1.

11. The client send a message to server and the server will figure it out and send back the message to the client .

12. The client send a message to the server is called HTTP request and the server send message to the client HTTP client.

## Html basics

1. The body structure of the html.

    ```
    <!DOCTYPE html>
    <html>
    <head>
    <title> My first program </title>
    </head>
    <body>
    <p>This is my first program</p>
    <img src = " ">
    </body>
    </head>
    ```

2. Html is start at `<!DOCTYPE html>` it defines the version of the html.

3. `<html>`is used for because of html program without this tag the program will not run.
4. `<head>` in the head we can use a another tag called `<title>` in this title tag we can give title of the of the webpage page it will dispaly at left side upper corner and then close the head `<head>` tag .
5. we can add a body `<body>` tag after the head tag we can give pragraph `<p>` tag and add link tag, img, video, audio etc..
6. After completation of the body content close the body `<body>` tag.
7. After completation program close the `<html>`.
8. If we need a gallery image, audio, video in vs code store the image in a path.

## Css basics

1. In css we can make a sharp image as softer and the make it circle.

2. We can make a font style and bold.

3. If there are two `<p>` and `<p>` we want make one paragraph style we can use class which parargraph you need.
   for example

    ```
    <!DOCTYPE html>

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>First web page</title>
        <style>
            img {
                width: 200px;
                border-radius:80%;
            }
            p{
                font-style:italic;

                font-size: larger;
            }
            .krishna{
                font-weight:bolder ;
            }
        </style>


    </head>
    <body>
        <p>Music Director</p>

    <img src ="rahman wallpaper.jpg">
    <p class = "krishna"> Marakuma Nenjam </p>
    </body>
    ```

## Formatting code

1. Formatting code means code in a proper format.

2. Example for formatting code.

  ```
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Document</title>
   </head>
   <body>

   </body>
   </html>
  
  ```

 ## Validaring web page

 1. Validating web page means if we sucessfully created the webpage we need to upload the web page in the internet.

 2. we need to check there is any error or problem in the web page. 

 3. There are many platform to check those problem but i prefore validation.w3.org . 

---

# Html basics

## Head section

1. The head section of th e html page is

   ```
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Document</title>
   </head>
   <body>

   </body>
   </html>
    ```

2. `<!DOCTYPE html>`is used to identify the version type and it give the template for the html.

3. `<meta charset="UTF-8">`Character Encoding: It specifies the character encoding for the HTML document. `UTF-8`: UTF-8 (Universal Character Set + Transformation Format—8-bit) it is used widely character encode all the set of character including emoji and various character are using world wide.It dispaly all the character, symbols and emoji's properly.

4. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`the meta tag name is viewport the viewport is used to display webpage visible area a of display.

5. `<content="width=device-width>`it display the webpage width of the webpage i mean the webpage is fit for the screen.

6. `initial-scale=1.0`it is a natural size or initial zoom 1.0 means the natural fit for dispaly.

## Text
 
1. Text part is mostly used in body tag in paragraph`<p>`in the paragraph tag the stress emphasis `<em>`is used to give more important for the text which is inside the `<em>`.

2. And `<i>` is used for italic and bold `<b>` is used for bold a content.

3. The text it can store the content in different style and in proper formate 

## Entities

1. Entities is used to create a special notation start with a &; and end with &;.

2. it is used in paragraph like an example.
 ```
 <p> this is a &lt; html &gt;
 o/p:
 <html>
 
 ```
 3. In this we can use 
 - &copy,euro,dollar,pound,copy,reg,amp,quote,apos.
 
 - `&nbsp;` - it is called as non-braking space. 

 ## Hypertext link
 
 1. we can use a link in website is known as hypertext link `<a>` anker tag has been used and href is used as attribute.
 
 2. syntax of the hypertext link

 ```
 <a hypertext="link">name for the link</a>
 
 ```
 3. By using hypertext link we can send a mail and jump key.

 4. By using jump we can go top but there is no key for go bottom

 ## Images

 1. We can create a image by using website or local, the element of the image is `<img>` tag and the attribute is src and alt.

 2. In image we can stye the image like we can change height, width, size. 

 ## Audio
 
 1. we can create a audio by using website or local file, the element of the audio is `<audio>`tag and the attribute is src and controls. 

 2. In audio we can stye the image like we can change height, width, size. 

## Video

 1. we can create a video by using website or local file, the element of the video is `<video>`tag and the attribute is src and controls. 

 2. In video we can style the image like we can change height, width, size. 

 ## List

 1. List is used to list something record of short pieces.

 2. There are two types in html

 - Unordered list
 
 - Ordered list

 ### Unordered list
 
 1. In unordered list just use bullet points,star etc... like many symbols for the list

 ```
 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unordered list</title>
    <style>
    ul{
        list-style-type: square;
    }
</style>
</head>

<body>
    <ul>
        <li>Front end</li>
        <li>Back end</li>
        <li>Front end
            <ul>
                <li>Html</li>
                <li>Css</li>
                <li>Js</li>
            </ul>
        </li>
    </ul>
</body>

</html>

```

 ### Ordered list
 
 1. In ordered list use a numbers,alphabets,roman letters etc.. for the list.

 ```
 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unordered list</title>
    <style>
        ol {
            list-style-type: upper-roman;
        }
    </style>
</head>

<body>
    <ol>
        <li>Front end</li>
        <li>Back end</li>
        <li>Front end
            <ol>
                <li>Html</li>
                <li>Css</li>
                <li>Js</li>
            </ol>
        </li>
    </ol>
</body>

</html>

```
### Description list

1. We can give a description for the list and we can style it.

```<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Description html</title>
    <style>
        dl {
            font-weight: bolder;
            font-size: x-large;
        }

        dd {
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
    </style>
</head>

<body>
    <dl>Black coffee</dl>
    <dd>Look like a black</dd>
    <dl>Cold Coffee </dl>
    <dd>The coffee is cold</dd>
</body>

</html>

```

## Table

1. Table is used to arrange the data in rows and colums

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>table</title>
    <style>
       table,td,th{
        border: 1px solid black;
        border-collapse: collapse;
        padding: 5px;
        }
         tr:nth-child(even){     
        background-color: cadetblue;
         }
         <!-- nth child means we can give style for n no.of row in the table, we need to mention the odd or even or row number -->
    </style>
</head>

<body>
    <table>
        <thead>
            <tr>
                <th colspan="2">Menu</th> 
            </tr>
           <!-- colspan is used to a  word is use n no.of row ,we want mention  the number. EG: colspan = "2"  -->
            <tr>
                <th>Food</th>
                <th>Cost</th>
            </tr>
        </thead>
        <tbody>
        <tr>
                <td>Idli</td>
                <td>200</td>
            </tr>
            <tr>
                <td>Dosa</td>
                <td>2000</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Total</th>
                <th>2200</th>
            </tr>
        </tfoot>


    </table>
</body>

</html>

```
## Container

1. `<div>` is used in the container it is a block-level-element.

2. It is start at new line.

3. We can give a style for the element.

## Class

1. It is a attribute.

2. We can give a name for class

3. By using the name we can give specific style for by using the class.

## Span 

1. It is a inline element.

2. We can give a style by using this.

## Semantic

1. Semantic means element which has meaningful words.

2. Like an example

- Body tag

- Head tag

- Article tag

- Form tag

- Table tag

etc..

3. We using article tag in the sematic

4. Article element is a semantic element. 

5. An independent, self contained content

- Forum post

- Review

- Comments

- Porduct cards

## Structure of the webpage

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    <header>
    <nav>
    <ul></ul>
    <li></li>
    <li></li>
    <li></li>
    </nav>
    </header>
    <main>
    <article>
        <section></section>
    </article>
    </main>
    <aside>
        <p></p>
    </aside>
    <footer>
    <nav>
        <ul></ul>
        <li></li>
        <li></li>
    </nav>
    </footer>
    
</body>
</html>
```
### Header

1. Header is used for introduction to show the topic's 

### Navigation bar

1. Navigation bar presented in the top of the website beolw the title bar.

2. In navigation bar has menue or other topics

### Ul

1. Ul means unordered list it has only symbols like dot,square,circle.

### Main 

1. It contain main content of the webpage.

### Article 

1. It can represent the content like article.

### section 

1. A group of content in a seperate section.

### Aside 

1. a group content seperated and will be part of side.

### Footer

1. It is used to represent any at botom of the webpage.

---

# CSS Basics

## providing CSS

1. CSS that is used to a make a beautiful the webpage and we can give different sentence and each for words for different styles.

2. There are three styles

- Embedded styling sheets

- Inline

- External

## Basic selector

1. The basic selectors

- Type

- ID

- Class

- Attribute

2. Example by attribute

```
                                   HTML sheet

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Selector</title>
    <link rel="stylesheet" href="./basicSelector.css">
</head>

<body>
    <a href="https://google.com">google</a>
</body>

</html>
```

```
                            Embedding style CSS

a[href]{
    color: green
}
```

## Relation selector

1. In relation selector we use styles using symbols like

- Greater than symbol (>) - In a section or article tag there two or more paragraph by using this we can color first one paragraph in the section

- Plus symbol (+) - After a section or aricle there are two or more paragraph we can style the first paragraph after that tag. 

- Tilde symbol (~) - It select all the paragrph after the tag elements. 

2. For example 

- Wrote the program in HTML sheet

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Relation Selector</title>
    <link rel="stylesheet" href="./relationSelector.css">
</head>

<body>
    <article id="products">
        <p>Lorem ipsum dolor sit amet.</p>
        <section>
            <p>Lorem ipsum dolor sit amet.</p>
        </section>
    </article>

    <p>Lorem ipsum dolor sit amet.</p>
    <p>Lorem ipsum dolor sit amet.</p>

</body>

</html>

```

- Wrote the in Embedding style sheet

```
                              Greater than  

#products > p{
    color: red;
}
```

```
                                  Plus  

#products + p{
    color: red;
}
```

```
                                 Tidile  

#products ~ p{
    color: red;
}
```

## Pseudo class selectors

1. A CSS pseudo-class is a keyword that can be added to a selector, to define a style for a special state of an element.

2. Some common use for pseudo-classes:

- Style an element when a user moves the mouse over it.

- Style visited and unvisited links differently.

- Style an element when it gets focus.

- Style valid/invalid/required/optional form elements.

- Style an element that is the first child of its parent.

3. Pseudo-classes are always denoted by a single colon (:) followed by the pseudo-class name:

4. For example

```
a:hover{
    color:blue
}
```

5. For HTML links, it is common to use the following pseudo-classes:

- :link - Styles unvisited links

- :visited - Styles visited links

- :hover - Styles an link on mouse over

- :active - Styles an activated link

- :first child - Styles the article and section content

- :first-of-type - Styles the article and section first       content

- :last-of-type - Styles the article and section last      content

6. For example

```

article p:first-of-type {
    color: red;
} 

article p:last-of-type {
     font-weight: bold;
}

ul li:nth-child(even){
    color: palevioletred;
}

/* a:visited{
    color: green; 
}*/

a:hover{
    color:red;

}

a:active{
    color:blueviolet
}

a:focus{
    background-color: yellow;
}

```

## Pseudo elemnt selectors

1. A CSS pseudo-element is a keyword that can be added to a selector, to style a specific part of an element.

2. Some common use for pseudo-elements:

- Style the first letter or first line, of an element

- Insert content before or after an element

- Style the markers of list items

- Style the user-selected portion of an element

- Style the viewbox behind a dialog box

3. Pseudo-elements are denoted by a double colon (::) followed by the pseudo-element name:

- ::first-letter - style the first letter

- ::first-line - style the first line

- ::selector - style the content which content has been selected like drag.

- ::before - style the content before

- ::after - style the content after

4. For example

```

p::first-letter{
    font-size: 120%;
    font-weight: bolder;
}

p::first-line{
  color: brown;
}

::selection{
   
    color:bisque
}

::before{
    content:"...";
    display: block;
}

::after{
    content:"...";
   
}

```

## Selectors specficity

1. In CSS there are four tag 

- Id tag

- Class tag

- Atribute tag

- Element tag

2. If i use all the tag in one content you know which tag gives more important.

3. consider the triangle the first importance for id tag and for class and atribute tag and finally for element tag.

4. If i use all the tag in one content it gives important for id tag but i need to give important for element tag you need to need to type important aside the tag.

5. For example

```
h1{
    color: yellow !important
}
```

## Inheritance

1. There is a style sentenced we can remove the style on any words that's called an inheritance.

## Gradient

1. A style we can mix two or more colors that makes a image stylish.

2. Make this steps is easy use gradient generator.

3. There are two types of gradients 

- Linear-gradient

- Radial-gradient

4. For example

```
.box{
    width: 300px;
    height:300px;
    background:linear-gradient(red,yellow,blue);
} 

.box{
    width: 800px;
    height:900px;
    background:radial-gradient(red,yellow,blue);
}
```

## Border

1. We can style the border using give different measurement and make radial shape and colors.

2. we can style the border measurement called trbl means top,right, bottom and left.

3. For example

```
.box{
    width: 400px;
    height:400px;
    background: burlywood;
    border:  dashed black 10px;
    border-radius: 100px;
    border-width: 10px 20px 30px 40px;//trbl
}
```

## Shadow

1. Shadow can style a image, box and text it makes that 3d view.

2. we can make a different color and gives different smoothnes.

3. shadow should represent as number measure of px and there three numbers should should for shadows to represent right or left, top or bottom and finally smoothnes.

3. First number for right or left for shadow positive number represent a shadow to right side and negative number for left  side.

5. Second number for top or bottom positive number represent a shadow to bottom and negative number for top.

6. Third number for softening the shadow if the value increase the shadow will be soften and the value decrease the shadow is harder.

7. For example

```
.box{
    width : 400px;
    height: 400px;
    background: lightblue;
    box-shadow:10px 10px 5px lightslategray
}

h1{
    text-align: center;
    text-shadow: 2px 2px 5px black;  
    
}
```
8. In .box the box-shadow:10px 10px 5px the first number 10px is positive number so the shadow will represent in right side and second number 10px is positive shadow represent bottom and the third numbers is 5px the value is lower so the shadw will be harder. 

---

# Part - 2

# Layout

## Box model

1. In CSS, the box model used whent talking about web desining and layout.

2. The CSS box model is essentially a box that wraps around every HTML element.

3. Every box consists of four parts: content, padding, borders and margins.

4. Consider the box, content is wrapped by padding and padding is wrapped by border and wrapped by margin.

5. Explanation of the different parts (from innermost part to outermost part) they are

6. Content - The content of the box, where text and images appear.

7. Padding - Clears an area around the content. The padding is transparent.

8. Border - A border that goes around the padding and content.

9. Margin - Clears an area outside the border. The margin is transparent.

10. The initial margin is 16, and the border, padding is 0. We can set border, padding and margin manually in CSS.

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>Lorem ipsum dolor sit amet.</p>
</body>
</html>

```

## Sizing element

























# Web development fundamentals

## Introduction

You learn

1. The languages and tools of web development.

2. And key concepts(eg URL,HTTP,DOM,etc).

3. How websites works.

4. Inspect network traffic using Devtools.

5. Bascis html and css.

6. Validating webpages.

## Languages amd tools of web development

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

1.  It has set of content and image, symbols and some buttons like bell, likes, comment, dislike for a website.

### CSS

1.  It allign the content, images, symbols and buttons in a formate.

2.  It can change the font style, image shape and change the color of the font.

### Javascript

1.  It is a behavior language if uou touch the buttons like bell button it make some sound and if touch the likes button it make that any colors

### Framework

1.  Frameworks or library come with a lot of code that can reuse in a websites so that can get jobs done faster.

- React js (library)

- Angular js (Framework)

- Vue js (Framework)

### Library

1.  Library does not contain everything like framework.

2.  If we need anything we can create a library.
    eg: React js (it most popular languge used)

### Version control system

1.  we use version control system to keep track on our project history work 
collaborative with others

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

1.  The combination of front end and back end.

## How the web works

1.  For example: http://www.codewithmosh.com

2.  The address are stored in the browser address bar is called URL (uniform resource locator).
3.  resource is locate on the internet.
4.  resource can be

- webpage (also can Html document)

- Images
- Video
- Fonts

5.  when you type the url in browser and hit enter there are two pieces works.


- Browser also called as client
- Server


6.  Client request a service and server provide the service.

7.  HTTP is used to talk client to server and this not a programming 
language plain text communicating on internet.
8.  We know the HTTPS which is HTTP + encryption so the client and server messagesare encrypted.
9.  Example of HTTP message with this messages,the browser tells server what look'ing for "Get /index.html HTTP/1.1".
10. It says get file or page name of index.html by using HTTP version 1.1
11. The client send a message to server and the server will figure it out
    and send back the message to the client .
12. The client send a message to the server is called HTTP request and the server send message to the client HTTP client.

## Html basics

1.  The body structure of the html.

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

3. `<html>`is used for because of html program without this tag the program will run.
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

## Format code

1. Format code is used to for make code in a proper format.

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

1. Entities is used to create a special notation start with a & and end with ;.

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

 ## Images

 1. We can create a image by using website or local, the element of the image is `<img>` tag and the attribute is src and alt.

 2. In image we can stye the image like we can change height, width, size. 

 ## Audio
 
 1. we can create a audio by using website or local file, the element of the audio is `<audio>`tag and the attribute is src and controls. 

 2. In audio we can stye the image like we can change height, width, size. 

## Video

 1. we can create a video by using website or local file, the element of the video is `<video>`tag and the attribute is src and controls. 

 2. In video we can stye the image like we can change height, width, size. 

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

2. We can give a style by useing this.

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








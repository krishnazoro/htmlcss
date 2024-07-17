# Web development fundamentals
You learn 
1. The languages and tools of web development.
2. And key concepts(eg URL,HTTP,DOM,etc).
3. How websites works.
4. Inspect network traffic using Devtools.
5. Bascis html and css.
6. Validating webpages.

# Languages amd tools of web development
1. Web development has two parts
- Front end
- Back end

## Front end
1. In browser page we can visualy see  icons and the page is front end.
2. The front end development use 
 - Html(Hyper text markup language)
 - Css(cascading stylesheets)
 - Javascript

 ### Html
 1. It has set of content and image, symbols and some buttons like  bell, likes, comment, dislike for a website.
 
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
 2. They are many version of the version control system
 - Git (70% of the company using git)
 - Subversion
 - Mercurial

## Back end
1. It store the data and database for front end and it stored  at server.
2. The back end development use
- java
- Node js

## Full stack
 1. The combination of front end and back end.

 # How the web works
 1. For example: http://www.codewithmosh.com
 2. The address are stored in the browser address bar is called URL (uniform resource locator).
 3. resource  is locate on the internet.
 4. resource can be
  - webpage (also can Html document)
  - Images
  - Video
  - Fonts
 5. when you type the url in browser and hit enter there are two pieces works.
 - Browser also called as client
 - Server
 6. Client request a service and server provide the service.
 7. HTTP is used to talk client to server and this not a programming language plain text communicating on internet.
 8. We know the HTTPS which is HTTP + encryption so the client and server messagesare encrypted.
 9. Example of HTTP message with this messages,the browser tells server what look'ing for "Get /index.html HTTP/1.1".
 10. It says get file or page name of index.html by using HTTP version 1.1
 11. The client send a message to server and the server will figure it out
 and send back the message to the client .
 12. The client send a message to the server is called HTTP request and the server send message to the client HTTP client.

 # Html basics
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
6. Html is start at  `<!DOCTYPE html>` it defines the version of the html.
7. `<html>`
8. `<head>` in the head we can use a another tag  called `<title>` in this title tag we can give title of the of the  webpage page it will dispaly at left side upper corner and then close the head `<head>` tag .
9. we can add a body `<body>` tag after the head tag we can give pragraph `<p>` tag  and add link tag, img, video, audio etc..
10. After completation of the body content close the body `<body>` tag.
11. After completation program close the `<html>`.
12. If we need a gallery image, audio, video in vs code store the image in a path. 

# Css basics
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

# Formate code
1. Format code is used to for make code in a proper format.
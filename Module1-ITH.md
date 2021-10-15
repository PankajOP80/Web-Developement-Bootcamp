# Introduction to HTML(Hyper Text Markup Language)
```HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript)."Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements" such as <head>, <title>, <body>, <header>, <footer>, <article>, <section>, <p>, <div>, <span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li> and many others.An HTML element is set off from other text in a document by "tags", which consist of the element name surrounded by "<" and ">".  The name of an element inside a tag is case insensitive. That is, it can be written in uppercase, lowercase, or a mixture. For example, the <title> tag can be written as <Title>, <TITLE>, or in any other way.```

### _WEB DEVELOPEMENT BOOTCAMP MODULE 1_
___
<!-- ol-->
<!-- blockquote -->
__1.Tags that I learned in this Module:-__
 <!-- Tables-->
 |Tags   |Function|
 |-------|--------|
 | h1  to h6|This element represent six levels of section headings. < h1 > is the highest section level and < h6 > is the lowest.|
|< hr >   |Element represents a thematic break between paragraph-level elements: for example, a change of scene in a story, or a shift of topic within a section.Its like a < br > tag and does not have end tag.|
 |< meta charset="UTF-8" >|The < meta> HTML element represents metadata that cannot be represented by other HTML meta-related elements, like < base >, < link >, < script>, < style> or < title>. In this line we are telling all the text in document is encoaded using utf-8 encoaded systeam. This is the standard encoading that you should be using in html file.|
 |< p > |The <  p > HTML element represents a paragraph.|
 |< em >| It italisize the text.|
 |< strong >|Its use for bold the text. The < strong> HTML element indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.|
 |< ul >| The < ul > HTML element represents an unordered list of items, typically rendered as a bulleted list.|
 |< li > |The < li> HTML element is used to represent an item in a list. It must be contained in a parent element: an ordered list (< ol>), an unordered list (< ul>), or a menu (< menu>). In menus and unordered lists, list items are usually displayed using bullet points. In ordered lists, they are usually displayed with an ascending counter on the left, such as a number or letter.|
 |< img >|The < img> HTML element embeds an image into the document.|
 |< a>|The < a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.Content within each < a> should indicate the link's destination. If the href attribute is present, pressing the enter key while focused on the < a> element will activate it.|
 <!-- ol-->
 <!-- blockquote -->
__2.Important sites to help yourself while studying:-__
<!-- Links -->
[W3schools](https://www.w3schools.com/html/)

[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
<!-- ol-->
<!-- blockquote -->
**3.First website main code**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pankaj's Personal Site</title>
</head>
 <body>
   <img src="C:\Users\Pankaj Naik\Desktop\Web Developement\HTML- Personal Site\Images\Naruto.png" alt="Pankaj Profile Picture">  
  <h1>Pankaj Naik</h1>      
  <p><em>Founder and CTO of <strong><a href="https://www.appbrewery.co/">The App brewery.</a></strong></em></p>
  <p>I am an IOS and App Developer. I love cofee and brew my own beers.</p>
  <hr>
  <h3>Books And Teaching</h3>
  <ul>
      <li>Complete iOS App Developement Bootcamp</li>
      <li>Complete Web Developement Boodcamp</li>
  </ul>
  <a href="Hobbies.html">My Hobbies</a>
  <a href="Contact-me.html">Contact Me</a>
 </body>
</html>
```
<!-- blockquote-->
___internal website codes___
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h3>My Hobbies</h3>
    <ol>
        <li><a href="https://www.bikewale.com/"> Bikes</a></li>
        <li>Watching Movies</li>
        <li><a href="https://developer.mozilla.org/en-US/"> Coading</a></li>
    </ol>  
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact me</title>
</head>
<body>
   <h1>My contact details</h1> 
   <p>My fictional address</p>
   <p>Mobile no:38742998274</p>
   <p>myemail@gmail.com</p>
</body>
</html>
```
<!-- codeblock -->
**Website Output**


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pankaj's Personal Site</title>
</head>
 <body>
   <img src="C:\Users\Pankaj Naik\Desktop\Web Developement\HTML- Personal Site\Images\Naruto.png" alt="Pankaj Profile Picture">  
  <h1>Pankaj Naik</h1>      
  <p><em>Founder and CTO of <strong><a href="https://www.appbrewery.co/">The App brewery.</a></strong></em></p>
  <p>I am an IOS and App Developer. I love cofee and brew my own beers.</p>
  <hr>
  <h3>Books And Teaching</h3>
  <ul>
      <li>Complete iOS App Developement Bootcamp</li>
      <li>Complete Web Developement Boodcamp</li>
  </ul>
  <a href="Hobbies.html">My Hobbies</a>
  <a href="Contact-me.html">Contact Me</a>
 </body>
</html>

<!-- blockquote-->
___

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h3>My Hobbies</h3>
    <ol>
        <li><a href="https://www.bikewale.com/"> Bikes</a></li>
        <li>Watching Movies</li>
        <li><a href="https://developer.mozilla.org/en-US/"> Coading</a></li>
    </ol>  
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact me</title>
</head>
<body>
   <h1>My contact details</h1> 
   <p>My fictional address</p>
   <p>Mobile no:38742998274</p>
   <p>myemail@gmail.com</p>
</body>
</html>

__```Now you can see how you can really easily start to create multiple pages of your website and as long you got under the same folder you can specify the path for browser to get to it.Then you can start your home page linking with all of these different satellite pages and you start to build up website rather than just a webpage```__


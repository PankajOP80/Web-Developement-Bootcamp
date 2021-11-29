# Introduction To CSS
## WEB DEVELOPEMENT BOOTCAMP MODULE 3
---
<!-- blockcode-->
#### ___In this module I have learned about CSS (Cascading style Sheet) to level up our website. The only purpose of CSS is that to style the markup languages.___.
---
#### **Important Notes** 

 <!-- Ul -->
* Inline CSS is used to apply CSS on single element. It is written as value using style attribute of element/tag. 
* Internal CSS is used to apply CSS on a single document or page. It is written inside the <style> …</style> tag within head section of html.
* External CSS is used to apply CSS on multiple pages. The CSS code is written in a CSS file (.css) and similar included/linked in HTML documents.These files are called as stylesheet.
* No website is completely unstyled. Even before we added CSS code to our index.html thereis some ready default CSS being applied to your browser.
---

#### **Website main code:**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pankaj's Personal Site</title>
    <link rel="stylesheet" href="CSS/style.css">

    

</head>
 <body>
     <table cellspacing="20">
         <tr>
             <td> <img src="C:\Users\Pankaj Naik\Desktop\Web Developement\HTML- Personal Site\Images\Naruto.png" alt="Pankaj Profile Picture">  </td>
             <td><h1>Pankaj Naik</h1>      
                <p><em>Engineering Student<strong><a href="https://www.bing.com/search?q=Pune&cvid=e4d3028c7d8f4bcd91e9940fae53da4a&aqs=edge..69i57j0l8.4216j0j1&pglt=43&FORM=ANNTA1&PC=ASTS">Pune College.</a></strong></em></p>
                <p>I am an IOS and App Developer. I love tea and creating new things.</p></td>
         </tr>
     </table>
<hr>
  <h3>Books And Teaching</h3>
  <ul>
      <li>Complete iOS App Developement Bootcamp</li>
      <li>Complete Web Developement Boodcamp</li>
  </ul>
<hr>
  <h3>Work Experience</h3>
  <table cellspacing='10'>
      <thead>
         <tr>
             <th>Dates</th>
             <th>Work</th>
         </tr>
      </thead>
      <tbody>

      </tbody>
      <tr>
          <td>2010-2015</td>
          <td>Lead developer at PokemonLegends app.</td>
      </tr>
      <tr>
          <td>2010</td>
          <td>Researcher at the Institute Of Cognitive Neurosciences</td>
      </tr>
  </table>
  <hr>
  <h3>Skills</h3>
  <table cellspacing='10'>
      <tr>
          <td>iOS Developement </td>
          <td>⭐⭐⭐⭐⭐</td>
      </tr>
      <tr>
        <td>Web Developement </td>
        <td>⭐⭐⭐⭐⭐</td>
    </tr>
    <tr>
        <td>Photography</td>
        <td>⭐⭐⭐</td>
    </tr>
  </table>
  <hr>
  <a href="Hobbies.html">My Hobbies</a>
  <a href="Contact-me.html">Contact Me</a>
 </body>
</html>
```
<!-- blockquote-->

####  ___Internal folder codes___
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact me</title>
    <link rel="stylesheet" href="CSS/style.css">

</head>
<body>
   <h1>My contact details</h1> 
   <p>My fictional address</p>
   <p>Mobile no:38742998274</p>
   <p>myemail@gmail.com</p>
   <hr>

   <form action="mailto:infothem56@gmail.com" method="post" enctype="text/plain">
       <label for="">Your Name:</label>
       <input type="text"><br>
       <label for="">Your Email:</label>
       <input type="email"><br>
       <label for="">Your message:</label><br>
       <textarea name="" id="" cols="30" rows="10"></textarea>
       <input type="submit">
   </form>
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
    <title>Document</title>
    <link rel="stylesheet" href="CSS/style.css">

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
####  ___STYLESHEET CODE___
```

        body {
            background-color: #C2FFF9;
        }

        h1 {
            color: blueviolet;

        }

        h3 {
            color: blueviolet;   
        }

        hr {
           
            border-style: dotted none none;
            border-color: blue;
            border-width: 5px;
            width: 5%;
        
        }

        img {
            height: 200px;
        }
  ```
  #### **2nd Website main code:**
  ```
  <!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Bacon Fansite</title>
  <link rel="stylesheet" href="css/styles.css">
</head>

<body>
  <h1 id="heading">I Love Bacon</h1>
  <p>bacon, bacon, bacon, bacon, bacon, bacon</p>
  <p>bacon, bacon, bacon, bacon, bacon, bacon</p>
  <p>bacon, bacon, bacon, bacon, bacon, bacon</p>
  <img class="bacon" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/285/bacon_1f953.png" alt="bacon-img">
  <img class="broccoli" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/285/broccoli_1f966.png" alt="broccoli-img">
</body>

</html>
```
####  ___STYLESHEET CODE___
```
/*********************Tag Selectors********************/

h1 {
    color: red; font-size: 200px;
}


img:hover {
    background-color: gold;
}


/*********************Tag Selectors********************/

.bacon{
    background-color: green;
}

.broccoli{
    background-color: red;
}

/*********************ID Selectors********************/

#heading{
    color: rgb(139, 67, 0);
}
```

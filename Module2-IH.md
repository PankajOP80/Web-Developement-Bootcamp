# Intermediate HTML
### _WEB DEVELOPEMENT BOOTCAMP MODULE 2_
---
<!-- blockcode-->
#### __In this module, I have learned about the remaining elements of HTML and their different attributes. And how to host website on internet using Github. Web hosting is an online service that allows you to publish your website onto the internet so, anyone who has access to the internet has access to your website__

___
___
<!-- ol-->
<!-- blockquote -->
#### __1.Tags that I learned in this Module:-__
___
 <!-- Tables-->
 |Tags   |Function|
 |-------|--------|
 |< table >|The < table > HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.|
|< tr  > |The < tr > HTML element defines a row of cells in a table.|
 |< td >|The < td > HTML element defines a cell of a table that contains data.|
 |< thead >|The < thead > HTML element defines a set of rows defining the head of the columns of the table.|
 |< tbody >|The < tbody > HTML element encapsulates a set of table rows (< tr > elements), indicating that they comprise the body of the table (< table >)|
 |< th >|The < th > HTML element defines a cell as header of a group of table cells. |
 |< tfoot > |The < tfoot > HTML element defines a set of rows summarizing the columns of the table.|
 |< form >|The < form > HTML element represents a document section containing interactive controls for submitting information.|
 |< label >|The < label > HTML element represents a caption for an item in a user interface.|
|< input >|The < input > HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The < input > element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.|
___

 <!-- ol-->
 <!-- blockquote -->
 #### **2.Website link(Output):**
 <!-- Links -->
[HTML-Personal Site](https://pankajop80.github.io/CV/)



<!-- ol-->
<!-- blockquote -->
#### **3.Website main code:**

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
___

# Ex.06 Book Front Cover Page Design
## Date:29.11.2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>

<head>
    <title>BOOK COVER</title>
    <style>
        .bookpage{

            width: 400px;
            height: 700px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(tech.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:palevioletred;
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:bisque;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 25px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
           
        }
        .pub{
            color:palevioletred;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:olive;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:lavender;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: Verdana;
            position: relative;
            top: 30px;
        }
        .mypic{
            position: relative;
            top: 275px;
            left: 320px;
            width: 70px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                PROGRAMMING 
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>THE ART OF PROGRAMMING LANGUAGE</h1></div>
            <div class="subtitle">
            <b> "PROGRAMMING ISN'T ABOUT WHAT YOU KNOW;
             IT'S ABOUT WHAT YOU CAN FIGURE OUT."</b>
     
            </div>
            
            <div class="mypic">
                <img src="img.jpg" width="70" height="80" >
            </div>
            <div class="id">
                <hr style="color:olive">
            </div>
            <div class="author">
               <p><b>KAVIYA D</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>FIRST EDITION</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:



<img width="960" alt="book" src="https://github.com/KAVIYADHARANI/cover/assets/144870680/95a97325-1e06-4943-b40e-8405b57c1079">

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

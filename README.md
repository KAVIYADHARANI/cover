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
    <title>CHANGES CAN BE BEAUTIFUL</title>
    <style>
        .bookpage{

            width: 400px;
            height: 650px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cover1.jpg);
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
            color:cornflowerblue;
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
            color:cornflowerblue;
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
            color:azure;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: Verdana;
            position: relative;
            top: 40px;
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
                BUTTERFLY
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>CHANGES CAN BE BEAUTIFUL</h1></div>
            <div class="subtitle">
                 "TO IMPROVE IS TO CHANGE;
                 <br>
                 TO BE PERFECT IS TO CHANGE OFTEN."
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

![Alt text](bc.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

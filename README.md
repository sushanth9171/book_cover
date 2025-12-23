# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        header{
            background-color:grey;
        } 
        body
        {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .book{
            width: 500px;
            height: 740px;
            background-color:#241E1F;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content:space-between;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            font-family: Arial, sans-serif;
        }
        .book-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .author-name {
            font-size: 13px;
        }
        .name{
            color: #64CAD8;
            font-size:70px ;
            text-align: center;
            font-family:Helvetica Bold,Impact, Haettenschweiler, 'Arial Narrow Bold';
        }
        .name1{
            color: #64CAD8;
            font-size: 50px;
            font-family: Arial, Helvetica, sans-serif;
        }
        .for{
            font-size: 30px;
            font-family:Arial, Helvetica, sans-serif;
        }
        .book,.name,.name1,.for{
            margin: 0;
            line-height: 1;
        }
    </style>
</head>
<body>
    <div class="book">
        <div></div>
        <div class="book-title">Bulid Data-Driven Solutions Using R</div>
        <div class="name">DATA<br>SCIENCE</div>
        <div class="for">-------for--------</div>
        <div class="name1">FUNDRAISING</div>
        <div><img src="book.jpg" width="300" height="350"></div>
        <div class="author-name">ASHUTOSH NANDESHWAR,Phd | RODGER DEVINE, MS</div>
        <div>  </div>
    </div>
</body>
</html>

# OUTPUT:
<img width="260" height="387" alt="image" src="https://github.com/user-attachments/assets/48c98ff3-4e3f-4876-acaf-3dcfe1593702" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
# Date:02/12/2024
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

# PROGRAM:
```
<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 100px;
            font-family: ' Arial, sans-serif';
            background-image: url("c:\\Users\\admin\\Downloads\\ghost.avif");
            background-size: cover;
        }
            
        .author{
        
            display: inline;
            position: relative;
            color:rgb(0, 0, 0);
            top:430px;
            font-family:Georgia;
            font-size:large;
        }
        .descript{
        
        display: inline;
        position: relative;
        color:rgb(120, 3, 3);
        top:200px;
        
        font-family:Georgia;
        font-size: medium;
        }
        .booktitle{
            color:rgb(0, 0, 0);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
    
        .subtitle{
            color:rgb(0, 0, 0);
            font-family:unicorn;
            font-size:larger;
            position: relative;
            top:60px;
        }
        
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            
            <div class="booktitle">
                <h1 style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; color: rgb(251, 2, 2);"> THE PARANORMAL THINGS</h1></div>
            <div class="subtitle" style="text-align: center;color: rgb(4, 51, 81);">
                 STORIES  ABOUT  PARANORMAL  THINGS
            </div>
            <div class="subtitle" style="color: rgb(130, 32, 32);text-align: center;">
                 GHOST X SCIENCE
            </div>             
            <div class="author" style="color: rgb(255, 255, 255);text-align:center;">
                --ALBERT SK--
            </div>
            <div class="descript" style="color: rgb(205, 21, 5);text-align: center;">
            DON'T READ THIS BOOK ALONE
            </div>
            
        </div>
        </body>
        

</html>
```
# OUTPUT:
![Screenshot 2024-11-25 112932](https://github.com/user-attachments/assets/27fd6405-055b-4069-88de-54c0ff426764)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
# Date:04/11/2024
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
```python
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book cover</title>
</head>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 100px;
            font-family: ' Arial, sans-serif';
            background-image: url("/static/ghost.avif");
            background-size: cover;
        }
            
        .author{
        
            display: inline;
            position: relative;
            color:rgb(0, 0, 0);
            top:350px;
            left: 140px;
            font-family:Georgia;
            font-size:30px;
        }
    
        .booktitle{
            color:rgb(0, 0, 0);
            font-family: Roquen;
            font-size: 25px;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
    
        .subtitle{
            color:rgb(0, 0, 0);
            font-family:unicorn;
            font-size:25px;
            position: relative;
            top:60px;
        }
        .img{
            position: relative;
            top: 220px;
            right: 90px;
        }
    </style>
      
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
        <div class="author" style="color: rgb(255, 0, 0);text-align:center;">
             AUTHOR--ALBERT
        </div>
        <div class="img">
        <img src="/static/Screenshot 2024-12-07 005546.png" width="150" height="150">
        </div>
    </div>
</body>
        

</html>
```
# OUTPUT:
![Screenshot 2024-12-07 125643](https://github.com/user-attachments/assets/c3b790f8-6a77-478e-8e5e-fe8d333e71c2)



# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

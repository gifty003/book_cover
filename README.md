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

# PROGRAM:
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: white;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(back.png);
            background-size: cover;
        }

        .insight {
            color: white;
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: white;
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: white;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="hrstyle">
            <hr style="color: white;">
        </div>
        <div class="booktitle">
            <h1>In Search of Lost Time </h1>
        </div>
        <div class="subtitle"></div>
        <div class="mypic"><img src="C:\Users\91904\Pictures\23014087(LATERAL ENTRY)AIDS_GIFTSON.png" width="130" height="145" alt=""></div>
        <div class="id">
            <hr style="color: white;">
        </div>
        <div class="author">
            <p><b>BY GIFTSON RAJARATHINAM N</b></p>
        </div>
        <div class="pub">OPEN >>></div>
        <div class="ed"><b>Special Edition</b></div>
    </div>
</bodY>

</html>
```
# OUTPUT:
<img width="1479" height="785" alt="Screenshot 2025-11-27 010319" src="https://github.com/user-attachments/assets/fd52f55c-0b82-478d-b494-52bc337e401d" />


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

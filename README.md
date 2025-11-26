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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover</title>

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body{
            background: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, Helvetica, sans-serif;
        }

        .cover{
            position: relative;
            width: 550px;
            height: 800px;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.6);
        }

        .cover img.bg{
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: brightness(0.45); /* Darken for readable text */
        }

        /* Main title */
        .title-block{
            position: absolute;
            top: 120px;
            left: 40px;
            color: white;
        }

        .title-block h1{
            font-size: 48px;
            line-height: 1.1;
            font-weight: 800;
            text-transform: uppercase;
        }

        .title-block p{
            margin-top: 10px;
            font-size: 20px;
            opacity: 0.9;
        }

        /* Edition */
        .edition{
            position: absolute;
            bottom: 150px;
            left: 40px;
            color: rgb(16, 219, 212);
            font-size: 24px;
            font-weight: bold;
        }

        .edition hr{
            margin-top: 8px;
            width: 180px;
            border: none;
            border-top: 2px solid rgb(16, 219, 212);
        }

        /* Name */
        .author{
            position: absolute;
            bottom: 80px;
            left: 40px;
            font-size: 28px;
            color: white;
            font-weight: bold;
        }

        /* Character image */
        .character{
            position: absolute;
            bottom: 40px;
            right: 30px;
            width: 180px;
            height: 250px;
        }

        .character img{
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
    </style>
</head>

<body>

    <div class="cover">
        <!-- Background -->
        <img src="1.jpg" class="bg">

        <!-- Title section -->
        <div class="title-block">
            <h1>YOUR<br>SECURITY</h1>
            <p>Data encryption & secure backups<br>to keep your information safe</p>
        </div>

        <!-- Edition -->
        <div class="edition">
            FIRST EDITION
            <hr>
        </div>

        <!-- Author name -->
        <div class="author">KAMLESH Y</div>

        <!-- Character image -->
        <div class="character">
            <img src="1.png">
        </div>

    </div>

</body>
</html>

```
# OUTPUT:
<img width="1862" height="1076" alt="image" src="https://github.com/user-attachments/assets/7c2c0391-007b-4ad1-9cd2-ed5e987a6401" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

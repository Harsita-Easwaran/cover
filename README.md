# Ex.06 Book Front Cover Page Design
## Date:

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      font-family: 'Georgia', serif;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .image-container {
      position: relative;
      width: 400px;
      height: 600px; /* Portrait size */
      background-color: #111;
      overflow: hidden;
    }

    .image-container img.cover {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .centered-title {
      position: absolute;
      top: 10%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: rgb(168, 176, 180);
      font-size: 28px;
      font-weight: bold;
      text-align: center;
    }

    .subtitle {
      font-size: 20px;
      font-weight: normal;
      color: #ccc;
      margin-top: 5px;
    }

    .quote {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: rgb(234, 229, 243);
      font-size: 18px;
      width: 80%;
      text-align: center;
    }

    .author-name {
      position: absolute;
      bottom: 20px;
      left: 20px;
      font-size: 22px;
      color: rgb(170, 186, 187);
      font-weight: bold;
    }

    .author-image {
      position: absolute;
      bottom: 20px;
      right: 20px;
    }

    .author-image img {
      width: 100px;
      height: 100px;
      border-radius: 10px;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <div class="image-container">
    <img class="cover" src="coverpage.jpg" alt="Book Cover">

    <div class="centered-title">
      WOLF BROTHER
      <div class="subtitle">Chronicles of Ancient Darkness</div>
    </div>

    <div class="quote">
      "In a world where spirits walk and beasts speak,<br>
      only a boy and his wolf can stand against the darkness."
    </div>

    <div class="author-name">Michelle Paver</div>

    <div class="author-image">
      <img src="author.webp" alt="Author">
    </div>
  </div>
</body>
</html>
'''


## OUTPUT:
![alt text](<Screenshot 2025-05-15 120050.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

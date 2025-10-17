# Ex.08 Design of Interactive Image Gallery
## Date:17.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html
<html>
    <head>
        <title>Gallery</title>
        <link rel="stylesheet" href="style1.css">
        <script src="style2.js"></script>
    </head>
    <body>
        <h1>MY GALLERY - SATHEESWARI(25017493)</h1>
        <div class="gallery">
            <div class="galleryitem">
                <img class="zoom" src="bunny.jpeg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
            <div class="galleryitem">
                <img class="zoom" src="cat.jpeg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
            <div class="galleryitem">
                <img class="zoom" src="penguin.jpeg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
            <div class="galleryitem">
                <img class="zoom" src="dog.jpeg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
        </div>
        <footer class="copyrights">
            &copy; SATHEESWARI(25017493)
        </footer>
    </body>
</html>



style1.css

body {
    background-color: rgb(244, 127, 219);
    text-align: center;
    margin-top: 50px;
}

.gallery {
    display: flex;
    gap: 20px;
    padding-top: 50px;
    justify-content: center;;
}

.galleryitem {
    cursor: pointer;
    text-align: center;
    width: 200px;
    padding: 20px;
}

.galleryitem img {
    width: 230px;
    height: 300px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    text-align: center;
    top: 130px;
    left: -20px;
    position: relative;
}

style2.js
function mousein()
{
    document.getElementById("Photo").style.width="250";
    document.getElementById("Photo").style.height="350";
}

function mouseout()
{
    document.getElementById("Photo").style.width="230";
    document.getElementById("Photo").style.height="300";
}

```
## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/4d6b0635-e62e-4059-a781-8299f44f79a6" />
<img width="1920" height="1080" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/10c53b6c-f542-4fc0-ab56-58ff6cd550dd" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.

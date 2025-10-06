# Ex.08 Design of Interactive Image Gallery
# Date:06-10-2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```

gallery.html
<html>
    <head>
        <title>Gallery</title>
        <link rel="stylesheet" href="link.css">
    </head>
    <body>
        </style>
        <div class="image">
            <img src="Screenshot 2025-10-06 211145.png" id="image1">
            <img src="WhatsApp Image 2025-10-05 at 18.08.21_ce5c7b6a.jpg" id="image2"> 
            <img src="Screenshot 2025-10-06 211353.png" id="image3">
            <img src="Screenshot 2025-10-06 211522.png" id="image4">
            <img src="Screenshot 2025-10-06 211640.png" id="image5">
        </div>
        
        <h1>&copy;Image Gallery|Designed by:</h1>
        <h2>VISHAL .R (25016264)</h2>
        <script src="LINK.JS"></script>
    </body>
</html>
style.css
*{
    margin: 0;
    border:0;
}
body{
    background: linear-gradient(135deg, #00c6ff, #2a5298, #00c6ff);
}
.image{
    
    display: grid;
    grid-template-columns: repeat(5,2fr);
}
img{
    position: relative;
    top: 200px;
    width: 170px;
    left:30px;
    height: 200px;
    border:solid 10px rgba(58, 135, 171, 0.83);
    transition: transform 1s ease;
    cursor: pointer;
}

h1,h2{
    position: relative; 
    top: 400px;
    left: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 35px;
    color: azure;
    
}
const img1=document.getElementById("image1");
img1.addEventListener("mouseover",()=>
{
    img1.style.transform="scale(2)"
    // img1.style.transform="rotate(20deg)"
});
img1.addEventListener("mouseout",()=>
{
    img1.style.transform="scale(1)" 
    img1.style.transform="rotate(0deg)"
});
const img3=document.getElementById("image3");
img3.addEventListener("mouseover",()=>
{
    img3.style.transform="scale(2.5)"
});
img3.addEventListener("mouseout",()=>
{
    img3.style.transform="scale(1)"
});
const img4=document.getElementById("image4");
img4.addEventListener("mouseover",()=>
{
    img4.style.transform="scale(2)"
});
img4.addEventListener("mouseout",()=>
{
    img4.style.transform="scale(1)"
});
const img5=document.getElementById("image5");
img5.addEventListener("mouseover",()=>
{
    img5.style.transform="scale(2)"
});
img5.addEventListener("mouseout",()=>
{
    img5.style.transform="scale(1)"
});
const img2=document.getElementById("image2");
img2.addEventListener("mouseover",()=>
{
    img2.style.transform="scale(2)"

});
img2.addEventListener("mouseout",()=>
{
    img2.style.transform="scale(1)"
});
```

# OUTPUT:
<img width="1919" height="1079" alt="Screenshot 2025-10-06 214536" src="https://github.com/user-attachments/assets/9e8fb42e-29b4-4b25-8284-94053b0fd86e" />
<img width="1919" height="1079" alt="Screenshot 2025-10-06 214556" src="https://github.com/user-attachments/assets/5d47b80d-938f-442b-8f59-995ebfca26e1" />


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.


# OUTPUT:

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.


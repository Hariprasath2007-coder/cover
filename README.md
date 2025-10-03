# Ex.06 Book Front Cover Page Design
## Date: 04-10-2025
## Name: HARI PRASATH E
## Ref No: 25007799

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
cover.html


<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title>Radha-Krishna Book</title>
    </head>
    <body>
        <div class="name"><h1>HARI PRASATH E(25007799)</h1></div>
        
        <div class="cover">
            <div class="main">
                <div class="title">
                    <h1>SEC Insight</h1>
                    <hr>
                </div>
                
                <div class="content">
                    <p><h2>Moonlit Melodies
                         of Vrindavan</h2></p>
                            
                </div>
                <br>
                <div class="subtitle">
                    <h3>
                    * The Eternal Love of Radha & Krishna
                    </h3>
                    <h3>* Sacred Love Beyond Time</h4>
                </div>
                <div class="image">
                    <img src="me2.jpg" alt="mypic">
                </div>
                <div class="edition">
                    <h2>Elite Edition</h2>
                    <hr>
                </div>
                <div class="author">
                    <h2>HARI PRASATH E</h2>
                </div>
                <div class="sub-bottom"><h2>WE</h2></div>
            </div>
       </div>
    </body>
</html>

style.html

body{
    background-color: #000000;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:rgba(255, 255, 255, 0.853);
}
.cover{
    background-image:url(rk1.jpg);  
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;  
    height: 725px;
    width: 500px;
    position: relative;
    left: 500px;
}
.main{
    margin: auto;
    border: solid 8px rgb(244, 236, 236);
}
.title{
    font-size: 12px;
    color: rgb(255, 255, 255);
    font-weight: 800;
    position: relative;
    top: 20px;
    left: 10px;
    width: 140px;
}
.content{
    font-size: 35px;
    text-align: center;
    position: relative;
    top: 0px;
    color:rgba(0, 0, 0, 0.853);
    font-weight: 800;
    
}
.subtitle{
    position: relative;
    left: 10px;
    font-size:18px;
    
}
.image{
    width: 150px; 
    height:190px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid rgb(255, 254, 254);
    background: rgb(63, 161, 219);
    overflow: hidden;   
}
.image img{
    width: 100%;
    height: 100%;
    color:rgb(255, 255, 255);
    object-fit: cover;
}
.edition{
    position: relative;
    top: 50px;
    left: 1px;
    font-weight: bolder;
}
.author{
    position: relative;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    top: 45px;
    left:20px;
    font-size: 18px;
    color:rgba(229, 38, 38, 0.853);
}
.sub-bottom{
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    bottom:5px;
    left:380px;
    font-size: 15px;
    color:rgba(218, 63, 63, 0.853);
}
.name{
    text-align: center;
    position: relative;
    right:50px;
    color:rgb(26, 198, 198);
}


```
## OUTPUT:
<img width="1902" height="1047" alt="webprgt" src="https://github.com/user-attachments/assets/2674ab90-b2ba-4c37-8843-3cd4e99fafeb" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

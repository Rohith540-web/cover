# Ex.06 Book Front Cover Page Design
## Date:3/12/24

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
    
    <style>
        .container {
            position: relative;
            margin-left: 40%;
            margin-right: 60%;
            width: 300px;
            height: 300px;
            
        }

        .expert-insight {
            position: absolute;
            top: 30px;
            left: 40px;
            color: whitesmoke;
            font-style: italic;
            font-size: 16px;

        }
        .background-image
        {
            width: 200%;
            height: 270%;
        }

        .main-title {
            position: absolute;
            top: 115px;
            left: 40px;
            color: whitesmoke;
            font-style: italic;
            font-size: 36px;
        }
        .photo {
            position: absolute;
            bottom: -440px;
            right: -270px;
            width: 120px;
            height: auto;
        }

        .subtitle {
            position: absolute;
            font-style: italic;
            font-size: 16px;
            top: 300px;
            left: 40px;
            font-weight: lighter;
            color: whitesmoke;
        }

        .edition {
            position: absolute;
            bottom: -450px;
            left: 40px;
            color: whitesmoke;
            font-style: italic;
            font-size: 20px
        }


        .author {
            position: absolute;
            bottom: -520px;
            left: 40px;
            color: whitesmoke;
            font-style: italic;
            font-size: 30px;
            
        }
        .SEC{
            position:absolute;
            bottom: -490px;
            right: -220px;
            font-style: italic ;
            font-size: 16px;
            color: whitesmoke;
        }
        
    </style>
</head>
<body>
    <div class="container">
        <img  class="photo" src="photo.jpg" >
        <img class="background-image" src="image 1.jpg">
        <p class ="expert-insight"> EXPERTS INSIGHT</p>
        <h1 class="main-title" >WEB DEVELOPMENT: A BEGINNERS GUIDE</h1>
        <h2 class="subtitle"> From ZERO to HERO: Step by Step</h2>
        <p class="edition" >First Edition</p>
        <p class="author" >Rohith V</p>
        <p class="SEC" >SEC</p>
    </div>
</body>
</html>



```


## OUTPUT:

![alt text](<Screenshot (53).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

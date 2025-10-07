# Ex.06 Book Front Cover Page Design
## Date: 07/10/2025

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
<html>
    <head>
        <title>
            Book Cover
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page" align="center">
        <div class="cover">
            <div class="quote">
                Algorithms that heal, Systems that save<hr>
            </div>
            <div class="title-block"> 
                <h1> Computational Medicine : <br>  Engineering Health Solutions</h1>
            </div>
            <div class="subtitle">
                 Computational approaches to modern medicine
            </div>
            <div class="author-photo">
                <img src="Sandya.jpg">
            </div>
                <p class="publisher"> TechMed Publications </p>
                <p class="edition"><b> - 3rd Edition</b>  </p>
                <p class="author-name"> Sandya S</p>
                <p class="copies-sold"><u> Over 10,000 copies sold worldwide </u></p>
            </div>
        </div>
</body>
</html>

style.css
body {
  margin:0;
  padding:0;
  font: Arial;
  justify-content: center;
  align-items: center;
}


.page {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.cover {
  position: relative;
  width: 350px;
  height: 550px;
  border: 5px solid darkgray;
  border-radius: 0;
  color: white;
  text-align: center;
  box-sizing: border-box;
  background-image: url('computational engg cover.jpg'); 
  background-size: cover;    
  background-position: center;
  padding: 20px;
}

.quote {
  font-size: 14px;
  font-style: italic;
  margin-bottom: 30px;
}

.title-block h1 {
  font-size: 22px;
  margin-top: 100px;
  text-align: center;
  line-height: 1.4;
}

.subtitle {
  text-align: left;
  margin-top: 70px;
  margin-left: 10px;
  font-size: 15px;
  font-style: italic;
}

.author-photo {
  position: absolute;
  bottom: 80px;
  right: 25px;
  text-align: center;
  width: 80px;
  height: 80px;
}

.author-photo img {
  width: 100%;
  height: 100%;
  border: 2px solid white;
  
}

.author-name{
  position: absolute;
  bottom: 55px;
  left: 20px;
 font-weight: bold;
 font-size: 20px;
 font-style: italic;  
}

.publisher{
  position: absolute;
  bottom: 130px;
  left: 20px;
  font-size: 20px;
}

.edition{
  position: absolute;
  bottom: 100px;
  left: 20px;
  font-size: 20px;
}

.copies-sold {
  position:absolute;
  font-weight: bold;
  bottom: 2px;
  left:0;
  right: 0;
  text-align: center;
  font-size: 20px;
  color: gold;
}

```


## OUTPUT:
![alt text](<Screenshot (37).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

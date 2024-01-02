# Ex.06 Book Front Cover Page Design
## Date:02/01/2024
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
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<style>
.bookpage{
width: 400px;
height: 600px;
color:yellow;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium', 'Arail Narrow', Arial, sans-serif;
background-image:"https://www.google.com/url?sa=i&url=https%3A%2F%2Falphacommunity.in%2Fexplore%2Fexpertspeak%2Fcapturing-the-rhythms-of-classicalindia%2F&psig=AOvVaw0RTtw42q8tFfie08rgSEYp&ust=1701673603118000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKDM5aPa8oIDF"

background-size:cover;
background-color: purple;
background-position: center;
}
.insight{
color: blanchedalmond;
}
.hrstyle{
width:100px;
}
.author{
display: inline;
position: relative;
color: Honeydew;
top:190px;
font-family:Georgia;
font-size: medium;
}
.booktitle{
font-family: 'Courier New', Courier, monospace;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}
.id {
width:400px;
position: relative;
top:180px;
}
.pub{
font-size: medium;
position: relative;
top:155px;
left:330px;
}
.ed{
color: cyan;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}
.subtitle{
color: greenyellow;
font-family:Tahoma;
font-size: large;
position: relative;
top:40px;
}
.mypic{
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
<div class="insight">
CSC INSIGHT
</div>
<div class="hrstyle">
<hr style="color:bisque;">
</div>
<div class="booktitle">
<h1>Honors diplomo computer application</h1></div>
<div class="subtitle">
C language, C++, Python, Ms-office and HTML and CSS combined in HDCA
</div>
<div class="mypic">
<img src="c:\Users\admin\Documents\Tamizhselvan.img.jpg" width="130" height="145" alt="">
</div>
<div class="id">
<hr style="color: hotpink;">
</div>
<div class="author">
<p><b>Tamizhselvan.B</b></p>
</div>
<div class="pub">
AIDS
</div>
<div class="ed">
<b>Seventh Edition</b>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![page cover output](https://github.com/tamizhselvan23013460/cover/assets/150231370/1a5fffc3-0267-4cb7-a2d4-7bfba6f89bac)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

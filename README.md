# Ex.05 Book Cover Page Design
## Date:16/03/2026

## AIM:
To design a book back cover page using HTML and CSS.

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
index.html
{% load static %}
<html>
<head>
    <title>Book Cover</title>

    <style>
        body{
            font-family: Arial, sans-serif;
            background:#a9d3ef;
            margin:0;
            padding:0;
        }

        .container{
            width:70%;
            margin:40px auto;
            background:rgba(255,255,255,0.7);
            padding:30px;
            border-radius:10px;
        }

        h1{
            color:#0b4d8c;
        }

        p{
            font-size:18px;
            line-height:1.6;
        }

        .highlight{
            background:yellow;
        }

        .quote{
            margin:20px 0;
            padding:15px;
            background:#e6f0fa;
            border-left:5px solid #0b4d8c;
            text-align:center;
            font-style:italic;
        }

        .author{
            display:flex;
            align-items:center;
            background:#f5f5f5;
            padding:15px;
            border-radius:8px;
        }

        .author img{
            width:80px;
            margin-right:15px;
        }

        .student{
            margin-top:20px;
            background:#e0f2ff;
            padding:10px;
            border-radius:5px;
        }
    </style>

</head>

<body>

<div class="container">

<h1>About the Book</h1>
<hr>

<p>
This book <span class="highlight">"Fundamentals of Web Application Development"</span>
provides an engaging journey through the art and science of web design.
It explores how creativity meets technology to craft visually appealing
and user-friendly websites.
</p>

<div class="quote">
“Design is not just what it looks like and feels like — design is how it works on the web.”
</div>

<div class="author">
<img src="{% static 'images/author.jpg' %}" width="80">

<div>
<h3>Dhyaneshwar S</h3>
<p>
Dhyaneshwar S is an enthusiastic learner with a strong interest in web
development and technology. Through learning web design and development,
Dhyaneshwar S aims to create creative and user-friendly web applications.
</p>
</div>

</div>

<div class="student">
<p><b>Name:</b> Dhyaneshwar S</p>
<p><b>Roll No:</b> 212225040078</p>
</div>

</div>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

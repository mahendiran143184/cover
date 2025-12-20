# Ex.06 Book Front Cover Page Design
## Date:15/12/25
# ref no :25008762

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
~~~
book.html
<html>
    <head>
        <title>Cascading Style Sheet</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="book">
            <div class="heading">
            <h1>About the Book</h1>
            <hr>
            </div>
            <div class="content">
                <p>This Book<span> Data science evolved from early statistics </span>(Tukey, 1960s) into a distinct field with the advent of big data (2000s), integrating computer science, AI, and domain knowledge to handle massive, complex datasets, shifting focus from inference to prediction and creating the "data scientist" role (Patil & Hammerbacher, 2008), leading to today's AI-driven, IoT-integrated, and ethically-focused data analysis for broad business and scientific innovation.</p>
            </div>
            <div class="quote-box">
            "Data are just summaries of thousands of stories—tell a few of those stories to help make the data meaningful."
            </div>
            <div class="author-box">
                 <div class="author-img"></div>

                <div class="author-text">
                     <div class="author-name">MAHENDIRAN.M</div>
                     <p>
                        Mahendiran.m is a first-year student at Saveetha Engineering College, pursuing his undergraduate studies in engineering. He demonstrates a keen interest in writing, often engaging with books to capture ideas, reflections, and creative thoughts.


                     </p>
                </div>
            </div>
            <div class="footer">
                <div class="footer-left">
                    <strong>SEC Publishers</strong>
                    <br>
                    <div class="printed">printed in India</div>
                </div>
                <div class="price">Price=RS999</div>
            </div>
        </div>
    </body>
</html>
body
{
    background: url('Screenshot 2025-12-12 102206.png') center / contain no-repeat fixed;
    min-height: 100vh;
    display: flex;
    justify-content: center;
}
.book
{
    padding-left: 700px;
    padding-right: 700px;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.heading
{
    padding-top: 20px;
    font-style: Montserrat;
    color: rgb(55, 41, 67);
    padding-left: 25px;
}
.content
{
    font-size: 16px;
    text-align: center;
    text-align: justify;
    padding-left: 25px;
    font-style:inherit
}
span
{
    background-color: yellow;
}
.quote-box
{
    margin: 15px 0;
    padding: 15px 15px;
    background: rgb(105, 97, 97);
    border-left: 6px solid rgb(147, 241, 15);
    font-style: italic;
}
.author-text 
{
    display: flex;
    flex-direction: column;
    font-size: 15px;
    
}

.author-box 
{
    display: flex;
    gap: 8px;
    background: cyan;
    padding: 8px;
    border-radius: 8px;
    margin-top: 15px;
    text-align: justify;
    align-items: center;
}
.author-img 
{
    width: 400px;
    height: 100px;
    border-radius: 8px;
    background-image: url('');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.author-name 
{
    color: blue;
    font-weight: bold;
    font-size: 15px;
}
.footer 
{
    margin-top: auto;
    background-color:rgb(54, 139, 158);
    color: rgb(38, 37, 36);
    padding: 5px 5px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left 
{
    display: flex;
    flex-direction: column;
}
.printed
{
    font-size: 14px;
}
.price 
{
    font-weight: bold;
    color: rgb(168, 236, 33);
    font-size: 18px;
}
~~~

## OUTPUT:
![alt text](<Screenshot (27).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.05 Book Cover Page Design
## Date:16-12-2025

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
html 
```
<html>
    <head>
        <title>Cover Page</title>
        <link rel="stylesheet" href="styles.css">
    </head>
<body>
<div class="container">
    <h2>About the Book</h2>
    <hr>
    <p>
        This book <b><mark>"The Quantum Everyday"</mark></b> The Quantum Everyday would be a bridge between the mind-bending physics of the quantum world and the ordinary objects and experiences that quietly depend on it.

    </p>
    <p>
        The Quantum Everyday will help readers see the invisible science shaping their lives. By connecting abstract quantum principles to familiar technologies like smartphones, GPS, and medical imaging, the book makes complex ideas simple and relatable. Readers will walk away with the confidence to explain quantum concepts in everyday conversations, a deeper appreciation for the hidden forces powering modern life, and inspiration to imagine how quantum innovations might transform the future. Ii is not just about learning physics it is about unlocking wonder in the ordinary.

    </p>
    <div class="quote">
        "Quantum mechanics is not just hidden in laboratories it is the quiet architect of the modern world we live in"
    <div class="author-box">
        <img src="mahi.jpeg" alt="Author Image">
        <div>
            <h3>Mahith M</h3>
            <p>
                Mahith, the author of The Quantum Everyday, is a passionate science communicator who brings the mysteries of quantum mechanics into the realm of daily life. With a gift for storytelling and clarity, Mahith reveals how the invisible rules of the quantum world power technologies we depend on, from smartphones to medical imaging, while inspiring readers to see themselves as part of the unfolding quantum revolution. His work blends scientific insight with human curiosity, making complex ideas accessible and sparking wonder in the ordinary.

            </p>
        </div>
    </div>
    <div class="footer">
        <span><b>TVK Publisher</b><br>printed in Tamilnadu</span>
        <span class="price">Price: Rs.999</span>
    </div>
</div>
</body>
</html>


```
css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background: rgb(18, 89, 7); 
}
.container {
    background: white;
    width: 46%;
    margin: auto;
    padding: 25px;
    border-radius: 10px;
    border: 2px solid rgb(9, 119, 5)
}
h2{
    color: rgb(205, 253, 48);
}
hr {
    border: none;
    height: 2px;
    background: rgb(136, 248, 24);
    margin: 10px 0 20px 0;
}
p {
    line-height: 2;
    color: black;
}
.quote {
    border: 1px solid rgb(131, 8, 80);
    background: rgb(8, 155, 62);
    border-left: 5px solid rgb(178, 192, 241);
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
    color: rgb(87, 249, 65);
    border-radius: 5px;
}
.author-box {
    display: flex;
    background: lightcyan;
    padding: 15px;
    border-radius: 10px;
    border: 1px solid rgb(230, 166, 69);
    margin-top: 25px;
    gap: 15px;
}
.author-box img {
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
    border: 2px solid rgb(64, 244, 85);
}
.author-box h3 {
    margin: 0 0 5px 0;
    color: rgb(53, 239, 112);
}
.footer {
    margin-top: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: lightgreen;
    color: rgb(105, 41, 23);
    padding: 12px 20px;
    border-radius: 10px;
}
.price {
    font-weight: bold;
    font-size: 18px;
}

```

## OUTPUT:

![alt text](<Screenshot (41).png>)
## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

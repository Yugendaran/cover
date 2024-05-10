# Ex.06 Book Front Cover Page Design

## Date: 28.04.2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Design with HTML5 and CSS</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <div class="container">
        <div class="cover">
            <div class="top-stripe"></div>
            <!-- <img src="book-cover.jpg" alt="Responsive Web Design with HTML5 and CSS"> -->
            <div class="bottom-stripe"></div>
        </div>
        <div class="content">
            <h5 style="margin-left: 20px; padding-top: 20px;">EXPERT INSIGHT</h5>
            <h1 style="margin-left: 30px; margin-right: 30px; font-size: 45px;">Responsive Web Design with HTML5 and CSS</h1>
            <h2 style="margin-left: 30px; margin-right: 30px; font-size: 18px;">Develop future-proof responsive websites using the latest HTML5 and CSS techniques.</h2>
            <img src="assets/css/modern-abstract-blue-resonance-wavy-digital-dashed-lines-background-wallpaper_591091-831.jpg" alt="" width="100%">
            <div style="display: flex">
                <h3 style="margin-left: 30px; color: orange;">Third Edition</h3>
                <img src="assets/css/images.jpeg" alt="" width="90px" style="margin-left: 48%;">
            </div>
            <hr style="border-top: 2px solid orange">
            <div class="author" style="display: flex;">
                <p style="margin-left: 30px;font-size: 25px;">By Ben Frain</p>
                <p style="margin-left: 45%;font-size: 25px;">Packt></p>
            </div>
        </div>
    </div>
</body>
</html>
```
style.css
```

.container{
    background-color: black;
    color: white;
    width: 550px;
    height: 750px;
    margin-left: 30%;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
```


## OUTPUT:
![image](https://github.com/Yugendaran/cover/assets/128135616/06c8fdc0-c446-4838-88aa-fb2fde664e04)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

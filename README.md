# Ex.07 Restaurant Website
## Date: 17/10/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
### HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <header>
        <div class="logo">
            
            <img src="logo.png" alt="Little Lemon Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>

   
    <main>
        
        <section class="promo-banner">
            <h2>50% Off This Weekend</h2>
            <p>Experience Authentic Arabian Hospitality!</p>
        </section>

        
        <section class="content-columns">
            <article class="column">
                <h3>Our New Menu</h3>
                <img src="kunafa.jpeg" alt="New Menu">
                <p>Crispy sweet kunafa</p>
                <a href="#">See our new menu</a>
            </article>

            <article class="column">
                <h3>Book a Table</h3>
                <img src="kapsa.jpeg" alt="Book a Table">
                <p>Spicy Kapsa</p>
                <a href="#">Book your table now</a>
            </article>

            <article class="column">
                <h3>Opening Hours</h3>
                <img src="chef.jpg" alt="Opening Hours">
                <p>A Taste of Tradition, a Touch of Luxury.</p>
                <p>Monday - Friday: 2pm - 10pm<br>Saturday: 2pm - 11pm<br>Sunday: 2pm - 9pm</p>
            </article>
        </section>
    </main>

    
    <footer>
        <div class="footer-logo">
            <img src="logo.png" alt="Little Lemon Logo">
        </div>
        <div class="footer-text">
            <p>© 2024 Little Lemon</p>
        </div>
    </footer>
</body>
</html>
```
### CSS
```CSS
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ffcc00;
    padding: 1rem 2rem;
}

header .logo img {
    height: 50px;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

header nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

header nav ul li a:hover {
    color: #666;
}

/* Promo Banner */
.promo-banner {
    background-color: #ff6600;
    color: #fff;
    text-align: center;
    padding: 2rem;
    margin-bottom: 1rem;
}

.promo-banner h2 {
    font-size: 2rem;
    margin-bottom: 0.5rem;
}

.promo-banner p {
    font-size: 1.2rem;
}

/* Main Content - Columns */
.content-columns {
    display: flex;
    justify-content: space-around;
    padding: 2rem;
    gap: 1.5rem;
}

.content-columns .column {
    background-color: #fff;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 30%;
    text-align: center;
}

.content-columns .column img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 1rem;
}

.content-columns .column h3 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
}

.content-columns .column p {
    margin-bottom: 0.5rem;
}

.content-columns .column a {
    text-decoration: none;
    color: #ff6600;
    font-weight: bold;
}

.content-columns .column a:hover {
    color: #333;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1.5rem;
    margin-top: 1.5rem;
}

footer .footer-logo img {
    height: 40px;
}

footer .footer-text p {
    margin-top: 0.5rem;
}

/* Responsive */
@media (max-width: 768px) {
    .content-columns {
        flex-direction: column;
        align-items: center;
    }

    .content-columns .column {
        width: 80%;
    }

    header {
        flex-direction: column;
        text-align: center;
    }

    header nav ul {
        flex-direction: column;
        gap: 0.5rem;
    }
}
```

## OUTPUT:
![Screenshot 2024-11-11 000304](https://github.com/user-attachments/assets/908c816c-7c10-40fc-9c8a-a27cf4b80531)
![Screenshot 2024-11-11 000314](https://github.com/user-attachments/assets/515c9df0-b234-4da3-9c3d-2bd69a0a8096)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

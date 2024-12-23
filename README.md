# Ex.07 Restaurant Website
## Date:13/12/2024

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

## restaurant.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lobster&family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin-bottom: 10px;
        }

        nav {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }
        .heading{
            font-family: Roboto Condensed;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            margin-bottom: 20px;
            font-size: 2em;
        }

        .menu-item {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .menu-item div {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 250px;
        }

        .menu-item img {
            width: 100%;
            border-radius: 5px;
        }

        .menu-item h3 {
            margin-top: 15px;
            font-size: 1.5em;
        }

        .menu-item p {
            color: #777;
            font-size: 1em;
        }
        .about {
            background-color: #333;
            color: white;
            padding: 40px 20px;
        }

        .about p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }
        .content{
            font-family: Lobster;
            font-size: 50px;
        }
        .contact {
            padding: 40px 20px;
            background-color: #fff;
        }

        .contact h2 {
            margin-bottom: 20px;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: 0 auto;
        }

        .contact input, .contact textarea {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        .contact button {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            border-radius: 5px;
        }

        .contact button:hover {
            background-color: #575757;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .creator{
            font-family: Roboto Condensed;
            padding-top: 18px;
        }
    </style>
</head>
<body>
    <header>
        <h1 class="heading">AASIF'S  RESTAURANT</h1>
        <nav>
            <a href="#menu">Menu</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section id="menu">
        <h2 class="heading">Our Menu</h2>
        <div class="menu-item">
            <div>
                <img src="1 (2).png" alt="Dish 1">
                <h3>Pasta Alfredo</h3>
                <p>Delicious creamy pasta with parmesan cheese.</p>
            </div>
            <div>
                <img src="2 (2).png" alt="Dish 2">
                <h3>Grilled Steak</h3>
                <p>Juicy grilled steak served with a side of vegetables.</p>
            </div>
            <div>
                <img src="3 (2).png" alt="Dish 3">
                <h3>Margherita Pizza</h3>
                <p>Classic pizza with mozzarella, basil, and tomato.</p>
            </div>
        </div>
    </section>
    <section id="about" class="about">
        <h2 class="heading">About Us</h2>
            <h2>Gallery</h2>
            <img src="g1.png" width="475px" alt="Gallery image 1" />
            <img src="g3.png" width="500px" alt="Gallery image 2" />
            <img src="g2.png" width="500px" alt="Gallery image 3" />
        <p class="content">At Aasif's Restaurant, we serve a variety of mouth-watering dishes, crafted with the freshest ingredients. Our chefs are passionate about creating exceptional culinary experiences, and we are committed to providing top-notch service in a comfortable and welcoming environment. Whether you're here for a casual meal with friends or celebrating a special occasion, we strive to make every visit memorable.</p>
    </section>
    <section id="contact" class="contact">
        <h2 class="heading">Contact Us</h2>
        <form action="#">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Aasif's Restaurant | All Rights Reserved</p>
        <p><a href="policy/privacy-policy.html">Privacy Policy</a> | <a href="t&c.html">Terms of Service</a></p>
        <h3 class="creator">
            Created by :  Raghu Ram [24900512]
        </h3>
        <div>
            <img src="ceo.jpg">
        </div>
    </footer>

</body>
</html>

```



## OUTPUT:
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

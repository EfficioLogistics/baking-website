<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delightful Bakes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f3f2;
        }
        header {
            background-color: #ffcc99;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            color: #603913;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #603913;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background: url('https://via.placeholder.com/1500x500') no-repeat center center;
            background-size: cover;
            color: white;
            font-size: 32px;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            font-size: 24px;
            color: #603913;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #603913;
            color: white;
        }
    </style>
</head>
<body>

<header>
    Welcome to Delightful Bakes
</header>

<nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#recipes">Recipes</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    Discover the joy of baking one recipe at a time.
</div>

<div class="container">
    <div class="section" id="about">
        <h2>About Us</h2>
        <p>Welcome to Delightful Bakes, your go-to destination for all things baking! From decadent cakes to wholesome bread, we believe that baking is not just a hobby but a way to spread joy and love. Join us as we share our passion for creating delightful treats.</p>
    </div>

    <div class="section" id="gallery">
        <h2>Gallery</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300" alt="Cake">
            <img src="https://via.placeholder.com/300" alt="Cookies">
            <img src="https://via.placeholder.com/300" alt="Bread">
            <img src="https://via.placeholder.com/300" alt="Pastries">
        </div>
    </div>

    <div class="section" id="recipes">
        <h2>Recipes</h2>
        <p>Looking for inspiration? Check out our tried-and-tested recipes:</p>
        <ul>
            <li><a href="#">Classic Chocolate Cake</a></li>
            <li><a href="#">Rustic Sourdough Bread</a></li>
            <li><a href="#">Buttery Croissants</a></li>
            <li><a href="#">Chewy Chocolate Chip Cookies</a></li>
        </ul>
    </div>

    <div class="section" id="contact">
        <h2>Contact Us</h2>
        <p>We'd love to hear from you! Reach out to us at <a href="mailto:info@delightfulbakes.com">info@delightfulbakes.com</a> or follow us on our social media channels.</p>
    </div>
</div>

<footer>
    &copy; 2025 Delightful Bakes. All rights reserved.
</footer>

</body>
</html>

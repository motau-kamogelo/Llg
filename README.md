<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lehe la Gauta - Fresh Eggs Direct</title>
    <style>
        /* Reset and basic styling */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        header {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 10px 0;
            text-align: center;
        }
        header img {
            max-width: 150px;
            height: auto;
        }
        nav ul {
            list-style-type: none;
            text-align: center;
            margin: 10px 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #555;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        nav ul li a:hover {
            color: #000;
        }
        .main-section {
            text-align: center;
            padding: 40px 0;
        }
        .main-section h2 {
            font-size: 2.5em;
            color: #333;
            margin-bottom: 20px;
        }
        .main-section p {
            font-size: 1.1em;
            color: #666;
            margin-bottom: 40px;
        }
        .section {
            padding: 60px 0;
            text-align: center;
        }
        .section h2 {
            font-size: 2.2em;
            color: #333;
            margin-bottom: 30px;
        }
        .section p {
            font-size: 1.1em;
            color: #666;
            line-height: 1.8;
        }
        .section img {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        footer p {
            font-size: 0.9em;
            margin-bottom: 5px;
        }
        footer a {
            color: #fff;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        footer a:hover {
            color: #f9ca24;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <img src="logo.png" alt="Lehe la Gauta Logo">
        </div>
    </header>
    <nav>
        <div class="container">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </div>
    </nav>
    <main>
        <section id="home" class="main-section">
            <div class="container">
                <h2>Welcome to Lehe la Gauta!</h2>
                <p>Your source for the freshest eggs in [Your Location].</p>
                <img src="eggs.jpg" alt="Fresh Eggs">
            </div>
        </section>
        <section id="about" class="section">
            <div class="container">
                <h2>About Us</h2>
                <p>Discover our story and commitment to providing high-quality eggs.</p>
                <img src="farm.jpg" alt="Our Farm">
            </div>
        </section>
        <section id="products" class="section">
            <div class="container">
                <h2>Our Products</h2>
                <p>Explore the variety of eggs we offer, including organic and free-range options.</p>
                <img src="products.jpg" alt="Our Products">
            </div>
        </section>
        <section id="contact" class="section">
            <div class="container">
                <h2>Contact Us</h2>
                <p>Get in touch with us to place an order or inquire about our products.</p>
                <p>Email: info@lehelagauta.com<br>
                   Phone: +123 456 7890</p>
                <p>Address: [Your Farm Address]</p>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2024 Lehe la Gauta. All rights reserved.</p>
            <p>Connect with us on social media:
                <a href="#" target="_blank">Facebook</a> |
                <a href="#" target="_blank">Instagram</a>
            </p>
        </div>
    </footer>
</body>
</html>

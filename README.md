<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sonali Photo Studio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fafafa;
        }

        header {
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background: #333;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff7e5f;
        }

        .hero {
            text-align: center;
            padding: 40px;
            background: url('https://via.placeholder.com/1200x400') no-repeat center/cover;
            color: white;
        }

        .hero h2 {
            font-size: 40px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 20px;
        }

        .photo {
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            overflow: hidden;
        }

        .photo img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .photo p {
            text-align: center;
            padding: 10px;
        }

        .contact {
            background: #eee;
            padding: 20px;
            text-align: center;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

<header>
    <h1>Sonali Photo Studio</h1>
    <p>Capturing Your Beautiful Moments</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Gallery</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h2>Welcome to Sonali Studio</h2>
    <p>We make your memories last forever 📸</p>
</section>

<section class="gallery">

    <div class="photo">
        <img src="https://via.placeholder.com/300x200" alt="">
        <p>Wedding Photography</p>
    </div>

    <div class="photo">
        <img src="https://via.placeholder.com/300x200" alt="">
        <p>Birthday Shoot</p>
    </div>

    <div class="photo">
        <img src="https://via.placeholder.com/300x200" alt="">
        <p>Portrait Session</p>
    </div>

    <div class="photo">
        <img src="https://via.placeholder.com/300x200" alt="">
        <p>Outdoor Shoot</p>
    </div>

</section>

<section class="contact">
    <h2>Contact Us</h2>
    <p>📍 Address: Solapur, Maharashtra</p>
    <p>📞 Phone: 9876543210</p>
    <p>📧 Email: sonalistudio@gmail.com</p>
</section>

<footer>
    <p>&copy; 2026 Sonali Photo Studio</p>
</footer>

</body>
</html>

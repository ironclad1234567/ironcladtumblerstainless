<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Iron Clad Tumblers</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Candara', Verdana, sans-serif;
            line-height: 1.6;
            background-color: #111;
            color: #e6e6e6;
            font-weight: bold;
        }

        header {
            background-color: #222;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.8);
        }

        header nav .logo h1 {
            font-size: 3em;
            color: #ff6600;
            text-transform: uppercase;
            letter-spacing: 4px;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        header nav .nav-links {
            list-style: none;
            display: flex;
            justify-content: center;
            padding-top: 15px;
        }

        header nav .nav-links li {
            margin: 0 20px;
        }

        header nav .nav-links a {
            color: #e6e6e6;
            text-decoration: none;
            font-size: 1.2em;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: color 0.3s ease;
        }

        header nav .nav-links a:hover {
            color: #ff6600;
        }

        /* Hero Section */
      

        .hero-text h2 {
            font-size: 4em;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 6px;
            font-weight: bold;
            color: #ff6600;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
        }

        .hero-text p {
            font-size: 1.5em;
            letter-spacing: 2px;
            font-weight: normal;
            text-transform: capitalize;
        }

        .hero-text img {
            max-width: 70%;
            height: auto;
            margin-top: 30px;
            border: 5px solid #ff6600;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }

        /* About Section */
        #about {
            padding: 60px;
            background-color: #222;
            text-align: center;
            color: #e6e6e6;
            box-shadow: inset 0 0 30px rgba(0, 0, 0, 0.6);
        }

        /* Product Section */
        #products {
            padding: 60px;
            background-color: #333;
            color: #e6e6e6;
        }

        .product-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
        }

        .product {
            width: 30%;
            margin-bottom: 20px;
            text-align: center;
            background-color: #444;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.8);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            border: 3px solid #ff6600;
        }

        .product .price {
            font-size: 1.5em;
            color: #ff6600;
            margin: 15px 0;
            font-weight: bold;
        }

        .product .add-to-cart {
            background-color: #ff6600;
            color: #111;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .product .add-to-cart:hover {
            background-color: #e65c00;
        }

        /* Contact Section */
        #contact {
            padding: 60px;
            background-color: #222;
            text-align: center;
            color: #e6e6e6;
            box-shadow: inset 0 0 30px rgba(0, 0, 0, 0.8);
        }

        #contact h2 {
            font-size: 3em;
            margin-bottom: 20px;
            letter-spacing: 5px;
            font-weight: bold;
            color: #ff6600;
        }

        #contact p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        #contact .social-icons {
            list-style: none;
            display: flex;
            justify-content: center;
            padding-top: 20px;
        }

        #contact .social-icons li {
            margin: 0 20px;
        }

        #contact .social-icons a {
            color: #e6e6e6;
            font-size: 2.5em;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        #contact .social-icons a:hover {
            color: #ff6600;
        }

        /* Footer */
        footer {
            background-color: #111;
            padding: 15px;
            text-align: center;
            color: #e6e6e6;
            font-size: 1em;
            box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.8);
        }

        footer p {
            letter-spacing: 1px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <h1>Iron Clad Tumblers</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#products">Our Product</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-text">
            <h2>Kekuatan dan Gaya Dalam Satu Genggaman</h2>
            <p>Premium Tumblers with a Hardcore Edge</p>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p><strong>Ironclad:</strong> Menggunakan istilah "ironclad" yang berarti kuat dan tidak tertembus, menggambarkan kualitas tumbler. Ironclad: Teman setia untuk gaya hidup aktifmu. Tumbler metal yang kuat dan stylish ini menjaga minumanmu tetap dingin atau panas, di mana pun kamu berada. Desain ergonomis dan portabilitasnya yang tinggi membuatnya sempurna untuk dibawa ke gym, perjalanan, atau aktivitas luar ruangan lainnya. Tunjukkan kekuatan dan gayamu dengan Ironclad!</p>
    </section>

    <section id="products">
        <h2>Our Product</h2>
        <div class="product-container">
            <div class="product">
                <img src="https://i.imgur.com/Ok9W7K0.jpeg" alt="Ironclad Tumbler">
                <h3>Ironclad Metal Tumbler</h3>
                <p>Desain ergonomis dan bahan berkualitas tinggi untuk tumbler yang kuat dan tahan lama. Menjaga minuman tetap dingin atau panas sepanjang hari.</p>
                <p class="price">Rp. 85.000</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Follow us on social media or reach out via the platforms below:</p>
        <ul class="social-icons">
            <li><a href="https://www.instagram.com/ironcladtumbler/" target="_blank"><i class="fab fa-instagram"></i></a></li>
            <li><a href="https://www.facebook.com/profile.php?id=61571167660047&mibextid=ZbWKwL" target="_blank"><i class="fab fa-facebook"></i></a></li>
            <li><a href="https://wa.me/6285652184533" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
            <li><a href="mailto:ironcladtumblerstainless" target="_blank"><i class="fas fa-envelope"></i></a></li>
            <li><a href="https://youtube.com/@ironclad-h3v?si=SPHawnPFVRqJUi5r" target="_blank"><i class="fab fa-youtube"></i></a></li>
            <li><a href="https://www.tiktok.com/@ironcladtumbler" target="_blank"><i class="fab fa-tiktok"></i></a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Iron Clad Tumblers. All rights reserved.</p>
    </footer>
</body>
</html>
# ironcladtumblerstainless

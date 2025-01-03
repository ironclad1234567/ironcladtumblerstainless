<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Iron Clad</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #0b0b0b;
            color: white;
        }

        header {
            background-color: #1e1e1e;
            padding: 10px 0;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.6);
        }

        header .logo h1 {
            font-size: 2.5em;
            color: #e63946;
            font-family: 'Impact', sans-serif;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        header .nav-links {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        header .nav-links li {
            margin: 0 15px;
        }

        header .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
        }

        /* Hero Section */
        #hero {
            background-image: url('https://images.unsplash.com/photo-1578367680904-026e165ee621?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&q=80&w=1080'); 
            background-size: cover;
            background-position: center;
            height: 600px;
            text-align: center;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .hero-text h2 {
            font-size: 3.5em;
            font-family: 'Impact', sans-serif;
            letter-spacing: 2px;
            margin-bottom: 20px;
        }

        .hero-text p {
            font-size: 1.5em;
        }

        /* About Section */
        #about {
            padding: 40px;
            background-color: #222;
            text-align: center;
        }

        #about h2 {
            font-size: 2.5em;
            color: #e63946;
            margin-bottom: 20px;
        }

        /* Products Section */
        #products {
            padding: 40px;
            background-color: #333;
            text-align: center;
        }

        .product-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .product {
            width: 30%;
            margin: 15px;
            text-align: center;
            background-color: #444;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.7);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .product h3 {
            color: #e63946;
            font-size: 1.5em;
            margin: 10px 0;
        }

        .product p {
            color: #ccc;
        }

        .product .price {
            font-size: 1.2em;
            color: #f4a261;
            margin: 10px 0;
        }

        /* Contact Section */
        #contact {
            padding: 40px;
            background-color: #222;
            text-align: center;
        }

        #contact h2 {
            font-size: 2.5em;
            color: #e63946;
            margin-bottom: 20px;
        }

        #contact .social-icons {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px 0;
        }

        #contact .social-icons li {
            margin: 10px;
        }

        #contact .social-icons a {
            color: white;
            font-size: 2em;
            text-decoration: none;
        }

        /* Footer */
        footer {
            background-color: #1e1e1e;
            padding: 10px;
            text-align: center;
            color: white;
        }

        footer p {
            font-size: 1em;
        }

        /* Media Queries */
        @media (max-width: 768px) {
            header .nav-links {
                flex-direction: column;
            }

            header .nav-links li {
                margin: 10px 0;
            }

            #hero {
                height: 400px;
            }

            .hero-text h2 {
                font-size: 2em;
            }

            .hero-text p {
                font-size: 1em;
            }

            .product {
                width: 80%;
                margin: 15px auto;
            }
        }

        @media (max-width: 480px) {
            header .logo h1 {
                font-size: 1.8em;
            }

            .hero-text h2 {
                font-size: 1.8em;
            }

            .hero-text p {
                font-size: 0.9em;
            }

            .product {
                width: 90%;
            }

            #contact h2 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <h1>Iron Clad</h1>
        </div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </header>

    <section id="hero">
        <div class="hero-text">
            <h2>Kekuatan dan Gaya Dalam Satu Genggaman</h2>
            <p>Strong Tumblers for Stronger Lives</p>
        </div>
    </section>

    <section id="about">
        <h2>About Iron Clad</h2>
        <p>Menggunakan Istilah "IRONCLAD"
yang Berarti Kuat dan Tidak Tertembus,
Menggambarkan Kualitas Tumbler. IRONCLAD: Teman Setia Untuk Gaya Hidup Aktifmu.  Tumbler Metal yang Kuat dan Stylish ini Menjaga Minumanmu Tetap Dingin atau Panas, di Mana pun Kamu Berada.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-container">
            <div class="product">
                <img src="https://i.imgur.com/Ok9W7K0.jpeg" alt="Tumbler Metal">
                <h3>Iron Clad Tumbler</h3>
                <p>Desain ergonomis dengan bahan berkualitas tinggi yang menjaga suhu minuman sepanjang hari.</p>
                <p class="price">Rp 85.000</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <ul class="social-icons">
            <li><a href="https://www.instagram.com/ironcladtumbler/" target="_blank"><i class="fab fa-instagram"></i></a></li>
            <li><a href="https://wa.me/6285652184533" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
            <li><a href="https://www.facebook.com/profile.php?id=61571167660047&mibextid=ZbWKwL" target="_blank"><i class="fab fa-facebook"></i></a></li>
            <li><a href="mailto:ironcladtumbler@gmail.com" target="_blank"><i class="fas fa-envelope"></i></a></li>
            <li><a href="https://www.tiktok.com/@ironcladtumbler" target="_blank"><i class="fab fa-tiktok"></i></a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Iron Clad Tumblers. All rights reserved.</p>
    </footer>
</body>
</html>
# ironcladtumblerstainless

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valorant Skins Shop</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
        }
        header {
            background: #1f1f1f;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 1.5rem;
            color: #ff4655;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ff4655;
        }
        .hero {
            text-align: center;
            padding: 3rem 2rem;
            background: url('hero-image.jpg') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .hero a {
            text-decoration: none;
            padding: 0.8rem 2rem;
            background: #ff4655;
            color: #fff;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s;
        }
        .hero a:hover {
            background: #e13c4a;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }
        .product {
            background: #1f1f1f;
            border-radius: 8px;
            padding: 1rem;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 1rem;
        }
        .product h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
        }
        .product p {
            margin-bottom: 1rem;
            color: #ccc;
        }
        .product a {
            text-decoration: none;
            padding: 0.5rem 1rem;
            background: #ff4655;
            color: #fff;
            border-radius: 5px;
            font-size: 0.9rem;
            transition: background 0.3s;
        }
        .product a:hover {
            background: #e13c4a;
        }
        footer {
            background: #1f1f1f;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Valorant Skins Shop</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Discover Exclusive Valorant Skins</h2>
        <p>Browse our collection of the rarest skins and upgrade your arsenal today!</p>
        <a href="#shop">Shop Now</a>
    </section>
    <section id="shop" class="products">
        <div class="product">
            <img src="skin1.jpg" alt="Phantom Skin">
            <h3>Phantom Skin</h3>
            <p>$15.99</p>
            <a href="#">Buy Now</a>
        </div>
        <div class="product">
            <img src="skin2.jpg" alt="Vandal Skin">
            <h3>Vandal Skin</h3>
            <p>$18.99</p>
            <a href="#">Buy Now</a>
        </div>
        <div class="product">
            <img src="skin3.jpg" alt="Operator Skin">
            <h3>Operator Skin</h3>
            <p>$21.99</p>
            <a href="#">Buy Now</a>
        </div>
        <div class="product">
            <img src="skin4.jpg" alt="Classic Skin">
            <h3>Classic Skin</h3>
            <p>$9.99</p>
            <a href="#">Buy Now</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Valorant Skins Shop. All rights reserved.</p>
    </footer>
</body>
</html>

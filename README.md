<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ameerah's Pure Touch</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: #f5fff7;
            color: #333;
        }
        header {
            background: #ffffff;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        header h1 {
            color: #228B22;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #e0f2e9;
            padding: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #2f4f2f;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 30px;
            background: #eaffea;
        }
        .hero img {
            width: 220px;
            border-radius: 12px;
        }
        .price {
            font-size: 22px;
            color: #388e3c;
            margin: 15px 0;
        }
        .button-container {
            margin-top: 10px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            margin: 5px;
            cursor: pointer;
            border-radius: 5px;
        }
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            animation: pulse 1.5s infinite;
            z-index: 999;
        }
        .whatsapp-button img {
            width: 35px;
            margin: 12px;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        footer {
            text-align: center;
            background-color: #e0f2e9;
            padding: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ameerah's Pure Touch</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Products</a>
        <a href="#">Testimonials</a>
        <a href="#">Contact</a>
    </nav>
    <div class="hero">
        <img src="product.jpg" alt="Organic Hair Oil">
        <div class="price">৳380.00 (120ml)</div>
        <div class="button-container">
            <button>Add to Cart</button>
            <button>Buy Now</button>
        </div>
        <p>Estimated Delivery: Mon, Jul 21 – Sat, Jul 26</p>
        <p><strong>49 people</strong> are viewing this right now</p>
    </div>

    <a href="https://wa.me/8801XXXXXXXXX" class="whatsapp-button" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="Chat on WhatsApp">
    </a>

    <footer>
        &copy; 2025 Ameerah's Pure Touch. All rights reserved.
    </footer>
</body>
</html>

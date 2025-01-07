# Yiminoodle
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yimi Noodle - 一米一线</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff7043;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff5722;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ff8a65;
        }
        .container {
            padding: 20px;
        }
        .menu-item {
            display: flex;
            border: 1px solid #ddd;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .menu-item img {
            width: 150px;
            height: 150px;
            border-radius: 5px 0 0 5px;
        }
        .menu-item div {
            padding: 10px;
        }
        footer {
            background-color: #ff7043;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .order-button {
            background-color: #ff5722;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .order-button:hover {
            background-color: #ff8a65;
        }
    </style>
</head>
<body>
    <header>
        <h1>一米一线 | Yimi Noodle</h1>
        <p>深惜的手工面，依流山而贵</p>
    </header>
    
    <nav>
        <a href="#menu">Menu</a>
        <a href="#order">Order</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <div id="menu" class="container">
        <h2>Menu</h2>
        <div class="menu-item">
            <img src="noodle1.jpg" alt="Classic Noodles">
            <div>
                <h3>Classic Noodles</h3>
                <p>Handmade noodles with a rich broth and fresh vegetables.</p>
                <p>Price: $12</p>
                <button class="order-button">Add to Order</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="noodle2.jpg" alt="Spicy Beef Noodles">
            <div>
                <h3>Spicy Beef Noodles</h3>
                <p>Flavorful beef paired with spicy broth and handmade noodles.</p>
                <p>Price: $15</p>
                <button class="order-button">Add to Order</button>
            </div>
        </div>
        <!-- Add more menu items here -->
    </div>

    <div id="order" class="container">
        <h2>Order</h2>
        <p>Coming Soon: Full online ordering system!</p>
    </div>

    <div id="about" class="container">
        <h2>About Us</h2>
        <p>Yimi Noodle (一米一线) is dedicated to bringing authentic handmade noodles to your table. Inspired by the culinary traditions of Yunnan, our dishes are crafted with care and passion.</p>
    </div>

    <div id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Email: contact@yiminoodle.com</p>
        <p>Phone: +86 123 456 7890</p>
        <p>WeChat: YimiNoodleOfficial</p>
    </div>

    <footer>
        <p>&copy; 2025 Yimi Noodle. All rights reserved.</p>
    </footer>
</body>
</html>

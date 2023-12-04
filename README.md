# surajp87.2.github.io
website for samsung productshttps://github.com/SurajP87/surajp87.2.github.io/tree/main
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samsung Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1em;
            text-align: center;
        }

        nav {
            background-color: #4CAF50;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product-card {
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: white;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Samsung Products</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Phones</a>
        <a href="#">Tablets</a>
        <a href="#">Wearables</a>
        <a href="#">Accessories</a>
        <input type="text" placeholder="Search...">
    </nav>

    <div class="product-container">
        <div class="product-card">
            <img src="samsung-phone.jpg" alt="Samsung Phone">
            <h2>Samsung Galaxy S21</h2>
            <p>Powerful smartphone with great features.</p>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="samsung-tablet.jpg" alt="Samsung Tablet">
            <h2>Samsung Galaxy Tab S7</h2>
            <p>High-performance tablet for productivity.</p>
            <button>Add to Cart</button>
        </div>

        <!-- Add more product cards as needed -->

    </div>

    <footer>
        <p>&copy; 2023 Samsung Products. All rights reserved.</p>
    </footer>
</body>

</html>

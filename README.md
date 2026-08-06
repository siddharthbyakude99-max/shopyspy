<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Products Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.2s;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0 5px 0;
        }
        .product p {
            padding: 0 15px 15px 15px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Digital Products Gallery</h1>
    </header>
    
    <section class="gallery">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 1">
            <h3>Fashion Accessory 1</h3>
            <p>Elegant scarf with floral patterns.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 2">
            <h3>Fashion Accessory 2</h3>
            <p>Stylish sunglasses for every occasion.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 3">
            <h3>Fashion Product 3</h3>
            <p>Minimalist bracelet with a modern twist.</p>
        </div>
        <!-- Add more products as needed -->
    </section>
</body>
</html>

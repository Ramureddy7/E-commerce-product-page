# E-commerce-product-page
 e-commerce product page using HTML and CSS. Here's a simple layout for a product page:
html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Product Name</h1>
        <p>Product Description Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, ad.</p>
    </header>
    <main>
        <div class="product-image">
            <img src="product-image.jpg" alt="Product Image">
        </div>
        <div class="product-details">
            <h2>$99.99</h2>
            <p>Availability: In Stock</p>
            <p>Description: Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatem?</p>
            <button>Add to Cart</button>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 E-commerce Store</p>
    </footer>
</body>
</html>
css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
}

.product-image {
    margin-right: 50px;
}

.product-details {
    text-align: left;
}

.product-details h2 {
    color: #333;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 15px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

# bharat-mobile-beats
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bharat Mobile Beats - E-commerce</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #007BFF;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .logo {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .category, .tags, .cart {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .category h2, .tags h2, .cart h2 {
            color: #007BFF;
        }
        .category ul, .tags ul {
            list-style: none;
            padding: 0;
        }
        .category ul li, .tags ul li {
            display: inline-block;
            background: #007BFF;
            color: white;
            padding: 10px;
            margin: 5px;
            border-radius: 3px;
        }
        .cart button {
            background-color: #007BFF;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Welcome to Bharat Mobile Beats</h1>
    </div>
    <div class="logo">
        <img src="logo.png" alt="Bharat Mobile Beats Logo" width="200">
    </div>
    <div class="container">
        <div class="category">
            <h2>Categories</h2>
            <ul>
                <li>Mobile Phone Shop</li>
                <li>Computer Accessories Shop</li>
                <li>Appliance Store</li>
                <li>Mobile Phone Accessory Shop</li>
                <li>Electronics Retail And Repair Shop</li>
            </ul>
        </div>
        <div class="tags">
            <h2>Popular Tags</h2>
            <ul>
                <li>Smartphone Near Me</li>
                <li>Mobiles Near Me</li>
                <li>5G Mobile Near Me</li>
                <li>TVs Near Me</li>
                <li>Refrigerators in Sector 12, Dwarka</li>
                <li>Laptops in Sector 12, Dwarka</li>
                <li>Gaming Laptops in Sector 12, Dwarka</li>
                <li>Washing Machines in Sector 12, Dwarka</li>
            </ul>
        </div>
        <div class="cart">
            <h2>Shopping Cart</h2>
            <p>No items in cart</p>
            <button onclick="alert('Proceeding to checkout...')">Checkout</button>
        </div>
    </div>
</body>
</html>

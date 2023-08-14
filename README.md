<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farnham Fudge Delights</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, h3, p, ul, li {
            margin: 0;
            padding: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4caf50;
            color: white;
            text-align: center;
            padding: 1em;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        .banner {
            text-align: center;
            padding: 2em;
        }
        .banner img {
            max-width: 100%;
            height: auto;
        }
        .about {
            background-color: #fff;
            padding: 2em;
        }
        .flavors {
            background-color: #f5f5f5;
            padding: 2em;
        }
        .flavor-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .flavor-gallery img {
            max-width: 100%;
            height: auto;
            margin: 10px;
        }
        .order {
            background-color: #fff;
            padding: 2em;
        }
        .order-form {
            text-align: center;
        }
        .order-button {
            background-color: #4caf50;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        .order-button:hover {
            background-color: #45a049;
        }
        .contact {
            background-color: #f5f5f5;
            padding: 2em;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Barnaby's Fudge</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#flavors">Fudge Flavours</a></li>
                <li><a href="#order">Order Online</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="banner">
        <img src="(https://github.com/bnab310/bnab310.github.io/assets/142220226/33704c7e-a3c9-4d02-8201-c3d9921a7340)">
        <h2>Indulge in the Finest Fudge in Farnham!</h2>
    </div>

    <div class="about" id="about">
        <h2>About Us</h2>
        <p>Hi, i am Barnaby law. I live on middle avenue and i have decided to earn some money by selling fudge. for my first batch i went door to door selling the fudge. that went well so i made a website for if people wanted to buy more fudge.</p>
    </div>

    <div class="flavors" id="flavors">
        <h2>Fudge Flavors</h2>
        <div class="flavor-gallery">
            <img src="(https://tse3.mm.bing.net/th?id=OIP.ljwAIqMKQg-qSR4kJJJm-QHaFj&pid=Api&P=0&h=180)" alt="vanilla Fudge">
            <img src="(https://tse4.mm.bing.net/th?id=OIP.4d0A34czodQaPWSiYyu_ZQHaFj&pid=Api&P=0&h=180)" alt="chocolate Fudge">
            <!-- Add more flavor images as needed -->
        </div>
    </div>

    <div class="order" id="order">
        <h2>Order Online</h2>
        <div class="order-form">
            <p>Order our delicious fudge online and enjoy our 10-minute bike ride delivery service within our delivery zone.</p>
            <form action="order.php" method="post">
                <label for="flavor">Select a Flavor:</label>
                <select name="flavor" id="flavor">
                    <option value="vanilla">Flavor 1</option>
                    <option value="chocolate">Flavor 2</option>
                    <!-- Add more flavor options as needed -->
                </select>
                <br>
                <label for="quantity">Quantity:</label>
                <input type="number" name="quantity" id="quantity" min="1" required>
                <br>
                <label for="address">Delivery Address:</label>
                <input type="text" name="address" id="address" required>
                <br>
                <button type="submit" class="order-button">Place Order</button>
            </form>
        </div>
    </div>

    <div class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or inquiries, please reach out to us using the contact form below or through our phone number or email.</p>
        <!-- Include a contact form here -->
    </div>

    <div class="footer">
        <p>&copy; 2023 Farnham Fudge Delights. All rights reserved.</p>
    </div>
</body>
</html>

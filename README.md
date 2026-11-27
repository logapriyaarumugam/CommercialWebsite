# Ex02 Commercial Website
## Date:27.11.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - About Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section class="about">
    <h2>About EcoNest</h2>
    <p>
        EcoNest is an eco-friendly online shopping store
        that offers sustainable products for everyday use.
        We believe in making small changes to create a
        cleaner and greener environment.
    </p>

    <h2>Our Mission</h2>
    <p>
        Our mission is to encourage people to choose
        reusable and environmentally friendly products
        for a better future.
    </p>

    <h2>Why Choose Us?</h2>
    <p>
        Quality Products | Affordable Prices |
        Sustainable Lifestyle
    </p>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>Live Green. Choose Better.</p>
    <div class="social">
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.pinterest.com/">Pinterest</a>
    </div>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

</body>
</html>

account.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - Account</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section class="account">
    <h2>User Login</h2>

    <form onsubmit="event.preventDefault(); alert('Login demo completed!');">
        <input type="text" placeholder="Enter Username" required>
        <input type="email" placeholder="Enter Email" required>
        <input type="password" placeholder="Enter Password" required>
        <button type="submit">Login</button>
    </form>

    <p class="account-text">Welcome back to EcoNest!</p>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>Live Green. Choose Better.</p>
    <div class="social">
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.pinterest.com/">Pinterest</a>
    </div>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

</body>
</html>

contact.html



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section class="contact">
    <h2>Contact Us</h2>
    <p>We would love to hear from you!</p>

    <form onsubmit="event.preventDefault(); alert('Thank you for contacting EcoNest!');">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <input type="text" placeholder="Subject" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>

    <div class="contact-info">
        <p>Email: hello@econest.com</p>
        <p>Phone: +91 98765 43210</p>
        <p>Location: Coimbatore, Tamil Nadu</p>
    </div>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>Live Green. Choose Better.</p>
    <div class="social">
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.pinterest.com/">Pinterest</a>
    </div>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section class="home">
    <div class="home-content">
        <h2>Live Green, Choose Better</h2>
        <p>Discover beautiful and eco-friendly products
        for your everyday lifestyle.</p>
        <a href="products.html" class="btn">Explore Products</a>
    </div>
</section>

<section class="welcome">
    <h2>Welcome to EcoNest</h2>
    <p>Make your everyday life simple, stylish and sustainable
    with our eco-friendly collections.</p>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>Live Green. Choose Better.</p>
    <div class="social">
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.pinterest.com/">Pinterest</a>
    </div>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

</body>
</html>

product.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - Product Details</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section class="product-page">
    <div class="details">
        <h2>Product Details</h2>
        <h3 id="name"></h3>
        <p>Thank you for choosing our eco-friendly products.</p>
        <h3 id="price"></h3>
        <button onclick="alert('Thank you for choosing EcoNest!')">
            Confirm Product
        </button>
        <br><br>
        <a href="products.html" class="btn">Back to Products</a>
    </div>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

<script>
    const products = {
        "Bamboo Toothbrush": "₹149",
        "Printed Tote Bag": "₹299",
        "Desk Organizer": "₹399",
        "Glass Water Bottle": "₹349",
        "Scented Candles": "₹249",
        "Reusable Lunch Box": "₹499"
    };

    const params = new URLSearchParams(window.location.search);
    const item = params.get("item");

    document.getElementById("name").textContent =
        item || "Product Not Found";

    document.getElementById("price").textContent =
        products[item] || "";
</script>

</body>
</html>

products.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoNest - Products</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>EcoNest</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
        <a href="account.html">Account</a>
    </nav>
</header>

<section id="products">
    <h2>Our Eco-Friendly Products</h2>
    <p class="subtitle">Simple choices for a greener lifestyle</p>

    <div class="product-container">

        <div class="product">
            <img src="https://images.unsplash.com/photo-1607613009820-a29f7bb81c04?w=500" alt="Bamboo toothbrush">
            <h3>Bamboo Toothbrush</h3>
            <p>₹149</p>
            <a class="buy-btn" href="product.html?item=Bamboo%20Toothbrush">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1590874103328-eac38a683ce7?w=500" alt="Tote bag">
            <h3>Printed Tote Bag</h3>
            <p>₹299</p>
            <a class="buy-btn" href="product.html?item=Printed%20Tote%20Bag">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1494438639946-1ebd1d20bf85?w=500" alt="Desk organizer">
            <h3>Desk Organizer</h3>
            <p>₹399</p>
            <a class="buy-btn" href="product.html?item=Desk%20Organizer">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1602143407151-7111542de6e8?w=500" alt="Water bottle">
            <h3>Glass Water Bottle</h3>
            <p>₹349</p>
            <a class="buy-btn" href="product.html?item=Glass%20Water%20Bottle">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1603006905003-be475563bc59?w=500" alt="Candles">
            <h3>Scented Candles</h3>
            <p>₹249</p>
            <a class="buy-btn" href="product.html?item=Scented%20Candles">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1547592180-85f173990554?w=500" alt="Lunch box">
            <h3>Reusable Lunch Box</h3>
            <p>₹499</p>
            <a class="buy-btn" href="product.html?item=Reusable%20Lunch%20Box">Buy Now</a>
        </div>

    </div>
</section>

<footer>
    <h3>EcoNest</h3>
    <p>Live Green. Choose Better.</p>
    <div class="social">
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.pinterest.com/">Pinterest</a>
    </div>
    <p>© 2026 EcoNest. All Rights Reserved.</p>
</footer>

</body>
</html>

style.css


/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background-color: #faf9f5;
    color: #333;
}

/* Header */
header {
    background-color: #244b38;
    color: white;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 30px;
}

nav {
    display: flex;
    gap: 25px;
}

nav a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

nav a:hover {
    color: #c5dfaa;
}

/* Home */
.home {
    min-height: 420px;
    background: linear-gradient(
        rgba(30,65,45,0.65),
        rgba(30,65,45,0.65)
    ),
    url("https://images.unsplash.com/photo-1441974231531-c6227db76b6e?w=1400");
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    padding: 30px;
}

.home h2 {
    font-size: 42px;
    margin-bottom: 18px;
}

.home p {
    font-size: 18px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background-color: #d5e8bd;
    color: #244b38;
    padding: 13px 28px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn:hover {
    background-color: white;
}

.welcome {
    text-align: center;
    padding: 65px 20px;
    line-height: 2;
}

/* Products */
#products {
    padding: 55px 8%;
    text-align: center;
}

#products h2 {
    color: #244b38;
    font-size: 30px;
}

.subtitle {
    margin: 15px 0 35px;
    color: #777;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.product {
    background-color: white;
    width: 270px;
    padding: 18px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.product:hover {
    transform: translateY(-8px);
}

.product img {
    width: 100%;
    height: 190px;
    object-fit: cover;
    border-radius: 8px;
}

.product h3 {
    margin: 16px 0 10px;
    color: #244b38;
}

.product p {
    color: #638b4e;
    font-weight: bold;
    margin-bottom: 15px;
    font-size: 18px;
}

.buy-btn {
    display: inline-block;
    background-color: #244b38;
    color: white;
    padding: 11px 22px;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.buy-btn:hover {
    background-color: #527b50;
}

/* About */
.about {
    background-color: #e9efe4;
    padding: 65px 10%;
    text-align: center;
    min-height: 450px;
}

.about h2 {
    color: #244b38;
    margin: 25px 0;
}

.about p {
    max-width: 800px;
    margin: auto;
    line-height: 1.8;
    font-size: 17px;
}

/* Contact */
.contact {
    padding: 55px 20px;
    text-align: center;
}

.contact h2 {
    color: #244b38;
    margin-bottom: 20px;
}

.contact form,
.account form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 350px;
    margin: 25px auto;
}

.contact input,
.contact textarea,
.account input {
    padding: 13px;
    border: 1px solid #ccc;
    border-radius: 5px;
    outline: none;
}

.contact textarea {
    min-height: 120px;
    resize: vertical;
}

.contact-info {
    line-height: 2;
}

/* Account */
.account {
    background-color: #e9efe4;
    padding: 65px 20px;
    text-align: center;
    min-height: 450px;
}

.account h2 {
    color: #244b38;
}

.account-text {
    color: #527b50;
}

/* Product Details */
.product-page {
    min-height: 450px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px 20px;
    background-color: #e9efe4;
    text-align: center;
}

.details {
    background-color: white;
    padding: 45px;
    max-width: 500px;
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.details h2,
.details h3 {
    color: #244b38;
    margin-bottom: 20px;
}

.details p {
    line-height: 1.7;
    margin-bottom: 20px;
}

/* Buttons */
button {
    background-color: #244b38;
    color: white;
    border: none;
    padding: 12px 22px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #527b50;
}

/* Footer */
footer {
    background-color: #244b38;
    color: white;
    text-align: center;
    padding: 28px;
}

footer h3 {
    font-size: 25px;
    margin-bottom: 10px;
}

.social {
    margin: 18px 0;
}

.social a {
    color: white;
    text-decoration: none;
    margin: 12px;
}

.social a:hover {
    color: #c5dfaa;
}

/* Responsive Design */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        gap: 20px;
    }

    nav {
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }

    .home h2 {
        font-size: 30px;
    }

    .product {
        width: 100%;
        max-width: 300px;
    }
}
```
## OUTPUT
![alt text](<Screenshot 2026-11-27 153747.png>)
![alt text](<Screenshot 2026-11-27 153757.png>)
![alt text](<Screenshot 2026-11-27 153809.png>)
![alt text](<Screenshot 2026-11-27 153818.png>)
![alt text](<Screenshot 2026-11-27 153827.png>)
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.

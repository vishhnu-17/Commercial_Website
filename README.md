## Date:29-5-26

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="ShopEase - Your one-stop online shopping destination for quality products at great prices.">
    <title>ShopEase - Online Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>


    <header>
        <div class="logo">ShopEase</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">My Account</a></li>
            </ul>
        </nav>
    </header>


    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to ShopEase</h1>
            <p>Discover quality products at unbeatable prices. Shop from the comfort of your home.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
        <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da?w=500&h=350&fit=crop" alt="Shopping banner">
        </div>
    </section>


    <section id="products" class="products">
        <h2>Our Products</h2>
        <p class="section-desc">Browse through our wide range of quality products</p>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1546868871-7041f2a55e12?w=250&h=200&fit=crop" alt="Watch">
                <h3>Smart Watch</h3>
                <p>Premium quality smartwatch with fitness tracking.</p>
                <span class="price">₹2,999</span>
                <button class="btn-small">Add to Cart</button>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1618366712010-f4ae9c647dcb?w=250&h=200&fit=crop" alt="Headphones">
                <h3>Wireless Headphones</h3>
                <p>Noise cancelling headphones for crystal clear audio.</p>
                <span class="price">₹1,499</span>
                <button class="btn-small">Add to Cart</button>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1594035910387-fea47794261f?w=250&h=200&fit=crop" alt="Perfume">
                <h3>Luxury Perfume</h3>
                <p>Long lasting fragrance for every occasion.</p>
                <span class="price">₹899</span>
                <button class="btn-small">Add to Cart</button>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=250&h=200&fit=crop" alt="Shoes">
                <h3>Running Shoes</h3>
                <p>Comfortable and durable shoes for everyday use.</p>
                <span class="price">₹1,999</span>
                <button class="btn-small">Add to Cart</button>
            </div>
        </div>
    </section>


    <section id="about" class="about">
        <div class="about-content">
            <div class="about-text">
                <h2>About Us</h2>
                <p>ShopEase was founded in 2020 with a simple goal — to make online shopping easy, affordable, and enjoyable for everyone.</p>
                <p>We offer a wide range of products from trusted brands and ensure fast delivery right to your doorstep.</p>
                <ul>
                    <li>✔ 10,000+ Products</li>
                    <li>✔ Fast Delivery</li>
                    <li>✔ Easy Returns</li>
                    <li>✔ 24/7 Support</li>
                </ul>
            </div>
            <div class="about-image">
                <img src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=400&h=300&fit=crop" alt="About Us">
            </div>
        </div>
    </section>


    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p class="section-desc">We'd love to hear from you!</p>
        <div class="contact-wrapper">
            <div class="contact-info">
                <h3>Get In Touch</h3>
                <p>123, MG Road, Bangalore - 560001</p>
                <p>+91 98765 43210</p>
                <p>support@shopease.com</p>
                <p>Mon - Sat: 9am to 6pm</p>
            </div>
            <div class="contact-form">
                <form>
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="4" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>


    <section id="account" class="account">
        <h2>My Account</h2>
        <p class="section-desc">Login or create an account to track your orders</p>
        <div class="account-box">
            <div class="login-box">
                <h3>Login</h3>
                <form>
                    <input type="email" placeholder="Email Address" required>
                    <input type="password" placeholder="Password" required>
                    <button type="submit" class="btn">Login</button>
                    <a href="#" class="forgot">Forgot Password?</a>
                </form>
            </div>
            <div class="register-box">
                <h3>New Customer?</h3>
                <p>Create an account to enjoy exclusive offers, faster checkout, and order tracking.</p>
                <button class="btn">Register Now</button>
            </div>
        </div>
    </section>


    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <h3>ShopEase</h3>
                <p>Your trusted online shopping partner.</p>
            </div>
            <div class="footer-links">
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-social">
                <h4>Follow Us</h4>
                <div class="social-links">
                    <a href="#" class="social-icon">Facebook</a>
                    <a href="#" class="social-icon">Instagram</a>
                    <a href="#" class="social-icon">Twitter</a>
                    <a href="#" class="social-icon">YouTube</a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 ShopEase. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>

```css
## CSS
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: inherit;
}

ul {
    list-style: none;
}


header {
    background-color: #2c3e50;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    letter-spacing: 1px;
}

nav ul {
    display: flex;
    gap: 25px;
}

nav ul li a {
    color: white;
    font-size: 15px;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #2dd4bf;
}


#home {
    background-color: #ecf0f1;
    padding: 60px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
}

.hero-content {
    flex: 1;
}

.hero-content h1 {
    font-size: 38px;
    color: #2c3e50;
    margin-bottom: 15px;
}

.hero-content p {
    font-size: 16px;
    color: #555;
    margin-bottom: 25px;
}

.hero-image {
    flex: 1;
    text-align: center;
}

.hero-image img {
    width: 100%;
    max-width: 450px;
    border-radius: 8px;
}


.btn {
    display: inline-block;
    background-color: #14b8a6;
    color: white;
    padding: 10px 25px;
    border: none;
    border-radius: 5px;
    font-size: 15px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #0f766e;
}

.btn-small {
    background-color: #2c3e50;
    color: white;
    padding: 7px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 13px;
    margin-top: 8px;
    transition: background-color 0.3s;
}

.btn-small:hover {
    background-color: #14b8a6;
}


section {
    padding: 60px 40px;
}

section h2 {
    text-align: center;
    font-size: 30px;
    color: #2c3e50;
    margin-bottom: 10px;
}

.section-desc {
    text-align: center;
    color: #777;
    margin-bottom: 35px;
    font-size: 15px;
}


#products {
    background-color: #fff;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: center;
}

.product-card {
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    width: 220px;
    text-align: center;
    transition: box-shadow 0.3s;
}

.product-card:hover {
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
}

.product-card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
    border-radius: 5px;
    margin-bottom: 12px;
}

.product-card h3 {
    font-size: 16px;
    margin-bottom: 8px;
    color: #2c3e50;
}

.product-card p {
    font-size: 13px;
    color: #666;
    margin-bottom: 8px;
}

.price {
    display: block;
    font-size: 18px;
    font-weight: bold;
    color: #14b8a6;
    margin-bottom: 5px;
}


#about {
    background-color: #f4f6f7;
}

.about-content {
    display: flex;
    gap: 40px;
    align-items: center;
    justify-content: center;
}

.about-text {
    flex: 1;
    max-width: 500px;
}

.about-text h2 {
    text-align: left;
    margin-bottom: 15px;
}

.about-text p {
    color: #555;
    margin-bottom: 12px;
    font-size: 15px;
}

.about-text ul {
    margin-top: 15px;
}

.about-text ul li {
    padding: 5px 0;
    color: #2c3e50;
    font-size: 15px;
}

.about-image img {
    width: 100%;
    max-width: 380px;
    border-radius: 8px;
}


#contact {
    background-color: #fff;
}

.contact-wrapper {
    display: flex;
    gap: 40px;
    justify-content: center;
    flex-wrap: wrap;
}

.contact-info, .contact-form {
    flex: 1;
    min-width: 260px;
    max-width: 420px;
}

.contact-info h3 {
    font-size: 20px;
    color: #2c3e50;
    margin-bottom: 15px;
}

.contact-info p {
    margin-bottom: 10px;
    font-size: 15px;
    color: #555;
}

.contact-form form {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.contact-form input,
.contact-form textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 14px;
    font-family: Arial, sans-serif;
    outline: none;
    transition: border-color 0.3s;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #14b8a6;
}


#account {
    background-color: #f4f6f7;
}

.account-box {
    display: flex;
    gap: 40px;
    justify-content: center;
    flex-wrap: wrap;
}

.login-box, .register-box {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 30px;
    flex: 1;
    min-width: 260px;
    max-width: 380px;
}

.login-box h3, .register-box h3 {
    font-size: 20px;
    color: #2c3e50;
    margin-bottom: 20px;
}

.login-box form {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.login-box input {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 14px;
    outline: none;
    transition: border-color 0.3s;
}

.login-box input:focus {
    border-color: #14b8a6;
}

.forgot {
    text-align: center;
    color: #14b8a6;
    font-size: 13px;
    transition: color 0.3s;
}

.forgot:hover {
    color: #0f766e;
}

.register-box p {
    color: #666;
    font-size: 14px;
    margin-bottom: 20px;
}


footer {
    background-color: #2c3e50;
    color: #ccc;
    padding: 40px 40px 0;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 30px;
    padding-bottom: 30px;
    border-bottom: 1px solid #3d5166;
}

.footer-brand h3 {
    color: white;
    font-size: 20px;
    margin-bottom: 8px;
}

.footer-brand p {
    font-size: 14px;
}

.footer-links h4, .footer-social h4 {
    color: white;
    margin-bottom: 12px;
    font-size: 16px;
}

.footer-links ul li {
    margin-bottom: 8px;
}

.footer-links ul li a {
    color: #ccc;
    font-size: 14px;
    transition: color 0.3s;
}

.footer-links ul li a:hover {
    color: #2dd4bf;
}

.social-links {
    display: flex;
    flex-direction: column;
    gap: 8px;
}

.social-icon {
    color: #ccc;
    font-size: 14px;
    transition: color 0.3s;
}

.social-icon:hover {
    color: #2dd4bf;
}

.footer-bottom {
    text-align: center;
    padding: 15px 0;
    font-size: 13px;
    color: #aaa;
}
```

## OUTPUT
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/40b304f6-0f72-48f0-beb3-04469c352bc3" />
<img width="1919" height="1069" alt="image" src="https://github.com/user-attachments/assets/fa4303ba-21ba-402a-90ca-3e57ef1fed1d" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/6fc842f6-46ea-4bcf-9fc5-10a1bef647af" />
<img width="1918" height="936" alt="image" src="https://github.com/user-attachments/assets/1a1b29be-375c-4a02-8a4e-7895ece98481" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.

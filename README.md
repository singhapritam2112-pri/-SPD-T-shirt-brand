<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CoolTees - Awesome T-Shirts</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">CoolTees</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="#" id="cart-link">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Welcome to CoolTees</h1>
            <p>Express yourself with our unique, high-quality T-shirts.</p>
            <a href="products.html" class="btn">Shop Now</a>
        </section>
        <section class="featured">
            <h2>Featured Products</h2>
            <div class="product-grid">
                <div class="product">
                    <img src="https://via.placeholder.com/300x300?text=Cool+Graphic+Tee" alt="Graphic Tee">
                    <h3>Graphic Tee</h3>
                    <p>$19.99</p>
                    <button class="add-to-cart" data-id="1" data-name="Graphic Tee" data-price="19.99">Add to Cart</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/300x300?text=Vintage+Style+Tee" alt="Vintage Tee">
                    <h3>Vintage Style Tee</h3>
                    <p>$24.99</p>
                    <button class="add-to-cart" data-id="2" data-name="Vintage Style Tee" data-price="24.99">Add to Cart</button>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 CoolTees. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - CoolTees</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">CoolTees</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="#" id="cart-link">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Our T-Shirts</h1>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/300x300?text=Cool+Graphic+Tee" alt="Graphic Tee">
                <h3>Graphic Tee</h3>
                <p>$19.99</p>
                <button class="add-to-cart" data-id="1" data-name="Graphic Tee" data-price="19.99">Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x300?text=Vintage+Style+Tee" alt="Vintage Tee">
                <h3>Vintage Style Tee</h3>
                <p>$24.99</p>
                <button class="add-to-cart" data-id="2" data-name="Vintage Style Tee" data-price="24.99">Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x300?text=Minimalist+Tee" alt="Minimalist Tee">
                <h3>Minimalist Tee</h3>
                <p>$22.99</p>
                <button class="add-to-cart" data-id="3" data-name="Minimalist Tee" data-price="22.99">Add to Cart</button>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2023 CoolTees. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
  </html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - CoolTees</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">CoolTees</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="#" id="cart-link">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>About CoolTees</h1>
        <p>We create fun, comfortable T-shirts for everyone. Founded in 2023, our mission is to make fashion affordable and expressive.</p>
    </main>
    <footer>
        <p>&copy; 2023 CoolTees. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
      </html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - CoolTees</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">CoolTees</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="#" id="cart-link">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Contact Us</h1>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" required>
            <label for="message">Message:</label>
            <textarea id="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2023 CoolTees. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
header { background: #333; color: white; padding: 1rem; }
nav { display: flex; justify-content: space-between; align-items: center; }
nav ul { list-style: none; display: flex; gap: 1rem; }
nav a { color: white; text-decoration: none; }
.hero { text-align: center; padding: 2rem; background: #f4f4f4; }
.btn { background: #007bff; color: white; padding: 0.5rem 1rem; text-decoration: none; border-radius: 5px; }
.product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; padding: 2rem; }
.product { border: 1px solid #ddd; padding: 1rem; text-align: center; }
.product img { max-width: 100%; }
.add-to-cart { background: #28a745; color: white; border: none; padding: 0.5rem; cursor: pointer; }
footer { text-align: center; padding: 1rem; background: #333; color: white; }
form { max-width: 400px; margin: 2rem auto; display: flex; flex-direction: column; }
form input, form textarea { margin-bottom: 1rem; padding: 0.5rem; }

# fashion

Clothing page HTML Code 

<!DOCTYPE html>
<html lang="en">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Fashion Bliss</title>
    <link rel="stylesheet" href="clothing.css">
</head>

<body>
    
    <div class="about-container">
        <header class="about-header">
            <h1>About Fashion Bliss</h1>
            <p>Your destination for timeless and trendy fashion</p>
        </header>

        <section class="about-content">
            <div class="text-section">
                <h2>Who We Are</h2>
                <p>At Fashion Bliss, we are passionate about empowering individuals through fashion. Since our founding in 2020, we’ve been delivering high-quality apparel, footwear, and accessories for every occasion. Our mission is to bring style, sustainability, and confidence to your wardrobe.</p>
                <p>We believe fashion is an art form that allows everyone to express their unique personality. Explore our exclusive collections tailored to meet your needs.</p>
                <section class="mission">
                    <h2>Our Mission</h2>
                    <p>To inspire and empower individuals through cutting-edge fashion and sustainable practices.</p>
                </section>
                <section class="history">
                    <h2>Our Story</h2>
                    <p>Founded in 2010, we began as a small team passionate about creating unique, stylish, and sustainable apparel. Over the years, we’ve grown into a global brand recognized for innovation and quality.</p>
                </section>
                <a href="shop.html" class="btn">Explore Our Collection</a>
            </div>
            <!-- <div class="image-section">
                <img src="fashion.jpg" alt="Fashion Bliss" />
            </div> -->
        </section>

        <section class="about-highlights">
            <h2>Why Choose Us?</h2>
            <div class="highlights-container">
                <div class="highlight">
                    <h3>Quality You Can Trust</h3>
                    <p>We source premium materials and focus on exceptional craftsmanship.</p>
                </div>
                <div class="highlight">
                    <h3>Sustainability Matters</h3>
                    <p>Our eco-friendly practices ensure a better future for our planet.</p>
                </div>
                <div class="highlight">
                    <h3>Customer First</h3>
                    <p>Your satisfaction drives everything we do.</p>
                    
                </div>
            </div>
            <div class="team-grid">
                <div class="team-member">
                    <img src="portrait-modern-man.jpg" alt="Founder">
                    <h3>Nithin</h3>
                    <p>Developer</p>
                </div>
                <div class="team-member">
                    <img src="pexels-jeffreyreed-769749.jpg" alt="Designer">
                    <h3>Chaitanya</h3>
                    <p>Lead Designer</p>
                </div>
                
            </div>
        </section>
            </section>
        </div>
        <section class="cta">
            <h2>Join Us on Our Journey</h2>
            <p>Explore our collections and discover the world of limitless fashion possibilities.</p>
            <a href="shop.html" class="cta-button">Shop Now</a>
        </section>
        </section>
    </div>


</body>

</html>


 
Now i will share CSS code for About page


@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: white;
}

/* Header Section */
.about-header {
    text-align: center;
    padding: 30px;
    background-color: #ff6347;
    color: white;
}

.about-header h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.about-header p {
    font-size: 18px;
    margin-top: 5px;
}
.header h1 {
    font-size: 24px;
}

.navbar {
    color: azure;
    text-decoration: none;
    margin: 0 10px;
    font-size: 16px;
}

.navbar a:hover {
    color: #ff6347;
}


/* About Content */
.about-content {
    display: flex;
    flex-wrap: wrap;
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
    background: white;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.text-section {
    flex: 1;
    padding: 20px;
}

.text-section h2 {
    font-size: 28px;
    margin-bottom: 10px;
    color: #ff6347;
}

.text-section p {
    margin-bottom: 15px;
    font-size: 16px;
}

.btn {
    display: inline-block;
    background-color: #ff6347;
    padding: 10px 20px;
    color: white;
    border-radius: 5px;
    font-size: 16px;
    text-align: center;
    margin-top: 10px;
}

.btn:hover {
    background-color: #e5533d;
}

.image-section {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
}

.image-section img {
    max-width: 100%;
    border-radius: 10px;
}

/* Highlights Section */
.about-highlights {
    text-align: center;
    padding: 30px;
    background: #f1f1f1;
}

.about-highlights h2 {
    font-size: 28px;
    margin-bottom: 20px;
}

.highlights-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.highlight {
    flex: 1;
    min-width: 250px;
    padding: 15px;
    background: white;
    border-radius: 8px;
    box-shadow: 0px 4px 8
}
.team {
    background-color: #f1f1f1;
}

.team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.team-member {
    text-align: center;
    max-width: 200px;
}

.team-member img {
    width: 100%;
    border-radius: 50%;
    margin-bottom: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.team-member h3 {
    color: #333;
    font-size: 18px;
}

.team-member p {
    font-size: 14px;
    color: #777;
}

.achievements ul {
    list-style: none;
    padding: 0;
    margin-top: 20px;
}

.achievements li {
    font-size: 16px;
    margin-bottom: 10px;
    color: #555;
}
.cta p {
    font-size: 18px;
}

.cta-button {
    display: inline-block;
    background-color: white;
    color: #ff6347;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 16px;
    border-radius: 5px;
    margin-top: 20px;
    text-align:center;
}

.cta-button:hover {
    background-color: #ffe5e0;
}

Now i will share the Product page  in that HTML Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Store - Categories</title>
    <link rel="stylesheet" href="products.css">
</head>
<body>
    <header class="header">
        <nav class="navbar">
            <a href="#" class="logo">Fashion Store</a>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Men</a></li>
                <li><a href="#">Women</a></li>
                <li><a href="#">Kids</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Boys Category -->
    <section class="category">
        <h2>Boys Fashion</h2>
        <div class="filters">
            <label for="size">Size:</label>
            <select id="size">
                <option value="all">All Sizes</option>
                <option value="small">Small</option>
                <option value="medium">Medium</option>
                <option value="large">Large</option>
            </select>
            <label for="price">Price:</label>
            <select id="price">
                <option value="all">All Prices</option>
                <option value="low">Low to High</option>
                <option value="high">High to Low</option>
            </select>
        </div>

        <div class="product-grid">
            <div class="product">
                <img src="Screenshot 2024-11-27 101913.png">
                <h3>Boys T-shirt</h3>
                <p class="price">Rs.2000</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="WhatsApp Image 2024-11-27 at 9.55.32 AM (7).jpeg" alt="Boys Jeans">
                <h3>Boys Jeans</h3>
                <p class="price">Rs.2500</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="jacket.jpeg">
                <h3>Boys Jacket</h3>
                <p class="price">Rs.500</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- Women Category -->
    <section class="category">
        <h2>Women Fashion</h2>
        <div class="filters">
            <label for="size">Size:</label>
            <select id="size">
                <option value="all">All Sizes</option>
                <option value="small">Small</option>
                <option value="medium">Medium</option>
                <option value="large">Large</option>
            </select>
            <label for="price">Price:</label>
            <select id="price">
                <option value="all">All Prices</option>
                <option value="low">Low to High</option>
                <option value="high">High to Low</option>
            </select>
        </div>

        <div class="product-grid">
            <div class="product">
                <img src="suits.png" alt="Women Dress">
                <h3>Women Dress</h3>
                <p class="price">Rs.750</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="tops.png" alt="Women Top">
                <h3>Women Top</h3>
                <p class="price">Rs.455</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="skrit.png" alt="Women Skirt">
                <h3>Women Skirt</h3>
                <p class="price">Rs.1000</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- Children Category -->
    <section class="category">
        <h2>Children Fashion</h2>
        <div class="filters">
            <label for="size">Size:</label>
            <select id="size">
                <option value="all">All Sizes</option>
                <option value="small">Small</option>
                <option value="medium">Medium</option>
                <option value="large">Large</option>
            </select>
            <label for="price">Price:</label>
            <select id="price">
                <option value="all">All Prices</option>
                <option value="low">Low to High</option>
                <option value="high">High to Low</option>
            </select>
        </div>

        <div class="product-grid">
            <div class="product">
                <img src="t-shirts.png" alt="Children T-shirt">
                <h3>Children T-shirt</h3>
                <p class="price">Rs.500</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="children-shorts.png" alt="Children Shorts">
                <h3>Children Shorts</h3>
                <p class="price">Rs.1800</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="shoes.png" alt="Children Shoes">
                <h3>Children Shoes</h3>
                <p class="price">Rs.550</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
</body>
</html>

Now i Will share css code


/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 20px 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin: 0 10px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

h2 {
    text-align: center;
    margin-top: 20px;
}

.category {
    margin: 40px 0;
    padding: 20px;
    background-color: white;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.filters {
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
}

.filters select {
    padding: 8px;
    font-size: 16px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 20px;
}

.product {
    background-color: #fff;
    padding: 15px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
    border-radius: 8px;
    transition: transform 0.3s ease-in-out;
}

.product img {
    max-width: 100%;
    border-radius: 8px;
}

.product h3 {
    font-size: 18px;
    color: #333;
}

.product .price {
    font-size: 20px;
    color: #e74c3c;
    margin: 10px 0;
}

.product button {
    padding: 10px;
    font-size: 16px;
    background-color: #e74c3c;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.product:hover {
    transform: translateY(-10px);
}

.product button:hover {
    background-color: #c0392b;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
    margin-top: 40px;
}






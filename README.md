# --Appscrip-task--chandrashekar-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metta Muse</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">LOGO</div>
        <div class="header-icons">
            <span>contrast</span>
            <span>favorite</span>
            <span>bag</span>
            <span>lock</span>
            <span>ENG</span>
        </div>
        <nav>
            <ul>
                <li><a href="#">SHOP</a></li>
                <li><a href="#">SKILLS</a></li>
                <li><a href="#">STORIES</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">CONTACT US</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>DISCOVER OUR PRODUCTS</h1>
        <p>welcome to our website.</p>
    </section>

    <section class="filters">
        <div class="filter-header">
            <p>3425 Items</p>
            <button>arrowleft HIDE FILTER</button>
        </div>
        <div class="filter-options">
            <label><input type="checkbox" checked> Recommended</label>
            <label><input type="checkbox" checked> Customizable</label>
            <label><input type="checkbox" checked> Men</label>
            <label><input type="checkbox" checked> Women</label>
            <label><input type="checkbox" checked> Baby & Kids</label>
        </div>
    </section>

    <section class="products">
        <div class="product">
            <img src="file:///C:/Users/chand/Downloads/dolls.webp" alt="Dolls">
            <img src="file:///C:/Users/chand/Downloads/caps.webp" alt="caps">
            <img src="file:///C:/Users/chand/Downloads/bag.webp" alt="Bags">
            <img src="file:///C:/Users/chand/Downloads/locate.webp" alt="locates">
            <h3>kids zone</h3>
            <p>Sign in or Create an account to see pricing</p>
        </div>
        <!-- Repeat the above block for each product -->
    </section>

    <footer>
        <div class="newsletter">
            <p>Be the first to know</p>
            <form action="#">
                <input type="email" placeholder="Enter your e-mail...">
                <button type="submit">Subscribe</button>
            </form>
        </div>
        <div class="footer-links">
            <div>
                <h4>mettā muse</h4>
                <ul>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Stories</a></li>
                    <li><a href="#">Artisans</a></li>
                    <li><a href="#">Boutiques</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#">Orders & Shipping</a></li>
                    <li><a href="#">Join/Login as a Seller</a></li>
                    <li><a href="#">Payment & Pricing</a></li>
                    <li><a href="#">Return & Refunds</a></li>
                    <li><a href="#">FAQs</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-contact">
            <p>CONTACT US</p>
            <p>+44 221 133 5360</p>
            <p><a href="mailto:customercare@mettamuse.com">customercare@mettamuse.com</a></p>
        </div>
    </footer>
</body>
</html>



//css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #f8f8f8;
    border-bottom: 1px solid #ddd;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.header-icons span {
    margin: 0 10px;
    cursor: pointer;
}

nav ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

.hero {
    text-align: center;
    padding: 50px 20px;
    background-color: #f1f1f1;
}

.filters {
    padding: 20px;
    background-color: #f8f8f8;
    border-top: 1px solid #ddd;
    border-bottom: 1px solid #ddd;
}

.filter-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}

.filter-options label {
    display: block;
    margin: 5px 0;
}

.products {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

.product {
    flex: 1 1 calc(25% - 40px);
    background-color: #fff;
    padding: 10px;
    text-align: center;
    border: 1px solid #ddd;
}

.product img {
    max-width: 100%;
    height: auto;
}

.product h3 {
    margin: 10px 0;
}

.product p {
    margin: 10px 0;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.newsletter {
    flex: 1 100%;
    text-align: center;
    margin-bottom: 20px;
}

.newsletter input[type="email"] {
    padding: 10px;
    margin-right: 10px;
    border: none;
    border-radius: 5px;
}

.newsletter button {
    padding: 10px 20px;
    background-color: #007BFF;
    border: none;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

.footer-links {
    flex: 1;
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
}

.footer-links div {
    flex: 1;
}

.footer-links ul {
    list-style: none;
    padding: 0;
}

.footer-links ul li {
    margin-bottom: 10px;
}

.footer-links ul li a {
    text-decoration: none;
    color: #fff;
}

.footer-contact {
    flex: 1 100%;
    text-align: center;
}

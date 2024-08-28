# --Appscrip-task--chandrashekar-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Listing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">LOGO COMPANY</div>
        <nav>
            <ul>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Sales</a></li>
                <li><a href="#">Stores</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="filters">
            <h2>Filters</h2>
            <ul>
                <li><a href="#">Category</a></li>
                <li><a href="#">Color</a></li>
                <li><a href="#">Size</a></li>
                <li><a href="#">Price</a></li>
                <!-- Add more filter options as needed -->
            </ul>
            <button>Clear All</button>
        </section>

        <section class="product-listing">
            <h2>Discover Our Products</h2>
            <div class="products">
                <div class="product">
                    <img src="C:\Users\chand\Downloads\WhatsApp Image 2024-08-28 at 3.19.38 PM.jpeg" alt="Product 1">
                    <h3>Smart needs</h3>
                </div>
                <div class="product">
                    <img src="C:\Users\chand\Downloads\WhatsApp Image 2024-08-28 at 3.19.37 PM.jpeg" alt="Product 2">
                    <h3>CHAIRS</h3>
                </div>
                <!-- Repeat for more products -->
            </div>
        </section>
    </main>

    <footer>
        <div class="subscribe">
            <h3>Be the first to know</h3>
            <input type="email" placeholder="Enter your email">
            <button>Subscribe</button>
        </div>
        <div class="footer-links">
            <ul>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact Us</a></li>
                <li><a href="#">Terms & Conditions</a></li>
                <li><a href="#">Privacy Policy</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>



//css 

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background-color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #ddd;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 16px;
}

main {
    display: flex;
    padding: 20px;
}

.filters {
    width: 20%;
    background-color: #fff;
    padding: 20px;
    border-right: 1px solid #ddd;
}

.filters h2 {
    margin-bottom: 15px;
    font-size: 20px;
}

.filters ul {
    list-style: none;
    margin-bottom: 15px;
}

.filters ul li {
    margin-bottom: 10px;
}

.filters ul li a {
    text-decoration: none;
    color: #333;
}

.filters button {
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

.product-listing {
    width: 80%;
    padding-left: 20px;
}

.product-listing h2 {
    margin-bottom: 20px;
    font-size: 24px;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
}

.product {
    background-color: #fff;
    padding: 10px;
    border: 1px solid #ddd;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
}

.product h3 {
    margin-top: 10px;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

footer .subscribe {
    flex: 1;
}

footer .subscribe h3 {
    margin-bottom: 10px;
    font-size: 18px;
}

footer .subscribe input {
    width: 70%;
    padding: 10px;
    margin-right: 10px;
}

footer .subscribe button {
    padding: 10px;
    background-color: #555;
    color: #fff;
    border: none;
    cursor: pointer;
}

footer .footer-links {
    flex: 1;
    text-align: right;
}

footer .footer-links ul {
    list-style: none;
    display: flex;
    justify-content: flex-end;
    gap: 20px;
}

footer .footer-links ul li a {
    text-decoration: none;
    color: #fff;
}

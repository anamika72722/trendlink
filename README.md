![Screenshot 2025-04-29 130502](https://github.com/user-attachments/assets/26718e51-becc-4fe1-9af0-3baefe2f66b2)

# trendlink
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrendLink.in - Fashion For Every Generation</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #FFDEE9;
            color: #333;
        }
        header {
            background-color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        header h1 {
            color: #FF69B4;
            font-size: 1.8rem;
        }
        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .banner {
            background-image: url('https://images.unsplash.com/photo-1521335629791-ce4aec67ddaf');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
        }
        .categories, .search-section, .trending-section {
            padding: 2rem;
            text-align: center;
        }
        .categories h2, .search-section h2, .trending-section h2 {
            color: #FF69B4;
        }
        .category-list, .trending-products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 1rem;
        }
        .category-item, .product-item {
            background: white;
            border-radius: 10px;
            padding: 1rem;
            margin: 0.5rem;
            width: 150px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .category-item:hover, .product-item:hover {
            transform: scale(1.05);
            background-color: #ffe6f0;
        }
        .product-item img {
            width: 100%;
            border-radius: 8px;
        }
        .product-title {
            margin-top: 0.5rem;
            font-weight: bold;
        }
        .search-bar input {
            padding: 0.5rem;
            width: 60%;
            margin: 1rem 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .upload-buttons button {
            margin: 0.5rem;
            padding: 0.7rem 1rem;
            background-color: #FF69B4;
            border: none;
            color: white;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background: white;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
            color: #888;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<header>
    <h1>TrendLink.in</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">Categories</a>
        <a href="#">Blog</a>
        <a href="#">Deals</a>
        <a href="#">Contact</a>
    </nav>
</header>

<div class="banner">
    Discover Fashion For Every Generation
</div>

<section class="categories">
    <h2>Shop By Categories</h2>
    <div class="category-list">
        <div class="category-item">Men's Clothing</div>
        <div class="category-item">Women's Clothing</div>
        <div class="category-item">Teenage Fashion</div>
        <div class="category-item">Footwear</div>
        <div class="category-item">Old Men's Clothing</div>
        <div class="category-item">Old Women's Clothing</div>
        <div class="category-item">Hair & Haircare</div>
    </div>
</section>

<section class="search-section">
    <h2>Find Your Look</h2>
    <div class="search-bar">
        <input type="text" placeholder="Search clothes, styles, trends...">
    </div>
    <div class="upload-buttons">
        <button onclick="openCamera()">📷 Use Camera</button>
        <button onclick="openGallery()">🖼️ Upload From Gallery</button>
    </div>
</section>

<section class="trending-section">
    <h2>🔥 Trending Products</h2>
    <div class="trending-products">
        <div class="product-item">
            <img src="https://images.unsplash.com/photo-1514995669114-6081e934b693" alt="T-shirt">
            <div class="product-title">Graphic Tee</div>
        </div>
        <div class="product-item">
            <img src="https://images.unsplash.com/photo-1580502304784-c8f02d3f3b70" alt="Shoes">
            <div class="product-title">Stylish Sneakers</div>
        </div>
        <div class="product-item">
            <img src="https://images.unsplash.com/photo-1618354691228-7d7ba30cbb45" alt="Teen Jacket">
            <div class="product-title">Teen Jacket</div>
        </div>
        <div class="product-item">
            <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f" alt="Hair Clips">
            <div class="product-title">Trendy Hair Clips</div>
        </div>
    </div>
</section>

<footer>
    &copy; 2025 TrendLink.in | Fashion For Every Generation
</footer>

<script>
    function openCamera() {
        alert('Camera function coming soon! (Will open mobile camera.)');
    }
    function openGallery() {
        alert('Gallery upload coming soon! (Will open image picker.)');
    }
</script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrendLink - Shop Fashion & Style</title>
    <meta name="description" content="Buy trendy clothes, accessories, and more at TrendLink!">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header with Navigation -->
    <header>
        <div class="logo">TrendLink</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#products">Shop</a></li>
                <li><a href="#cart">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>


    <!-- Hero Banner -->
    <section class="hero">
        <h1>Welcome to TrendLink!</h1>
        <p>Your one-stop shop for trendy fashion.</p>
        <a href="#products" class="btn">Shop Now</a>
    </section>

    <!-- Product Grid -->
    <section id="products" class="product-grid">
        <h2>Featured Products</h2>
        <div class="products">
            <!-- Product 1 -->
            <div class="product">
                <img src="product1.jpg" alt="Trendy T-Shirt">
                <h3>Cool T-Shirt</h3>
                <p class="price">₹499</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            
            <!-- Product 2 -->
            <div class="product">
                <img src="product2.jpg" alt="Stylish Jeans">
                <h3>Stylish Jeans</h3>
                <p class="price">₹1299</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            
            <!-- Add more products here -->
        </div>
    </section>

    <!-- Shopping Cart (Hidden by Default) -->
    <section id="cart" class="cart">
        <h2>Your Cart</h2>
        <div class="cart-items">
            <!-- Cart items will be added dynamically via JavaScript -->
        </div>
        <div class="cart-total">
            <p>Total: ₹<span id="total-price">0</span></p>
            <button class="checkout-btn">Proceed to Checkout</button>
        </div>
    </section>

    <!-- Footer -->
    <footer>

    /* ===== Base Styles ===== */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

/* ===== Header Styles ===== */
header {
    background-color: #fff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-size: 1.8rem;
    font-weight: 700;
    color: #ff6b6b;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 1.5rem;
}

nav a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
}

nav a:hover {
    color: #ff6b6b;
}

#cart-count {
    background-color: #ff6b6b;
    color: white;
    padding: 0.2rem 0.5rem;
    border-radius: 50%;
    font-size: 0.8rem;
}

/* ===== Hero Section ===== */
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('hero-bg.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 5rem 1rem;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.btn {
    background-color: #ff6b6b;
    color: white;
    padding: 0.8rem 2rem;
    border: none;
    border-radius: 5px;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #ff5252;
}

/* ===== Product Grid ===== */
.product-grid {
    padding: 3rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.product-grid h2 {
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 2rem;
}

.product {
    background-color: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.product:hover {
    transform: translateY(-5px);
}

.product img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.product h3 {
    padding: 0 1rem;
    margin: 1rem 0 0.5rem;
}

.product .price {
    padding: 0 1rem;
    font-weight: 700;
    color: #ff6b6b;
    font-size: 1.2rem;
}

.add-to-cart {
    display: block;
    width: 100%;
    padding: 0.8rem;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s;
}

.add-to-cart:hover {
    background-color: #ff6b6b;
}

/* ===== Cart Section ===== */
.cart {
    background-color: white;
    padding: 2rem;
    margin: 2rem auto;
    max-width: 800px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    display: none; /* Hidden by default */
}

.cart h2 {
    margin-bottom: 1.5rem;
}

.cart-items {
    margin-bottom: 1.5rem;
}

.cart-total {
    text-align: right;
    font-size: 1.2rem;
    font-weight: 700;
}

.checkout-btn {
    background-color: #ff6b6b;
    color: white;
    padding: 0.8rem 2rem;
    border: none;
    border-radius: 5px;
    font-weight: 600;
    cursor: pointer;
    margin-top: 1rem;
}

/* ===== Footer ===== */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1.5rem;
    margin-top: 3rem;
}

/* ===== Responsive Design ===== */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        padding: 1rem;
    }

    nav ul {
        margin-top: 1rem;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .products {
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    }
}
        <p>&copy; 2024 TrendLink. All rights reserved.</p>
    </footer>

    <!-- JavaScript -->
    <script src="script.js"></script>
</body>
</html>
// ===== DOM Elements =====
const productGrid = document.querySelector('.product-grid');
const cartSection = document.querySelector('.cart');
const cartItemsEl = document.querySelector('.cart-items');
const cartCountEl = document.getElementById('cart-count');
const totalPriceEl = document.getElementById('total-price');
const checkoutBtn = document.querySelector('.checkout-btn');

// ===== Sample Product Data (Replace with your actual products) =====
const products = [
    { id: 1, name: 'Cool T-Shirt', price: 499, image: 'product1.jpg' },
    { id: 2, name: 'Stylish Jeans', price: 1299, image: 'product2.jpg' },
    { id: 3, name: 'Trendy Sneakers', price: 1999, image: 'product3.jpg' },
    { id: 4, name: 'Classic Watch', price: 1599, image: 'product4.jpg' }
];

// ===== Cart State =====
let cart = JSON.parse(localStorage.getItem('cart')) || [];

// ===== Render Products =====
function renderProducts() {
    productGrid.querySelector('.products').innerHTML = products.map(product => `
        <div class="product" data-id="${product.id}">
            <img src="${product.image}" alt="${product.name}">
            <h3>${product.name}</h3>
            <p class="price">₹${product.price}</p>
            <button class="add-to-cart">Add to Cart</button>
        </div>
    `).join('');
}
    

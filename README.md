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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>E-Commerce Store</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>My Online Store</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Cart (<span id="cart-count">0</span>)</a>
    </nav>
  </header>

  <main>
    <section id="product-list">
      <!-- Products will be loaded here by JS -->
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cart - My Online Store</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>My Online Store</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="cart.html">Cart</a>
    </nav>
  </header>

  <main>
    <section id="cart-items">
      <h2>Your Cart</h2>
      <p>No items in cart.</p>
      <!-- JavaScript will load cart items here -->
    </section>

    <section id="checkout">
      <button>Proceed to Checkout</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>   


    

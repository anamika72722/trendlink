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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product Details</title>
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
    <section id="product-detail">
      <h2>Product Name</h2>
      <p>Price: ₹999</p>
      <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <button>Add to Cart</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login - My Store</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>My Online Store</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="register.html">Register</a>
    </nav>
  </header>

  <main>
    <h2>Login</h2>
    <form action="#" method="post">
      <label>Email:</label><br>
      <input type="email" name="email" required><br><br>
      <label>Password:</label><br>
      <input type="password" name="password" required><br><br>
      <button type="submit">Login</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Register - My Store</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>My Online Store</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="login.html">Login</a>
    </nav>
  </header>

  <main>
    <h2>Register</h2>
    <form action="#" method="post">
      <label>Full Name:</label><br>
      <input type="text" name="fullname" required><br><br>
      <label>Email:</label><br>
      <input type="email" name="email" required><br><br>
      <label>Password:</label><br>
      <input type="password" name="password" required><br><br>
      <button type="submit">Register</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>   
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Checkout - My Store</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>Checkout</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="cart.html">Cart</a>
    </nav>
  </header>

  <main>
    <h2>Billing Information</h2>
    <form action="#" method="post">
      <label>Full Name:</label><br>
      <input type="text" name="name" required><br><br>
      <label>Address:</label><br>
      <input type="text" name="address" required><br><br>
      <label>Payment Method:</label><br>
      <select name="payment" required>
        <option value="cod">Cash on Delivery</option>
        <option value="card">Credit/Debit Card</option>
        <option value="upi">UPI</option>
      </select><br><br>
      <button type="submit">Place Order</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Admin Panel - My Store</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>Admin Dashboard</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="admin.html">Admin Panel</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Add New Product</h2>
      <form id="add-product-form">
        <label>Product Name:</label><br>
        <input type="text" id="product-name" required><br><br>
        <label>Price:</label><br>
        <input type="number" id="product-price" required><br><br>
        <label>Description:</label><br>
        <textarea id="product-description" required></textarea><br><br>
        <button type="submit">Add Product</button>
      </form>
    </section>

    <section>
      <h2>All Products</h2>
      <table>
        <thead>
          <tr>
            <th>Name</th>
            <th>Price (₹)</th>
            <th>Description</th>
            <th>Actions</th>
          </tr>
        </thead>
        <tbody id="product-table">
          <!-- Products will appear here -->
        </tbody>
      </table>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>

  <script>
    const form = document.getElementById("add-product-form");
    const table = document.getElementById("product-table");
    let adminProducts = [];

    form.addEventListener("submit", (e) => {
      e.preventDefault();
      const name = document.getElementById("product-name").value;
      const price = document.getElementById("product-price").value;
      const desc = document.getElementById("product-description").value;

      const newProduct = { name, price, desc };
      adminProducts.push(newProduct);
      renderTable();
      form.reset();
    });

    function renderTable() {
      table.innerHTML = "";
      adminProducts.forEach((product, index) => {
        table.innerHTML += `
          <tr>
            <td>${product.name}</td>
            <td>${product.price}</td>
            <td>${product.desc}</td>
            <
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Online Store</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>My Online Store</h1>
    <nav>
      <a href="#">Home</a>
      <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
      <a href="login.html">Login</a>
    </nav>
  </header>

  <main>
    <section>
      <input type="text" id="search-input" placeholder="Search products..." />
      <select id="category-filter">
        <option value="all">All Categories</option>
        <option value="clothing">Clothing</option>
        <option value="shoes">Shoes</option>
        <option value="accessories">Accessories</option>
      </select>
    </section>

    <section id="product-list">
      <!-- Product cards loaded by JS -->
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Store. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
const products = [
  { id: 1, name: "T-Shirt", price: 499, category: "clothing" },
  { id: 2, name: "Sneakers", price: 1999, category: "shoes" },
  { id: 3, name: "Jeans", price: 1299, category: "clothing" },
  { id: 4, name: "Cap", price: 299, category: "accessories" },
];

let cart = [];

function renderProducts(filtered = products) {
  const container = document.getElementById("product-list");
  container.innerHTML = "";
  filtered.forEach(product => {
    container.innerHTML += `
      <div class="product">
        <h3>${product.name}</h3>
        <p>₹${product.price}</p>
        <p>Category: ${product.category}</p>
        <button onclick="addToCart(${product.id})">Add to Cart</button>
      </div>
    `;
  });
}

function addToCart(productId) {
  cart.push(productId);
  document.getElementById("cart-count").innerText = cart.length;
}

document.getElementById("search-input").addEventListener("input", () => {
  filterAndSearch();
});

document.getElementById("category-filter").addEventListener("change", () => {
  filterAndSearch();
});

function filterAndSearch() {
  const searchText = document.getElementById("search-input").value.toLowerCase();
  const category = document.getElementById("category-filter").value;

  const filtered = products.filter(product => {
    const matchesSearch = product.name.toLowerCase().includes(searchText);
    const matchesCategory = category === "all" || product.category === category;
    return matchesSearch && matchesCategory;
  });

  renderProducts(filtered);
}

renderProducts();
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Online Store</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      color: #333;
      padding: 0 15px;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 15px 0;
      text-align: center;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      max-width: 1200px;
      margin: 20px auto;
    }

    input[type="text"], select {
      padding: 8px;
      margin: 10px 5px;
      width: 200px;
    }

    #product-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .product {
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .product h3 {
      margin-bottom: 10px;
    }

    .product button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      margin-top: 10px;
      border-radius: 5px;
    }

    .product button:hover {
      background-color: #218838;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #222;
      color: white;
      margin-top: 40px;
    }

    @media screen and (max-width: 600px) {
      #product-list {
        grid-template-columns: 1fr;
      }

      input[type="text"], select {
        width: 100%;
        margin: 10px 0;
      }
    }
  </style>
</head>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TrendLink - Add Product</title>
  <style>
    body { font-family: Arial; padding: 20px; background: #f4f4f4; }
    form { background: white; padding: 20px; max-width: 400px; margin: auto; border-radius: 10px; }
    input, textarea { width: 100%; margin-bottom: 10px; padding: 8px; }
    button { background: #000; color: white; padding: 10px; border: none; cursor: pointer; }
  </style>
</head>
<body>
  <h2>Add Product to TrendLink</h2>
  <form id="productForm">
    <input type="text" name="name" placeholder="Product Name" required />
    <input type="number" name="price" placeholder="Price (₹)" required />
    <textarea name="description" placeholder="Product Description" required></textarea>
    <input type="text" name="image" placeholder="Image URL" required />
    <button type="submit">Add Product</button>
  </form>

  <script>
    document.getElementById('productForm').addEventListener('submit', async function(e) {
      e.preventDefault();
      const form = e.target;
      const data = {
        name: form.name.value,
        price: form.price.value,
        description: form.description.value,
        image: form.image.value
      };

      const res = await fetch('/api/products', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(data)
      });

      if (res.ok) {
        alert('Product added successfully!');
        form.reset();
      } else {
        alert('Failed to add product.');
      }
    });
  </script>
</body>
</html>

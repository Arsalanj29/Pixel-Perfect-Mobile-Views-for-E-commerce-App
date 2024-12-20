# Pixel-Perfect-Mobile-Views-for-E-commerce-App
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pixel-Perfect Mobile Views</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Mobile-Main View -->
  <div id="mobile-main" class="mobile-view">
    <!-- Navigation Bar -->
    <header class="nav-bar">
      <div class="logo">E-Shop</div>
      <button class="menu-button">☰</button>
    </header>

    <!-- Search Bar -->
    <div class="search-bar">
      <input type="text" placeholder="Search products...">
    </div>

    <!-- Categories Section -->
    <div class="categories">
      <button class="category-tab active">Gadgets</button>
      <button class="category-tab">Clothes</button>
      <button class="category-tab">Accessories</button>
    </div>

    <!-- Image-based Cards -->
    <div class="image-cards">
      <div class="card trending">
        <img src="images/trending.jpg" alt="Trending Items">
        <h3>Latest Trending Items</h3>
      </div>
      <div class="card deals">
        <img src="images/deals.jpg" alt="Deals and Offers">
        <h3>Deals and Offers</h3>
      </div>
    </div>

    <!-- Recommended Items Section -->
    <div class="recommended">
      <h3>Recommended Items</h3>
      <div class="item-grid">
        <div class="item">
          <img src="images/item1.jpg" alt="Item 1">
          <p>Item 1</p>
          <span>$19.99</span>
        </div>
        <div class="item">
          <img src="images/item2.jpg" alt="Item 2">
          <p>Item 2</p>
          <span>$29.99</span>
        </div>
        <div class="item">
          <img src="images/item3.jpg" alt="Item 3">
          <p>Item 3</p>
          <span>$39.99</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Mobile-ItemList View -->
  <div id="mobile-itemlist" class="mobile-view hidden">
    <!-- Category Tabs and Filters -->
    <div class="itemlist-header">
      <div class="tabs">
        <button class="tab active">All</button>
        <button class="tab">New Arrivals</button>
        <button class="tab">Popular</button>
      </div>
      <div class="filters">
        <select class="sort-dropdown">
          <option value="price">Sort by Price</option>
          <option value="rating">Sort by Rating</option>
        </select>
        <button class="filter-button">Filter</button>
      </div>
    </div>

    <!-- Product Cards -->
    <div class="product-list">
      <div class="product-card">
        <img src="images/product1.jpg" alt="Product 1">
        <h4>Product 1</h4>
        <p>$25.99</p>
        <span>⭐⭐⭐⭐☆</span>
      </div>
      <div class="product-card">
        <img src="images/product2.jpg" alt="Product 2">
        <h4>Product 2</h4>
        <p>$45.99</p>
        <span>⭐⭐⭐⭐⭐</span>
      </div>
      <div class="product-card">
        <img src="images/product3.jpg" alt="Product 3">
        <h4>Product 3</h4>
        <p>$35.99</p>
        <span>⭐⭐⭐⭐☆</span>
      </div>
    </div>

    <!-- Pagination -->
    <div class="pagination">
      <button class="prev">Previous</button>
      <button class="next">Next</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>

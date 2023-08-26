<!DOCTYPE html>
<html lang="en">
<head>
  <!-- meta tags and styles -->
</head>
<body>
  <header>
    <!-- navigation and header content -->
  </header>
  <div class="container">
    <h2>Featured Products</h2>
    <div class="product-list">
      <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h3>Product 1</h3>
        <p>Description of Product 1.</p>
        <p class="price">$99.99</p>
        <button>Add to Cart</button>
      </div>
      <!-- More product listings go here -->
    </div>
  </div>
  <footer>
    <!-- footer content -->
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- meta tags and styles -->
</head>
<body>
  <header>
    <!-- navigation and header content -->
  </header>
  <div class="container">
    <h2>Featured Products</h2>
    <div class="product-list">
      <?php
      // Simulated product data
      $products = [
        ["name" => "Product 1", "description" => "Description of Product 1.", "price" => 99.99, "image" => "product1.jpg"],
        // Add more products here
      ];

      // Loop through products and display them
      foreach ($products as $product) {
        echo '<div class="product">';
        echo '<img src="' . $product["image"] . '" alt="' . $product["name"] . '">';
        echo '<h3>' . $product["name"] . '</h3>';
        echo '<p>' . $product["description"] . '</p>';
        echo '<p class="price">$' . number_format($product["price"], 2) . '</p>'; // Format price with 2 decimal places
        echo '<button>Add to Cart</button>';
        echo '</div>';
      }
      ?>
    </div>
  </div>
  <footer>
    <!-- footer content -->
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- meta tags and styles -->
</head>
<body>
  <header>
    <!-- navigation and header content -->
  </header>
  <div class="container">
    <h2>Featured Products</h2>
    <div class="product-list">
      <?php
      // Simulated product data
      $products = [
        ["name" => "Product 1", "description" => "Description of Product 1.", "price" => 99.99, "image" => "product1.jpg"],
        // Add more products here
      ];

      // Loop through products and display them
      foreach ($products as $product) {
        echo '<div class="product">';
        echo '<img src="' . $product["image"] . '" alt="' . $product["name"] . '">';
        echo '<h3>' . $product["name"] . '</h3>';
        echo '<p>' . $product["description"] . '</p>';
        echo '<p class="price">$' . number_format($product["price"], 2) . '</p>'; // Format price with 2 decimal places
        echo '<button>Add to Cart</button>';
        echo '</div>';
      }
      ?>
    </div>
  </div>
  <footer>
    <!-- footer content -->
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Raj-e-Store</title>
<style>
  /* Add your CSS styling here */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  header {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
  }
  .container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
  }
  /* Add more styling for product listings, user registration, etc. */
</style>
</head>
<body>
  <header>
    <h1>Welcome to Raj-e-Store</h1>
    <p>Order your favorite products now!</p>
  </header>
  <div class="container">
    <h2>Product Listings</h2>
    <!-- Add product listings here -->
  </div>
  <footer>
    <p>Contact us at: +92 313 0336726</p>
  </footer>
</body>
</html>


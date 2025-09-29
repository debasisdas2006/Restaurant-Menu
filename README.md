<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Menu</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f8f8f8;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #ff6f61;
      color: white;
      text-align: center;
      padding: 20px 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .menu-container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }

    .category {
      margin-bottom: 30px;
    }

    .category h2 {
      border-bottom: 2px solid #ff6f61;
      padding-bottom: 5px;
      color: #333;
    }

    .dish {
      display: flex;
      justify-content: space-between;
      padding: 10px 0;
      border-bottom: 1px dashed #ddd;
    }

    .dish:last-child {
      border-bottom: none;
    }

    .dish-name {
      font-weight: bold;
      color: #555;
    }

    .dish-price {
      color: #ff6f61;
      font-weight: bold;
    }

    .dish-desc {
      font-size: 0.9em;
      color: #888;
      margin-top: 3px;
    }

    @media (max-width: 600px) {
      .dish {
        flex-direction: column;
        align-items: flex-start;
      }

      .dish-price {
        margin-top: 5px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Delicious Bites Restaurant</h1>
  </header>

  <div class="menu-container">
    <!-- Starters -->
    <div class="category">
      <h2>Starters</h2>
      <div class="dish">
        <div>
          <div class="dish-name">Garlic Bread</div>
          <div class="dish-desc">Crispy bread topped with garlic and herbs.</div>
        </div>
        <div class="dish-price">$4.99</div>
      </div>
      <div class="dish">
        <div>
          <div class="dish-name">Bruschetta</div>
          <div class="dish-desc">Grilled bread with tomatoes, basil, and olive oil.</div>
        </div>
        <div class="dish-price">$5.99</div>
      </div>
    </div>

    <!-- Main Course -->
    <div class="category">
      <h2>Main Course</h2>
      <div class="dish">
        <div>
          <div class="dish-name">Grilled Chicken</div>
          <div class="dish-desc">Juicy grilled chicken served with vegetables.</div>
        </div>
        <div class="dish-price">$12.99</div>
      </div>
      <div class="dish">
        <div>
          <div class="dish-name">Pasta Alfredo</div>
          <div class="dish-desc">Creamy pasta with parmesan cheese and herbs.</div>
        </div>
        <div class="dish-price">$11.49</div>
      </div>
    </div>

    <!-- Desserts -->
    <div class="category">
      <h2>Desserts</h2>
      <div class="dish">
        <div>
          <div class="dish-name">Chocolate Cake</div>
          <div class="dish-desc">Rich and moist chocolate cake with frosting.</div>
        </div>
        <div class="dish-price">$6.50</div>
      </div>
      <div class="dish">
        <div>
          <div class="dish-name">Ice Cream Sundae</div>
          <div class="dish-desc">Vanilla ice cream topped with chocolate syrup and nuts.</div>
        </div>
        <div class="dish-price">$5.00</div>
      </div>
    </div>

    <!-- Beverages -->
    <div class="category">
      <h2>Beverages</h2>
      <div class="dish">
        <div>
          <div class="dish-name">Cappuccino</div>
          <div class="dish-desc">Hot coffee with frothy milk.</div>
        </div>
        <div class="dish-price">$3.50</div>
      </div>
      <div class="dish">
        <div>
          <div class="dish-name">Fresh Lemonade</div>
          <div class="dish-desc">Refreshing lemonade made with fresh lemons.</div>
        </div>
        <div class="dish-price">$2.99</div>
      </div>
    </div>
  </div>
</body>
</html>

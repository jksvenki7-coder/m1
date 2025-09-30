# m1<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>E-commerce Combined Page</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(90deg, red 50%, white 50%);
    color: #333;
  }
  .container {
    max-width: 900px;
    margin: 20px auto;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px #b30000;
    overflow: hidden;
  }
  header {
    background-color: red;
    color: white;
    padding: 20px;
    text-align: center;
  }
  .products {
    display: flex;
    gap: 20px;
    padding: 20px;
    justify-content: center;
  }
  .product {
    background-color: #fff0f0;
    border: 2px solid red;
    border-radius: 8px;
    padding: 15px;
    width: 45%;
    box-sizing: border-box;
    text-align: center;
  }
  .product h2 {
    color: red;
    margin-top: 0;
  }
  .product p {
    font-size: 1rem;
    margin: 10px 0 15px;
  }
  .product button {
    background-color: red;
    color: white;
    border: none;
    padding: 10px 18px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }
  .product button:hover {
    background-color: #b30000;
  }
</style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Shop Our Products</h1>
    </header>
    <div class="products">
      <div class="product" onclick="alert('Product 1 added to cart!')">
        <h2>Product 1</h2>
        <p>Fresh and organic fruits directly from the farm.</p>
        <button>Add to Cart</button>
      </div>
      <div class="product" onclick="alert('Product 2 added to cart!')">
        <h2>Product 2</h2>
        <p>High-quality dairy products for your daily needs.</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </div>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>E-commerce Combined Page</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(90deg, red 50%, white 50%);
    color: #333;
  }
  .container {
    max-width: 900px;
    margin: 20px auto;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px #b30000;
    overflow: hidden;
  }
  header {
    background-color: red;
    color: white;
    padding: 20px;
    text-align: center;
  }
  .products {
    display: flex;
    gap: 20px;
    padding: 20px;
    justify-content: center;
  }
  .product {
    background-color: #fff0f0;
    border: 2px solid red;
    border-radius: 8px;
    padding: 15px;
    width: 45%;
    box-sizing: border-box;
    text-align: center;
    cursor: pointer;
  }
  .product h2 {
    color: red;
    margin-top: 0;
  }
  .product p {
    font-size: 1rem;
    margin: 10px 0 15px;
  }
  .product button {
    background-color: red;
    color: white;
    border: none;
    padding: 10px 18px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }
  .product button:hover {
    background-color: #b30000;
  }
</style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Shop Our Products</h1>
    </header>
    <div class="products">
      <div class="product" onclick="alert('Product 1 added to cart!')">
        <h2>Product 1</h2>
        <p>Fresh and organic fruits directly from the farm.</p>
        <button>Add to Cart</button>
      </div>
      <div class="product" onclick="alert('Product 2 added to cart!')">
        <h2>Product 2</h2>
        <p>High-quality dairy products for your daily needs.</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </div>
</body>
</html>

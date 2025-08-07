Here’s a simple example of an Online Food Ordering App using HTML and CSS. This code creates a basic structure for a food app with a header, menu items, and a footer.

Code Example:
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Ordering App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
    }
    header {
      background-color: #ff6f61;
      color: white;
      padding: 15px;
      text-align: center;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .menu-item {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .menu-item img {
      width: 100%;
      border-radius: 8px;
    }
    .menu-item h3 {
      margin: 10px 0;
      font-size: 18px;
    }
    .menu-item p {
      color: #555;
      font-size: 14px;
    }
    .menu-item button {
      background-color: #ff6f61;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }
    .menu-item button:hover {
      background-color: #e65a50;
    }
    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Online Food Ordering</h1>
  </header>

<div class="menu"> <div class="menu-item"> <img src="https://via.placeholder.com/200" alt="Pizza"> <h3>Pizza</h3> <p>Delicious cheesy pizza</p> <button>Order Now</button> </div> <div class="menu-item"> <img src="https://via.placeholder.com/200" alt="Burger"> <h3>Burger</h3> <p>Juicy grilled burger</p> <button>Order Now</button> </div> <div class="menu-item"> <img src="https://via.placeholder.com/200" alt="Pasta"> <h3>Pasta</h3> <p>Italian creamy pasta</p> <button>Order Now</button> </div> </div>

<footer> <p>© 2025 Food App. All rights reserved.</p> </footer> </body> </html>

Copy code
Features:
Header: Displays the app title.
Menu Section: Showcases food items with images, descriptions, and an "Order Now" button.
Footer: Contains copyright information.

You can expand this by adding more items, integrating a backend, or making it dynamic with JavaScript! Let me know if you'd like further assistance. 😊

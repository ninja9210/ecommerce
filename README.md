
## 📘 Assignment Details  

### **Assignment 2 – Online Shopping Homepage**
A simple static homepage for an online shopping website named **ShopSmart**.  

#### 🔹 index.html
```html
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ShopSmart - Online Store</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">ShopSmart</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
      <a href="#">Cart 🛒</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to ShopSmart</h1>
    <p>Your one-stop online shop for everything!</p>
  </section>

  <section class="products">
    <h2>Featured Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Product 1">
        <h3>Product 1</h3>
        <p>$19.99</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Product 2">
        <h3>Product 2</h3>
        <p>$29.99</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Product 3">
        <h3>Product 3</h3>
        <p>$9.99</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 ShopSmart. All rights reserved.</p>
  </footer>
</body>
</html>
````

#### 🔹 style.css

```css
body {
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  margin: 0;
}

header {
  background: #333;
  color: white;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
}

.hero {
  background: #ffcc00;
  text-align: center;
  padding: 60px 20px;
}

.products {
  padding: 40px 20px;
  text-align: center;
}

.product-grid {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.product-card {
  background: white;
  width: 250px;
  padding: 15px;
  text-align: center;
}

.product-card img {
  width: 100%;
}

.product-card button {
  margin-top: 10px;
  padding: 10px;
  background: #333;
  color: white;
  border: none;
  cursor: pointer;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 15px;
}
```

---

### **Assignment 3 – Feedback Form**

#### 🔹 index.html

```html
<html>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Feedback Form - Online Shopping</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <form class="feedback-form">
    <h2>Customer Feedback</h2>
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="Your name" required />

    <label for="email">Email</label>
    <input type="email" id="email" name="email" placeholder="your.email@example.com" required />

    <label for="rating">Overall Rating</label>
    <select id="rating" name="rating" required>
      <option value="" disabled selected>Select rating</option>
      <option value="5">Excellent - 5</option>
      <option value="4">Good - 4</option>
      <option value="3">Average - 3</option>
      <option value="2">Poor - 2</option>
      <option value="1">Very Poor - 1</option>
    </select>

    <label for="comments">Comments</label>
    <textarea id="comments" name="comments" placeholder="Write your feedback here..."></textarea>

    <button type="submit">Submit Feedback</button>
    <p class="note">Thank you for helping us improve!</p>
  </form>
</body>
</html>
```

#### 🔹 style.css

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f7f7f7;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.feedback-form {
  background: white;
  padding: 20px 30px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  width: 350px;
}

.feedback-form h2 {
  margin-bottom: 20px;
  color: #333;
  text-align: center;
}

label {
  display: block;
  margin-bottom: 6px;
  font-weight: bold;
  color: #555;
}

input[type="text"],
input[type="email"],
select,
textarea {
  width: 100%;
  padding: 8px 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 14px;
}

textarea {
  height: 80px;
}

button {
  background-color: #28a745;
  color: white;
  border: none;
  padding: 12px;
  width: 100%;
  border-radius: 4px;
  font-size: 16px;
  cursor: pointer;
}

button:hover {
  background-color: #218838;
}

.note {
  font-size: 12px;
  color: #888;
  text-align: center;
  margin-top: 10px;
}
```

---

### **Assignment 4 – Product Catalog**

#### 🔹 index.html

```html
<html>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Product Catalog - Online Shopping</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Online Shopping Catalog</h1>
  </header>

  <main class="product-grid">
    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 1" />
      <h3>Product Name 1</h3>
      <p>$19.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 2" />
      <h3>Product Name 2</h3>
      <p>$29.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 3" />
      <h3>Product Name 3</h3>
      <p>$15.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 4" />
      <h3>Product Name 4</h3>
      <p>$49.99</p>
      <button>Add to Cart</button>
    </div>
  </main>
</body>
</html>
```

#### 🔹 style.css

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
  background: #f4f4f4;
}

header {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 15px;
}

.product-grid {
  display: grid;
  grid-gap: 20px;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.product-card {
  background: #fff;
  padding: 10px;
  text-align: center;
  box-shadow: 0 0 5px #ccc;
  border-radius: 5px;
}

.product-card img {
  max-width: 100%;
  border-radius: 4px;
}

button {
  background: #28a745;
  color: white;
  border: none;
  padding: 8px;
  cursor: pointer;
  border-radius: 4px;
}

button:hover {
  background: #218838;
}
```

---

## 🚀 How to Run

1. Clone or download the project files.
2. Open any `index.html` file in your browser.
3. Ensure `style.css` is in the same directory for proper styling.

---

```
```


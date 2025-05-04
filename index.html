<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>ЭкоМаркет – экологически чистые продукты</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f9f4;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    .container {
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }
    .product {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product button {
      margin-top: 10px;
      padding: 8px 12px;
      background-color: #66bb6a;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .cart {
      position: fixed;
      top: 80px;
      right: 20px;
      width: 300px;
      background-color: #fff;
      border: 1px solid #ccc;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      max-height: 70vh;
      overflow-y: auto;
    }
    form input, form textarea {
      width: 100%;
      margin-top: 8px;
      margin-bottom: 10px;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #2e7d32;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      width: 100%;
      cursor: pointer;
    }
    footer {
      background: #eee;
      padding: 20px;
      text-align: center;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <div><strong>🌿 ЭкоМаркет</strong></div>
  <nav>
    <a href="#home">Главная</a>
    <a href="#products">Товары</a>
    <a href="#contacts">Контакты</a>
  </nav>
</header>

<div class="container">
  <h2 id="products">Наши товары</h2>
  <div class="products">
    <div class="product">
      <h3>Органические яблоки</h3>
      <p>500 руб / кг</p>
      <button onclick="addToCart('Органические яблоки')">В корзину</button>
    </div>
    <div class="product">
      <h3>Молоко фермерское</h3>
      <p>150 руб / литр</p>
      <button onclick="addToCart('Молоко фермерское')">В корзину</button>
    </div>
    <div class="product">
      <h3>Хлеб цельнозерновой</h3>
      <p>120 руб</p>
      <button onclick="addToCart('Хлеб цельнозерновой')">В корзину</button>
    </div>
  </div>
</div>

<div class="cart" id="cart">
  <h3>🛒 Корзина</h3>
  <ul id="cart-items">
    <li>Корзина пуста</li>
  </ul>
  <form id="order-form" onsubmit="submitOrder(event)">
    <h4>Оформить заказ</h4>
    <input type="text" id="name" placeholder="Ваше имя" required>
    <input type="tel" id="phone" placeholder="Телефон" required>
    <textarea id="address" placeholder="Адрес доставки" rows="3" required></textarea>
    <button type="submit">Оформить</button>
  </form>
</div>

<footer id="contacts">
  <p>📧 info@ecomarket.ru | 📞 +7 (999) 123-45-67</p>
</footer>

<script>
  let cartItems = [];

  function saveCart() {
    localStorage.setItem('cartItems', JSON.stringify(cartItems));
  }

  function loadCart() {
    const saved = localStorage.getItem('cartItems');
    if (saved) {
      cartItems = JSON.parse(saved);
      updateCartDisplay();
    }
  }

  function updateCartDisplay() {
    const list = document.getElementById('cart-items');
    list.innerHTML = '';
    if (cartItems.length === 0) {
      list.innerHTML = '<li>Корзина пуста</li>';
    } else {
      cartItems.forEach(item => {
        const li = document.createElement('li');
        li.textContent = item;
        list.appendChild(li);
      });
    }
  }

  function addToCart(productName) {
    cartItems.push(productName);
    saveCart();
    updateCartDisplay();
  }

  function submitOrder(event) {
    event.preventDefault();
    const name = document.getElementById('name').value.trim();
    const phone = document.getElementById('phone').value.trim();
    const address = document.getElementById('address').value.trim();

    if (cartItems.length === 0) {
      alert("Ваша корзина пуста.");
      return;
    }

    const orderDetails = `
Заказ от: ${name}
Телефон: ${phone}
Адрес: ${address}
Товары: ${cartItems.join(', ')}
    `;

    alert("Ваш заказ оформлен!\n\n" + orderDetails);

    cartItems = [];
    saveCart();
    updateCartDisplay();
    document.getElementById('order-form').reset();
  }

  window.onload = loadCart;
</script>

</body>
</html>

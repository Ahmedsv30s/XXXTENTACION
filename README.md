<!DOCTYPE html><html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TENTACION - متجر إلكتروني</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      direction: rtl;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 2px;
    }
    nav {
      background-color: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 15px;
      text-align: center;
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.02);
    }
    .product img {
      max-width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      color: #28a745;
      font-weight: bold;
    }
    .product button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 10px;
    }
    .product button:hover {
      background-color: #0056b3;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    .admin-link {
      display: block;
      text-align: center;
      margin: 20px 0;
    }
    .admin-link a {
      color: #007bff;
      font-weight: bold;
      text-decoration: none;
    }
    .admin-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>TENTACION - متجر إلكتروني</h1>
  </header>  <nav>
    <a href="#">الرئيسية</a>
    <a href="admin.html">لوحة التحكم</a>
    <a href="#">اتصل بنا</a>
  </nav>  <main class="container">
    <div class="product">
      <img src="https://via.placeholder.com/250x200" alt="منتج 1">
      <h3>تيشيرت أسود</h3>
      <p>100 ريال</p>
      <button>أضف إلى السلة</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200" alt="منتج 2">
      <h3>قبعة TENTACION</h3>
      <p>80 ريال</p>
      <button>أضف إلى السلة</button>
    </div>
    <!-- يمكن إضافة المزيد من المنتجات هنا -->
  </main>  <div class="admin-link">
    <a href="admin.html">صفحة الإدارة الخاصة بك</a>
  </div>  <footer>
    <p>جميع الحقوق محفوظة &copy; TENTACION 2025</p>
  </footer>
</body>
</html># XXXTENTACION
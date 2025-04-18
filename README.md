- 👋 Hi, I’m @tshirtmood
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
tshirtmood/tshirtmood is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TshirtMood Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #111;
      color: #fff;
      padding: 20px;
      font-size: 28px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }
    .item {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin: 15px;
      width: 200px;
      padding: 10px;
      transition: 0.3s;
    }
    .item:hover {
      transform: scale(1.05);
    }
    .item img {
      width: 100%;
      border-radius: 8px;
    }
    .item a {
      display: inline-block;
      margin-top: 10px;
      color: #007bff;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>TshirtMood Store</header>

  <div class="gallery">
    <div class="item">
      <img src="design1.jpg" alt="T-shirt Design 1">
      <a href="https://yourshoplink.com/design1" target="_blank">Buy Now</a>
    </div>
    <div class="item">
      <img src="design2.jpg" alt="T-shirt Design 2">
      <a href="https://yourshoplink.com/design2" target="_blank">Buy Now</a>
    </div>
    <!-- तिमी यस्तै गरेर अरु item थप्न सक्छौ -->
  </div>

</body>
</html>

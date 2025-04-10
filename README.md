<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kartvizit</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: #f4f4f4;
    }

    .card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      text-align: center;
      max-width: 300px;
    }

    .card h1 {
      margin: 0;
      font-size: 24px;
      color: #333;
    }

    .card p {
      margin: 5px 0;
      color: #666;
    }

    .card .socials a {
      margin: 0 10px;
      color: #0077b5;
      text-decoration: none;
    }

    .card .socials a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Adınız Soyadınız</h1>
    <p>Unvanınız</p>
    <p><a href="mailto:email@example.com">email@example.com</a></p>
    <p><a href="tel:+1234567890">+12 345 678 90</a></p>
    <div class="socials">
      <a href="https://github.com/kullaniciadi" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/kullaniciadi" target="_blank">LinkedIn</a>
    </div>
  </div>
</body>
</html>

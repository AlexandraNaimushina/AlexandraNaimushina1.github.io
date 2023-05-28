<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="main-style.css">
  <link rel="stylesheet" href="style.css">
  <title>Интернет-магазин «Китайский БИТ»</title>
</head>
<body>
<div class="container">
<header class="page-header">
  <h1 class="title"><span class="accent">Интернет-магазин</span> <br>«Китайский БИТ»</h1>
  <div class="logo">
    <img src="logo.png" width="150" />
  </div>
</header>
<main class="page-main">
  <ol class="products-list">
    <li class="product product-1">
      <h2>Камера</h2>
      <p>Камера интернет (960-001106) Logitech Webcam BRIO</p>
    </li>
    <li class="product product-2">
      <h2>Ноутбук</h2>
      <p>Ноутбук HP 840 G8 6A3P2AV 14</p>
    </li>
    <li class="product product-3">
      <h2>МФУ</h2>
      <p>Лазерное МФУ HP Color LaserJet Pro MFP M479fdn W1A79A</p>
    </li>
    <li class="product product-4">
      <h2>Принтер</h2>
      <p>Принтер HP Color Laser 150a <4ZB94A> A4</p>
    </li>
  </ol>
</main>
<footer class="page-footer">
  © 2020 — что есть, тем и торгуем
</footer>
</div>

</body>
</html>



.body{
    margin:0;
    }

.products-list{
    display: grid;
    grid-template-columns:1fr 1fr;
    margin:0;
    padding: 20px;
    padding-top: 25px;
    padding-bottom: 40px;
    row-gap: 30px;
    column-gap: 20px;
}


.page-header{
	padding: 20px;
    padding-top:30px;
    padding-bottom:70px ;
	display: grid;
	grid-template-columns:1fr 160px;
	
}
.page-footer{
    padding: 20px;
    padding-top: 10px;
}

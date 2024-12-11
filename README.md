<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>El Chispa Loca</title>
<style>

*{
box-sizing:border-box;
}

body {
font-family: Arial, sans-serif;
padding: 10px;
background-color: #ffffff; 
}


.header {
background-color: #2c3e50; 
color: #ffffff;
padding: 20px;
text-align: center;
}

.header h1{
display: flex;
justify-content: center;
align-items: center;
font-size:45px;
}

header h1 img {
margin-right: 10px;
width: 100px;
height: auto;
}

nav {
background-color: #f4b047; 
padding: 10px;
text-align: center;
}

nav a {
color: #2c3e50; 
text-decoration: none;
padding: 10px;
margin: 5px;
}
nav a:hover {
background-color: #f68d36; 
}


.dropdown {
 position: relative;
 display: inline-block;
}
.dropdown-header {
cursor: pointer;
padding: 10px;
color: #2c3e50;
}
.dropdown-content {
display: none;
position: absolute;
background-color: #f4b047;
min-width: 200px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
left: 0;
top: 100%;
text-align: left;
}

.dropdown-content img {
    margin-right: 8px; 
}

.dropdown:hover .dropdown-content {
display: block;
}
.dropdown-content a {
color: #2c3e50;
padding: 12px 16px;
text-decoration: none;
display: block;
width: 100%;
text-align: left;
}
.dropdown-content a:hover {
background-color: #f68d36;
}

 .content-center {
 float: left;
 width: 80%;
 padding: 20px;
 }

.product {
padding: 10px;
margin: 10px;
text-align: center; 
background-color: white; 
width: 150px; 
display: inline-block;
}

.product img {
max-width: 100%; 
height: auto; 
}

.product button {
background-color: #2c3e50; 
color: white; 
border: none; 
padding: 10px 15px; 
cursor: pointer;
border-radius: 5px; 
}

.product button:hover {
background-color: #f68d36; 
}

.content-right {
float: right;
width: 20%;
background-color: #f2f2f2; 
padding: 20px;
}

.content-right img {
width: 100%; 
height: auto; 
display: block;
}

footer { 
clear:both;
padding:10px;
text-align:center;
background:#2c3e50;
color: #ffffff;

}
@media screem and(max-width:800px){
.rightcolum{
widht:100%;
padding:0;
}
}
/*Responsive layout-when the screen is less than 400px wide, make the navigation links stack on the top of each other instead of next to each other*/
@media screem and(max-width:400px){
.nav a{
float:none;
width:100%;
}
}

</style>
</head>
<body>
<div class="header">
<h1><img src="Img/logochispa.png" alt="Icono de Tienda de Electrónica" width="100" height="100">El Chispa Loca</h1>
</div>

<nav>
<a href="#">Inicio</a>
<a href="Acercade.html">Acerca de</a>
<a href="Contacto.html">Contacto</a>
<div class="dropdown">
<span class="dropdown-header">Productos ▼</span>
<div class="dropdown-content">
<a href="Celulares.html"><img src="Img/movil.png" alt="Movil" style="width: 16px; height: 16px;">Smartphones</a>
<a href="Laptos.html"><img src="Img/ordenador.png" alt="Laptop" style="width: 16px; height: 16px;">Laptops</a>
<a href="Accesorios.html"><img src="Img/raton.png" alt="Raton" style="width: 16px; height: 16px;">Accesorios</a>
<a href="AudioyVideo.html"><img src="Img/auriculares.png" alt="Audio" style="width: 16px; height: 16px;">Audio y Video</a>
<a href="Hogar.html"><img src="Img/hogar.png" alt="Hogar" style="width: 16px; height: 16px;">Hogar</a>
</div>

</nav>

<div class="content-center">
<h2>LO MÁS VENDIDO</h2>
<div class="product">
<img src="Img/Audifonos.png" alt="Audifono 1" width="180" height="180">
<h3>Audifonos</h3>
<p>Precio: $800.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/lap.png" alt="Lap 2" width="150" height="150">
<h3>Laptop HP</h3>
<p>Precio: $5,000.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/alexa.png" alt="Alexa" width="150" height="150">
<h3>Alexa</h3>
<p>Precio: $1000.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/reloj.png" alt="Reloj" width="90" height="90">
<h3>Reloj Inteligente</h3>
<p>Precio: $700.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/tablet.png" alt="Tablet" width="150" height="150">
<h3>iPad</h3>
<p>Precio: $9,000.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/audisony.png" alt="Sony" width="100" height="100">
<h3>Audifonos Inalambricos Sony</h3>
<p>Precio: $400.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/samsungcel.png" alt="Cel" width="100" height="100">
<h3>Samsung S23 Ultra</h3>
<p>Precio: $9,000.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/cargador.png" alt="Cargador" width="150" height="150">
<h3>Cargador Portatil</h3>
<p>Precio: $750.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/iPhone.png" alt="Iphone" width="150" height="150">
<h3>Iphone 13 3</h3>
<p>Precio: $10,000.00</p>
<button>Comprar</button>
</div>
<div class="product">
<img src="Img/lap2.png" alt="Lap2" width="150" height="150">
<h3>Laptop HP</h3>
<p>Precio: $13000.00</p>
<button>Comprar</button>
</div>

</div>

<div class="content-right">
<h2>Ofertas de Temporada</h2>
<div class="card">
<img src="Img/ofertas.png" alt="Ofertas de Temporada" style="width: 100%; height: auto;">

</div>

</div>
</div>

<footer>
<p>&copy; 2024 EL CHISPA LOCA, S.A. DE C.V. TODOS LOS DERECHOS RESERVADOS.</p>
</footer>
</body>
</html>

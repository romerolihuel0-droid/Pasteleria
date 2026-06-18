# Pasteleria
Pasteleria
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dulce Tentación</title>
<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#fff8f0;
}
header{
    background:#ffb6c1;
    color:white;
    text-align:center;
    padding:30px;
}
nav{
    background:#ff8fab;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}
section{
    padding:20px;
}
.productos{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
}
.card{
    background:white;
    border-radius:10px;
    padding:15px;
    width:220px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}
button{
    background:#ff8fab;
    color:white;
    border:none;
    padding:10px;
    border-radius:5px;
    cursor:pointer;
}
footer{
    background:#ffb6c1;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}
</style>
</head>
<body>

<header>
    <h1>Dulce Tentación</h1>
    <p>Tortas, cupcakes y postres artesanales</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
    <h2>Bienvenidos</h2>
    <p>Las mejores delicias para tus eventos y momentos especiales.</p>
</section>

<section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
        <div class="card">
            <h3>Torta de Chocolate</h3>
            <p>$15.000</p>
            <button>Comprar</button>
        </div>

        <div class="card">
            <h3>Cupcakes</h3>
            <p>$8.000</p>
            <button>Comprar</button>
        </div>

        <div class="card">
            <h3>Cheesecake</h3>
            <p>$12.000</p>
            <button>Comprar</button>
        </div>
    </div>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>WhatsApp: +54 11 1234-5678</p>
    <p>Email: contacto@dulcetentacion.com</p>
</section>

<footer>
    © 2026 Dulce Tentación - Todos los derechos reservados.
</footer>

</body>
</html>

# proyectfinal
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap-theme.min.css">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>
<link rel="stylesheet" type="text/css" href="style.css">
<link rel="stylesheet" type="text/css" href="footer.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
<link href="https://fonts.cdnfonts.com/css/d3-craftism" rel="stylesheet">
	<title>Inicio</title>
</head>
<style>
    body{
	background-image: linear-gradient(to right, rgb(0, 0, 0),rgb(0, 0, 0));
}
</style>
<body>
    <div style="margin: 24px;">
		<nav class="navbar navbar-light" style="background-color: rgb(3, 3, 32);">
			<div class="container">
				<ul class="nav navbar-nav">
					<li class="active"> 
					<a href="index.html">-Inicio</a>
					</li>
					<li> 
					<a href="menu.html">-Menu</a>
					</li>
					<li>
					<a href="formulario.html">-Formulario</a>
					</li>
					<li>
					<a href="resultado.html">-Resultado</a>
					</li>
					<li>
					<a href="contacto.html">-Contacto</a>
					</li>
                    <li>
                    <a href="apimovie.html">-Peliculas</a>
                    </li>
                    <li>
                    <a href="calculadorafisica.html">-Fisica</a>
                    </li>
                    <li>
                    <a href="calculadora.html">-Calculadora</a>
                    </li>
				    <li>
					<a href="perfil.html">-Perfil</a>
				    </li>
				    <li>
					<a href="cuestionario.html">-Cuestionario</a>
				    </li>
                </ul>
			</div>
		</nav>
	</div>
        <!-- <div style="position: relative; background-color: rgb(255, 255, 255); color: grey;"> -->
            <div style="position: relative;">
            <video autoplay muted preload loop>
                <source src="index.mp4.mp4" type="video/mp4">
            </video>
            <h1 class="titulo">BIENVENIDOSS</h1>
        </div>
    <!--<h1>Bienvenidos a mi Pagina</h1>
    <h1>Julissa Perez Aguilar</h1>
-->
    <footer>
        <div class="containerf">
            <div class="footer-content">
                <div class="footer-section about">

            </div>
        </div>
    </footer>
    <!--con esto lo siguiente, hace que los links de la pag se habran mediante JS en una pag nueva-->
    <script>
        const socialnetworks = document.querySelectorAll('.contact-links a');
        socialnetworks.forEach(link =>{
          link.addEventListener('click',e=>{
           e.preventDefault();
           window.open(link.href, '_blank');
        });
      });
    </script>
</body>
</html>

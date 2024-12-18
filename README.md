<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Servicios de Cortadora de Pasto</title>
    <link rel="stylesheet" href="t.css">
</head>
<body>
    <!-- Header (Encabezado) -->
    <header>
 <title>Servicios de Cortadora de Pasto</title>
        <div class="logo">
            <img src="pe.png" alt="edaste cortes"width="300" height="200">
        </div>
        <nav>
            <ul>
                   <li><a href="#quienes-somos">¿Quiénes somos?</a></li>
                <li><a href="#nuestros-servicios">Nuestros Servicios</a></li>
                    <li><a href="#¿con que cortamos tus pasto?">¿con que cortamos tus pasto?</a></li>
                <li><a href="#ubicacion">Ubicación</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sección: ¿Quiénes somos? -->
    <section id="quienes-somos">
        <h1>¿Quiénes somos?</h1>
        <p>Somos una empresa especializada en el corte de pasto para jardines, áreas verdes y terrenos. Nos destacamos por ofrecer un servicio de calidad, rápido y a buen precio, utilizando equipos de última tecnología.</p>
<style>
    /* Asegura que la imagen ocupe todo el ancho */
    img {
      width: 100%; /* La imagen se ajusta al 100% del ancho de la página */
      height:180 ; /* Mantiene la proporción original de la imagen */
      display: block; /* Elimina espacios adicionales si la imagen está en línea */
    }

    body {
      margin: 0; /* Elimina el margen predeterminado del navegador */
    }
  </style>
</head>
<body>
  <img src="Presentación.png" alt="Descripción de la imagen">
</body>  

 </section>

    <!-- Sección: Nuestros Servicios -->
    <section id="nuestros-servicios">
        <h2>Nuestros Servicios</h2>
        <div class="servicios">
            <div class="servicio">
                <img src="pt1.jpg" alt="Corte de pasto residencial">
                <h3>Corte de Pasto Residencial</h3>
                <p>Ofrecemos un servicio de corte de pasto para jardines residenciales, asegurando un acabado limpio y profesional.</p>
            </div>
            <div class="servicio">
                <img src="pasto3.jpg" alt="Corte de pasto comercial">
                <h3>Corte de Pasto Comercial</h3>
                <p>Corte de áreas verdes comerciales, ideal para mantener tu negocio con una excelente imagen.</p>
            </div>
            <div class="servicio">
                <img src="pasto4.jpg" alt="Mantenimiento de áreas verdes">
                <h3>Mantenimiento de Áreas Verdes</h3>
                <p>Realizamos mantenimiento continuo de jardines y áreas verdes para garantizar que siempre se vean bien.</p>
            </div>
        </div>
 </section>
     <!-- Sección: Nuestros Servicios -->
    <section id="nuestros-servicios">
        <h2>Nuestros Servicios</h2>
        <div class="servicios">
            <div class="servicio">
            
                <img src="16.png" alt="Corte de pasto residencial">
                <h3>FS 160</h3>
             <p>Potente desbrozadora para trabajar en grandes superficies de hierba dura.
            </div>
            <div class="servicio">
                <img src="5.png" alt="Corte de pasto comercial">
                <h3>FS 55%%</h3>
               <p>permite cortar grandes superficies de manera eficiente.</p>
            </div>
            <div class="servicio">
                <img src="china.png" alt="Mantenimiento de áreas verdes">
                <h3>issei 52</h3>
                <p> DESMALEZADORA ISSEI CON BARRAL DESMONTABLE MODELO IS-BC52OT</p>
            </div>
        </div>
 </section>


   
    <!-- Sección: Ubicación -->
    <section id="ubicacion">
        <h2>¿Dónde estamos?</h2>
 <div class="servicios">
            <div class="servicio">
                <img src="n.png" alt="Corte de pasto residencial">
                <h3>GRAL: RODRIGUEZ</h3>
             <p> </p>
            </div>
            <div class="servicio">
                <img src="ubi.jpg" alt="Corte de pasto comercial">
                <h3>MORENO</h3>
               <p> </p>
            </div>
            
        </div>
    </section>

    <!-- Sección: Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Si tienes alguna pregunta o necesitas solicitar nuestros servicios, puedes contactarnos a través de:</p>
        <ul>
            <li>Teléfono: +54 9 11 5262-3224</li>
            <li>Email: cortes.hot.mail</li>
            <li>Redes sociales: edaste.ar</li>
        </ul>
    </section>

    <!-- Footer (Pie de página) -->
    <footer>
        <p>&copy;  edaste a full siempre.</p>
    </footer>
</body>
</html>


/* Reset de estilos básicos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif; /* Tipografía principal */
    line-height: 1.6;
    background-color: #f0f9f4; /* Color de fondo suave */
    color: #333;
}

/* Estilos de Header */
header {
    background: linear-gradient(135deg, #4CAF50, #8BC34A); /* Fondo degradado verde */
    color: white;
    padding: 20px 0;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

header .logo img {
    width: 150px;
    height: auto;
    margin-bottom: 10px;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline-block;
    margin: 0 20px;
}

header nav ul li a {
    color: white;
    font-size: 18px;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}

header nav ul li a:hover {
    color: #FFEB3B; /* Color de hover amarillo */
}

/* Sección: ¿Quiénes somos? */
#quienes-somos {
    background-color: #ffffff;
    text-align: center;
    padding: 40px 20px;
    margin-top: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

#quienes-somos h1 {
    font-size: 36px;
    color: #4CAF50;
    margin-bottom: 20px;
}

#quienes-somos p {
    font-size: 18px;
    color: #555;
    line-height: 1.8;
    max-width: 800px;
    margin: 0 auto;
}

/* Sección: Nuestros Servicios */
#nuestros-servicios {
    padding: 40px 20px;
    background: #f9f9f9;
    text-align: center;
}

#nuestros-servicios h2 {
    font-size: 32px;
    color: #4CAF50;
    margin-bottom: 20px;
}

.servicios {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 30px;
}

.servicio {
    width: 30%;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.servicio:hover {
    transform: translateY(-10px);
}

.servicio img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 15px;
}

.servicio h3 {
    font-size: 24px;
    color: #4CAF50;
    margin-bottom: 10px;
}

.servicio p {
    font-size: 16px;
    color: #777;
    line-height: 1.6;
}

/* Sección: ¿con que cortamos tus pasto? */
#¿con que cortamos tus pasto? {
    padding: 40px 20px;
    background: #f9f9f9;
    text-align: center;
}

#¿con que cortamos tus pasto? h2 {
    font-size: 32px;
    color: #4CAF50;
    margin-bottom: 20px;
}

.maquinas {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 30px;
}

.maquina { /* Cambiar de ".maquinas" a ".maquina" (igual que ".servicio") */
    width: 0%; /* Igual que .servicio */
    background-color: #ffffff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.maquina:hover {
    transform: translateY(-10px);
}

.maquina img { /* Asegúrate de usar esta clase para las imágenes */
    width: 45%; /* Cambiado a 100% para que coincida con .servicio img */
    height: auto;
    border-radius: 8px;
    margin-bottom: 15px;
}

.maquina h2 {
    font-size: 24px;
    color: #4CAF50;
    margin-bottom: 10px;
}

.maquina p {
    font-size: 16px;
    color: #777;
    line-height: 1.6;
}

#ubicacion p {
    font-size: 18px;
    color: #555;
    max-width: 800px;
    margin: 0 auto;
    line-height: 1.8;
}

#ubicacion img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    margin-top: 20px;
}

/* Sección: Contacto */
#contacto {
    padding: 40px 20px;
    text-align: center;
    background: #f9f9f9;
    margin-top: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

#contacto h2 {
    font-size: 32px;
    color: #4CAF50;
    margin-bottom: 20px;
}

#contacto p {
    font-size: 18px;
    color: #555;
    margin-bottom: 20px;
}

#contacto ul {
    list-style-type: none;
}

#contacto ul li {
    font-size: 18px;
    color: #777;
    margin-bottom: 10px;
}

/* Estilos de Footer */
footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer p {
    font-size: 16px;
    color: #fff;
}

/* Estilos Responsivos */
@media (max-width: 768px) {
    .servicios {
        flex-direction: column;
        align-items: center;
    }

    .servicio {
        width: 80%;
        margin-bottom: 20px;
    }

    header nav ul li {
        margin: 0 10px;
    }
}


<!DOCTYPE html>
<html lang="es">
<head>
    <meta http-equiv="Content-Type' content='text/html; charset=iso-8859-1'>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instituto Nacional de Educación Básica y Diversificado Sergio Leonel Celis Navas J.V </title>
    <style>
        body {
            font-family: Arial Unicode MS, Arial;
            margin: 0;
            padding: 0;
        }

        /* Estilos para el header y el menú */
        header {
            background-color: #003;
            padding: 10px;
            color: Yellow;
            text-align: center;
        }

        nav {
            background-color: #051094;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color:yellow;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            background-color: #999;
        }

        .container {
            padding: 20px;
        }

        /* Estilos para la galería */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .form-section {
            margin-bottom: 30px;
        }

        /* Sección de comentarios */
        .comments-section {
            margin-top: 50px;
        }

        .comment {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: #003;
            color: Yellow;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Estilos para el menú desplegable en pantallas pequeñas */
        @media screen and (max-width: 600px) {
            nav a {
                float: none;
                display: block;
                text-align: left;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Instituto Nacional de Educación</h1>
         <h1>Básica y Diversificado</h1>
          <h1>"Sergio Leonel Celis Navas" J.V</h1>
    </header>

    <!-- Barra de navegación -->
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre nosotros">Sobre nosotros</a>
        <a href="#galería">Galería</a>
        <a href="#publicar">Publicar</a>
        <a href="#comentarios">Comentarios</a>
        <a href="#Contacto">Contacto</a>
    </nav>

    <!-- Contenido principal -->
    <div class="container">

        <!-- Sección Inicio -->
        <section id="inicio">
            <h2>Inicio</h2>
            <p>"Bienvenidos al Instituto Nacional de Educación Básica Y diversificado "Sergio Leonel Celis Navas" J.V Sumpango Sacatepéquez Guatemala, un espacio donde la educación, la creatividad y la tecnología se encuentran. Explora nuestro contenido, comparte tus ideas y se parte de nuestra comunidad."</p>
        </section>
 
       
        <!-- Sección Sobre nosotros -->
        <section id="Sobre nosotros">  
            <h2>sobre nosotros</h2>
            <li>Misión: Somos una institución educativa que brinda un servicio educativo eficiente y efectivo en la comunidad de Sumpango Sacatepéquez y zonas aledañas utilizando de acuerdo a la coyuntura y las circunstancia el mejor equipo humano la más actualizada tecnología educativa e instalaciones adecuadas para lograr una sana educación para los jóvenes que se nos confían.</li>
            <li>Visión: Constituir como un aliado eficiente de la comunidad de Sumpango Sacatepéquez y zonas aledañas a cuanto prestarles un servicio integral para su hijo que abarquen educación intelectual y académica haciendo uso de la razón. Educación emocional para la dimensión psicológica del alumno haciendo uso del amor.</li>     
            <h2>Niveles que ofrecemos</h2>
             <p>Nivel básico</p>
              <li>Primero básico</li>
              <li>Segundo básico</li> 
              <li>tercero básico</li>
            <p>Nivel diversificado con carreras de:</p>
              <li>Perito contador</li>
              <li>Bachillerato en ciencias y letras con orientación en computación</li>   
        </section>


        <!-- Galería de imágenes y videos -->
        <section id="galeria">
            <h2>Galería</h2>
            <div class="gallery">
                <img src="https://via.placeholder.com/200" alt="Imagen 1">
                <img src="https://via.placeholder.com/200" alt="Imagen 2">
                <img src="https://via.placeholder.com/200" alt="Imagen 3">
                <video width="100%" controls>
                    <source src="movie.mp4" type="video/mp4">
                    Tu navegador no soporta el video.
                </video>
            </div>
        </section>

        <!-- Formulario para Publicar Información -->
        <section id="publicar" class="form-section">
            <h2>Publicar Información</h2>
            <form>
                <label for="title">Título:</label>
                <input type="text" id="title" name="title"><br><br>

                <label for="content">Contenido:</label><br>
                <textarea id="content" name="content" rows="5" cols="40"></textarea><br><br>

                <label for="image">Subir Imagen:</label>
                <input type="file" id="image" name="image" accept="image/*"><br><br>

                <label for="video">Subir Video:</label>
                <input type="file" id="video" name="video" accept="video/*"><br><br>

                <label for="musica">Subir música:</label>
                <input type="file" id="música" name="música" accept="música/*"><br><br>


                <input type="submit" value="Publicar">
            </form>
        </section>

        <!-- Sección de comentarios -->
        <section id="comentarios" class="comments-section">
            <h2>Comentarios</h2>
            <div class="comment">
                <p><strong>Usuario 1:</strong> Este es un comentario de ejemplo.</p>
            </div>
            <div class="comment">
                <p><strong>Usuario 2:</strong> ¡Qué buena publicación!</p>
            </div>

            <!-- Formulario para enviar un comentario -->
            <form>
                <label for="comment">Escribe un comentario:</label><br>
                <textarea id="comment" name="comment" rows="3" cols="40"></textarea><br><br>
                <input type="submit" value="Comentar">
            </form>
        </section>

    </div>

        <!-- Sección de contacto -->
        <section id="Contacto">
            <h2>Contacto</h2>
            <p>Puedes ponerte en contacto con nosotros a travas de los siguientes medios:</p>
            <section>
                <li>Teléfono: 7833-1687</li>
                <li>Dirección: Avenida del Niño, zona 4, Sumpango, Guatemala</li>
                <li>Facebook: Ineb-d Plan Diario J.V. Sergio Celis Navas Sumpango Sacatepéquez Guatemala</li>
            </form>
        </section>
    </div>

 
    <!-- Footer -->
    <footer>
        <p>Instituto Nacional de Educación</p>
         <p>Básica y Diversificado</p>
          <p>"Sergio Leonel Celis Navas" J.V</p>
           <p>Sumpango Sacatepéquez 2024</p>
    </footer>

</body>
</html>

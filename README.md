<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <main>

    <!-- Navegación principal: conecta las páginas del sitio -->

    <header class="header">

      <div class="menu container">
        <a href="index.html" class="Logo">COFFE</a>
        <input type="checkbox" id="menu" />
        <label for="menu">
          <img src="images/menu.png" class="menu-icono" alt="">
        </label>
        <nav class="navbar">
          <ul>
            <li><a href="index.html" style="text-decoration: none;">Inicio</a></li>
            <li><a href="Servicios.html" style="text-decoration: none;">Servicios</a></li>
            <li><a href="Productos.html" style="text-decoration: none;">Productos</a></li>
            <li><a href="Contacto.html" style="text-decoration: none;">Contacto</a></li>
            <li><a href="Delivery.html" style="text-decoration: none;">Tiendas</a></li>
          </ul>
        </nav>
      </div>

      <div class="header-content container">

        <h1>Todo cafe</h1>
        <p>
          Descubre el sabor auténtico del café en cada taza. Ofrecemos una cuidada selección de cafés de
          especialidad, desde intensos espresso y suaves americanos hasta cremosos cappuccinos y aromáticos
          lattes. Ya sea que prefieras un tostado fuerte o una mezcla balanceada, aquí encontrarás la variante
          perfecta para cada momento del día. Vive la experiencia del café como nunca antes.
        </p>
        <a href="Contacto.html" style="text-decoration: none;" class="btn-1">Informacion</a>
      </div>

    </header>

    <!-- Sección 1: Presentación visual de la cafetería -->
    <section class="Coffee">
      <img class="Coffee-img" src="images/bg2.png" alt="">

      <div class="Coffee-content container">

        <h2>Los diferentes tipos de cafe</h2>
        <p class="txt-p">
          En nuestra tienda encontrarás las tres principales variedades de café del mundo: el suave y aromático
          Arábica, ideal para quienes disfrutan de sabores delicados y complejos; el intenso Robusta, perfecto
          para los que buscan un café con más cuerpo y energía; y el exótico Liberica, con notas únicas y un
          perfil audaz para paladares curiosos. Elige tu variedad favorita y descubre una experiencia de café
          pensada para cada gusto y ocasión.
        </p>

        <div class="Coffee-group">

          <div class="Coffee-1">
            <img src="images/c1.png" alt="">
            <h3>Coffea Robusta</h3>
            <P>
              Sabor más fuerte, amargo y con mayor contenido de cafeína.
              Los usos son comunes en mezclas para espresso, café instantáneo y bebidas energéticas, ya que
              aporta
              cuerpo y una crema espesa.

            </P>
          </div>
          <div class="Coffee-1">
            <img src="images/c2.png" alt="">
            <h3>Coffea Arábica</h3>
            <P>
              Sabor Suave, aromático y con notas frutales o florales.
              Es la variedad más apreciada en cafés de especialidad. Ideal para métodos de extracción
              como filtrado, V60, Chemex o espresso delicado.

            </P>
          </div>
          <div class="Coffee-1">
            <img src="images/c3.png" alt="">
            <h3>Coffea Liberica</h3>
            <P>
              Sabor exótico, con notas amaderadas y afrutadas, menos común.
              Usada en mezclas especiales o en mercados específicos como Filipinas y Malasia, para
              quienes buscan un perfil de sabor único y distintivo.

            </P>
          </div>
        </div>
        <a href="#" style="text-decoration: none;" class="btn-1">Informacion</a>
      </div>


    </section>

    <!-- Sección 3: Catálogo de productos -->
    <section class="Services">
      <div class="Services-content container">

        <h2>Cafeteria servicios</h2>

        <div class="Services-group">

          <div class="Services-1">
            <img src="images/i1.svg" alt="">
            <h3>Americano</h3>
          </div>
          <div class="Services-1">
            <img src="images/i2.svg" alt="">
            <h3>Latte</h3>
          </div>
          <div class="Services-1">
            <img src="images/i3.svg" alt="">
            <h3>Expresso</h3>
          </div>

        </div>
        <p>
          En nuestra cafetería encontrarás una variedad de preparaciones pensadas para cada gusto: desde el
          espresso, intenso y concentrado, hasta el americano, suave y ligero; pasando por el cremoso cappuccino,
          el delicado latte con mayor proporción de leche, y el irresistible moka, que combina café, leche y
          chocolate. Cada bebida está hecha con dedicación para ofrecerte una experiencia única en cada sorbo.
        </p>
        <a href="#" style="text-decoration: none;" class="btn-1">Informacion</a>
      </div>
    </section>


    <!-- Sección 4: Galería de imágenes -->
    <section class="galeria">
      <div class="galeria-container">
        <h2>Ambiente y Experiencia</h2>
        <p>Descubre cómo es vivir un momento en nuestra cafetería.</p>
        <div class="grid">
          <img src="images/img.interiordecafeteria.jpg" alt="Interior de cafetería"
            style="width:100%; max-width:300px;">
          <img src="images/productos.jpg" alt="Mesa con café y postre" style="width:100%; max-width:300px;">
          <img src="images/img.clientes  disfrutando.jpg" alt="Clientes disfrutando"
            style="width:100%; max-width:300px;">
          <img src="images/interior.jpg" alt="interior de Cafeteria" style="width:100%; max-width:300px;">

        </div>
      </div>
    </section>

    <!-- Sección 5: General -->
    <section class="general">

      <div class="general-1">
        <h2>Tipos de cafe que ofrecemos</h2>
        <p>
          Ofrecemos tres tipos de café según su variedad de grano: el Arábica, reconocido por su sabor suave,
          aroma delicado y notas frutales o florales; el Robusta, de sabor más fuerte y amargo, con mayor
          contenido de cafeína, ideal para quienes buscan un café intenso; y el Liberica, menos común, con un
          perfil exótico y afrutado, perfecto para paladares que buscan algo diferente y distintivo.
        </p>
        <a href="#" style="text-decoration: none;" class="btn-1">Informacion</a>
      </div>
      <div class="general-2"></div>

    </section>
    <section class="general">
      <div class="general-3"></div>
      <div class="general-1">
        <h2>Variedad de preparaciones</h2>
        <p>
          Nuestros cafés, ya sean Arábica, Robusta o Liberica, pueden disfrutarse en una amplia variedad de
          preparaciones que realzan sus cualidades únicas: desde un espresso concentrado que resalta la intensidad
          del grano, hasta un americano más suave ideal para apreciar los matices; también ofrecemos opciones como
          el cappuccino y el latte, que combinan café y leche para una experiencia más cremosa, o el moka, que
          añade un toque de chocolate para un sabor dulce y reconfortante. Cada preparación está pensada para
          adaptarse a tu gusto y resaltar lo mejor de cada tipo de café.
        </p>
        <a href="#" style="text-decoration: none;" class="btn-1">Informacion</a>
      </div>
    </section>

    <!-- Sección 2: Video de presentación (YouTube) -->

    <section class="video">
      <img class="Coffee-img" src="images/bg2.png" alt="">

      <div class="video-container">

        <h2>café para todos los gustos</h2>

        <p class="txt-p1">
          Creemos que el café no es solo una bebida, sino una experiencia que se adapta a cada persona,
          momento y estado de ánimo.Somos un espacio acogedor, moderno y cálido, donde cada taza cuenta una historia.
          Mira este breve video sobre los tipos de café.</p>

        <div class="video-content">
          <iframe width="560" height="315"
            src="https://www.youtube.com/embed/dRCOwt0flLs?si=1z7bh8X7jPUcWkM7&amp;controls=0"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>

      </div>

    </section>

    <!-- Sección 6: Blog e interacciones -->

    <section class="Blog container">

      <h2>Blog</h2>
      <p>Descubre todo acerca de nosotros</p>

      <div class="Blog-content">
        <div class="Blog-1">
          <img src="images/blog1.jpg" alt="">
          <h3>Cafe acojedor</h3>
          <p>
            Espacio cálido y confortable donde el aroma del café recién hecho te invita a relajarte y disfrutar
            del momento. Su ambiente combina una decoración armoniosa, iluminación suave, atención amable y
            detalles que hacen sentir como en casa. Es el lugar perfecto para conversar, trabajar con calma o
            simplemente disfrutar de una buena taza de café en un entorno tranquilo y agradable
          </p>
        </div>
        <div class="Blog-1">
          <img src="images/blog2.jpg" alt="">
          <h3>Barafe</h3>
          <p>
            Espacio versátil que combina lo mejor de dos mundos: la calidez y tranquilidad de una cafetería con
            la energía y el ambiente social de un bar. Durante el día, es ideal para disfrutar de un buen café,
            leer o trabajar en un entorno relajado; y por la tarde o noche, se transforma en un lugar animado
            donde compartir cócteles, cervezas o bebidas especiales entre amigos. Su ambiente acogedor y
            dinámico lo convierte en el punto de encuentro perfecto para cualquier hora del día.
          </p>
        </div>
        <div class="Blog-1">
          <img src="images/blog3.jpg" alt="">
          <h3>Breakfast</h3>
          <p>
            Ideal para comenzar el día con buen sabor y energía. Ofrece un ambiente acogedor y familiar, donde
            se pueden disfrutar desde cafés recién preparados hasta jugos naturales, panes artesanales, huevos
            al gusto, frutas y otras opciones deliciosas y nutritivas. Es el espacio perfecto para relajarse por
            la mañana, compartir un desayuno con amigos o simplemente tomarse un momento para uno mismo antes de
            iniciar la jornada.
          </p>
        </div>
      </div>

      <a href="#" style="text-decoration: none;" class="btn-1">Informacion</a>

    </section>

    <!-- Sección 7: Formulario de suscripción -->
    <section class="suscripcion">
      <div class="suscripcion-container">
        <h2>Suscríbete a nuestra comunidad</h2>
      </div>

      <div class="suscripcion-content">
        <form>
          <label for="nombre">Nombre completo:</label>
          <input type="nombre" id="nombre" name="nombre" required>
        </form>
        <form>
          <label for="correo">Correo:</label>
          <input type="email" id="correo" name="correo" required>
          <button type="submit">Suscribirse</button>
        </form>
      </div>
      
    </section>


      <!-- Sección 8: Ubicación / mapa -->
      <section class="ubicacion">
        <div class="ubicacion-container">
          <h2>¿Dónde nos encontramos?</h2>
        </div>
        <div class="ubicacion-content">
          <p>Visítanos en Av. Angamos Oeste 1003, Miraflores.</p>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d62414.11703637561!2d-77.0386926!3d-12.1202039!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9105c83bff6daaef%3A0x84518c6b33f3434f!2sCaf%C3%A9%20de%20Lima%20-%20Angamos!5e0!3m2!1ses-419!2spe!4v1750037720769!5m2!1ses-419!2spe"
            width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
      
      </section>

  </main>

  <footer class="footer">
    <div class="footer-content container">
      <div class="link">
        <h3>Nosotros</h3>
        <ul>
          <li> <a href="#" style="text-decoration: none;">Nuestro equipo</a></li>
          <li> <a href="#" style="text-decoration: none;">Gerencia</a></li>
          <li> <a href="#" style="text-decoration: none;">Acerca de</a></li>
          <li> <a href="#" style="text-decoration: none;">Trabaja con nosotros</a></li>
        </ul>
      </div>
      <div class="link">
        <h3>Servicios</h3>
        <ul>
          <li> <a href="#" style="text-decoration: none;">Delivery</a></li>
          <li> <a href="#" style="text-decoration: none;">Pedir para llevar</a></li>
          <li> <a href="#" style="text-decoration: none;">Alquiler</a></li>
          <li> <a href="#" style="text-decoration: none;">Coorporativo</a></li>
        </ul>
      </div>
      <div class="link">
        <h3>Contactanos</h3>
        <ul>
          <li> <a href="#" style="text-decoration: none;">Libro de reclamaciones</a></li>
          <li> <a href="#" style="text-decoration: none;">Donde nos encontramos</a></li>
          <li> <a href="#" style="text-decoration: none;">Informacion</a></li>
          <li> <a href="#" style="text-decoration: none;">Resolvemos</a></li>
        </ul>
      </div>
      <div class="link">
        <h3>Siguenos</h3>
        <ul>
          <li> <a href="#" style="text-decoration: none;">Nuestras redes sociales</a></li>

        </ul>
      </div>
    </div>
  </footer>
</body>

</html>

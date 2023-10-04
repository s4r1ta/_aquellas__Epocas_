# _aquellas__Epocas_
El mejor contenido
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Enlaza los archivos CSS de Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap.min.css">

    <!-- Enlaza los archivos JavaScript de Bootstrap (jQuery y Popper.js) -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap/dist/js/bootstrap.min.js"></script>
</head>
<body>

<!-- Barra de navegación -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">Mi Página</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca de</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Contenido principal -->
<div class="container mt-4">
  <h1>Bienvenido a mi página</h1>
  <p>Esta es una página que utiliza Bootstrap para estilizar su contenido.</p>
    <p>He enlazado los archivos de Bootstrap en la sección <head> de la página para que los estilos y las funcionalidades de Bootstrap estén disponibles.</p>

<p>Utilice una barra de navegación (navbar) de Bootstrap con una estructura típica que incluye un logotipo, un botón de alternancia de navegación, y una lista de elementos de menú.</p>

Cree un botón de Bootstrap utilizando la clase btn btn-primary</p>
  <button class="btn btn-primary">Botón de Ejemplo</button>
</div>

</body>
</html>

<head>
  <title>Aquellas Épocas</title>
  <style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #D79AA9;
    color: black;
  }
  header {
    background-color: #F351B6;
    color: black;
    text-align: center;
    padding: 1rem;
  }
  .container {
    max-width: 5000px;
    margin: 0 auto;
    padding: 2rem;
  }
  footer {
      background-color: #D671DC;
      background-position: center center;
      color: black;
      padding: 20px;
      border-radius: 15px;
      border: 5px solid #D5671D;
            background-size: cover; 
      background-repeat: no-repeat;
      background-position: center center; 
    }
        .dropdown {
      position: relative;
      display: inline-block;
    }
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #AA71DC;
      min-width: 160px;
      z-index: 1;
    }
    .dropdown:hover .dropdown-content {
      display: block;
    }
    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
    }
    .dropdown-content a:hover {
      background-color: #AA71DC;
    }
     section {
      padding: 20px;
      color: black
        }
     article {
      background-color: #AA71DC;
      border: 3px solid #F0FB64;
      border-radius: 5px;
      margin-bottom: 20px;
      padding: 20px;
        }
      .imagen_centrada {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40vh;
        }
        #subtema1 {
        text-decoration: underline;
        text-decoration-color: #F0FB64;
        font-size: 25px;
        text-decoration-thickness: 3px;
        }
        #subtema2 {
        text-decoration: underline;
        text-decoration-color: #F0FB64;
        font-size: 25px;
        text-decoration-thickness: 3px;
}
        #subtema3 {
        text-decoration: underline;
        text-decoration-color: #F0FB64;
        font-size: 25px;
        text-decoration-thickness: 3px;
}
    table {
      border: 5px solid #F0FB64;
      width: 96%;
      margin: 20px auto;
      border-radius: 10px;
      overflow: hidden;
    }
    th, td {
      padding: 13px;
      text-align: left;
      border-color: #003235;
    }
    th {
      background-color: #015156;
    }
    tr:nth-child(even) {
      background-color: #006F76;
    }

    nav {
      color: #fff;
      text-align: center;
}
 nav.tema1 {
      color: #fff;
      text-align: left;
      }
  </style>
</head>
<body>
  <header>
    <h1>Época Clásica</h1>
    <p>He creado esta pagina con el fin de que puedas aprender de esta magica epoca clásica,fue un periodo de la historia de la humanidad que se caracterizó por sus grandes avances culturales, científicos y filosóficos.Fue una época marcada por el florecimiento del arte y la literatura, la filosofía y la democracia.</p>
    <div class="dropdown">
      <span>Opciones</span>
      <div class="dropdown-content">
        <a href="#subtema1">Subtema 1</a>
        <a href="#subtema2">Subtema 2</a>
        <a href="#subtema3">Subtema 3</a>
      </div>
    </div>
  </header>
  <div class="container">
    <div class="imagen_centrada">
      <img src="https://pymstatic.com/122060/conversions/baja-edad-media-social.jpg" alt="edad media.jpg" width="420">
    </div>
    <article>
      <h2 id="lista">Lista</h2>
      <ol>
        <strong>
          <li><a href="#subtema1" style="color: #FFFFFF;">¿Qué es la época clásica?</a></li>
          <li><a href="#subtema2" style="color: #FFFFFF;">La Grecia Clásica de -510 a 330 a. C-</a></li>
          <li><a href="#subtema3" style="color: #FFFFFF;">Tabla</a></li>
        </strong>
      </ol>
      <h2 id="externo">Links Externos</h2>
      <a href="https://www.youtube.com/watch?v=9LMlD7L4Vdk" style="color: #FFFFFF;" target="_blank">Video sobre la antigua grecia</a><br>
      <br>
      <a href="file:///C:/Users/SARA%20ARIZA%20GONZALEZ/Downloads/Dialnet-LaEducacionEnLaAntiguaGrecia-2676979.pdf" style="color: #FFFFFF;" target="_blank">Articulo -Época Clásica-</a>
    </article>
    <nav>
    <article>
      <ul>
        <h3 id="subtema1"><li>¿Qué es la época clásica?</li></h3>
        <p>La “Época Clásica” o “Antigüedad Clásica”, es un período de la historia ubicado entre la Alta Antigüedad (cuando aparecieron las primeras civilizaciones de Oriente Próximo Antiguo) y la Baja Antigüedad (la transición hacia la Edad Media).Este período corresponde al florecimiento de la cultura grecorromana, ubicada en la cuencadel Mediterráneo y las costas del Oriente Próximo. Incluye el momento en que la civilizacióngriega alcanzó su máximo esplendor artístico, filosófico, arquitectónico y económico y eldesarrollo del Periodo Helenístico, durante el cual la cultura griega se extendió por Oriente y fue, a su vez, influenciada por elementos culturales de las culturas locales.También comprende el desarrollo de la cultura romana en la península itálica y su conquista de la región mediterránea y el Cercano Oriente.<p>La época clásica comienza en el siglo V a. C., con el fin de la guerra entre las ciudades-Estado de la Grecia Antigua y el Imperio Persa. Los ejércitos griegos obtuvieron la victoria ante el invasor persa. Así se fundó un nuevo sentimiento de grandeza y de confianza cultural entre sus habitantes.Ambas civilizaciones constituyen un antecedente fundamental de la cultura occidental actual, debido a que en su seno se crearon instituciones, prácticas y formas de pensamiento que siguieron influenciando a las sociedades europeas durante siglos.</p>
        </p>
        </nav>
      </ul>
    </article>
    </nav>
    <nav>
    <article>
      <h3 id="subtema2"><li>La Grecia Clásica de -510 a 330 a. C-</li></h3>
      <p><br>Entre los siglos VI y IV a. C., las polis griegas tuvieron una época de esplendor, riqueza económica y desarrollo cultural. Tebas, Atenas, Corinto, Mileto y Esparta resaltaron por sus avances artísticos, arquitectónicos y militares. Además, promovieron la profundización de los conocimientos matemáticos, filósofos y el estudio de la naturaleza. En Atenas, el periodo que va del 490 y 404 a. C. es conocido como el Siglo de Oro, debido a su esplendor cultural, político y económico.

Los principales rasgos del esplendor de la cultura griega fueron los siguientes:<br>
      <br>
      Filosofía: La disciplina filosófica nació en el siglo VI a. C., y tuvo su esplendor durante el siglo V a. C. Los pensadores se cuestionaban sobre el origen de la vida y el funcionamiento de la naturaleza, y enaltecían el pensamiento racional para conocer y comprender el mundo en el que vivían. Platón y Aristóteles, entre otros filósofos, son exponentes de la filosofía clásica griega.

Estudio de la naturaleza: Otros pensadores, como Heráclito, Zenón, Anaxágoras, Parménideso Empédocles estudiaron otros temas relacionados a la naturaleza (como la astronomía o la botánica).
<br>
      <br>
      Medicina:De esta época datan los estudios de Alcmeón e Hipócrates, que investigaronel cuerpo humano y desarrollaron importantes avances en medicina.

Artes: Durante el periodo clásico, hubo un gran fomento a las artes. Algunas ciudades, como Atenas,se convirtieron en centros para el desarrollo artístico, tanto para las artes visuales (como la escultura) comopara las artes escénicas (como el teatro). De este periodo data la arquitectura de Fidias y las obras de teatro de Sófocles, Esquilo y Eurípides.

Política: Cada polis mantuvo su independencia política y estableció su propio sistema de gobierno. En Esparta, por ejemplo, se estableció un gobierno aristocrático que tenía diferentes magistraturas(algunas temporales y otras vitalicias). En Atenas se desarrolló, por primera vez en la historia, un sistema de gobierno democrático que incorporaba la participación política del pueblo.

En la segunda mitad del siglo V a. C., la rivalidad entre Atenas y Esparta, las dos polis más poderosas, aumentó y generó la formación de dos coaliciones: la Liga de Delos (ateniense) y la Liga del Peloponeso (espartana). Las diferentes polis de la región quedaron alineadas en uno u otro bando y, desde 431 a. C., se enfrentaron en la Guerra del Peloponeso. Hacia 404 a. C, la Liga de Delos fue finalmente derrotada. Sin embargo, estas décadas de guerra debilitaron a todas las polis que se vieron involucradas en el conflicto.</p>
      </nav>
    </article>
        </nav>
    <article>
      <h1 id="subtema3"> Tabla </h1>
      <h3><table>
          <tr>
              <th>Sucesos importantes</th>
              <th>Caracteristicas</th>
              <th>Causas</th>
          </tr>
          <tr>
            <td>El Imperio Romano de Occidente.</td>
            <td>Tuvo lugar entre los siglos XII y XV d. C. y se caracterizó por la decadencia de la Iglesia </td>
            <td>Caída del Imperio Romano Occidental.</td>
          </tr>
          <tr>
            <td>La invasión islámica.</td>
            <td>El poder monárquico, el hambre, las pestes y las cruzadas,que consistieron en ocho campañas militares impulsadas por la Iglesia católica contra Palestina.</td>
              <td>Fundación del Imperio de Oriente Bizantino.</td>
          </tr>
          <tr>
             <td>El Sacro Imperio Romano Germánico.</td>
             <td>El historiador sacerdote jesuita Gregorio Arango dice que la Edad Media es la edad de la plenitud, porque hubo un gran adelanto en la cultura y en la civilización</td>
             <td>Conformación de los Reinos Germanos.</td>
          </tr>
          <tr>
             <td>Época de carestía.</td>
             <td>Nacieron muchas de las ciudades europeas y se fundaron las más famosas universidades, o "los templos del saber"</td>
             <td>División del Imperio en Occidente Y Oriente</td>
          </tr>
      </table></h3>
    </article>

  <footer>
    <div>
      <p><strong>Autor: Sara Ariza Gonzalez</strong></p>
      <img src="file:///C:/Users/SARA%20ARIZA%20GONZALEZ/Desktop/Skolmi%20foto.jpg.jpeg" alt="Skolmi foto.jpg">
      <p><strong>Fecha de Creación: 8/24/23</strong></p>
      <p><strong>Instituto: Skolmi</strong></p>
      <p><strong>Esta web está principalmente sustentada de la siguiente <a href="https://humanidades.com/epoca-clasica/">web</a>.</p> </strong>
      <p><strong>correo:</strong> <a href="https://mail.google.com/">saraarizagomzalez1911@gmail.com</a></p>
    </div>
  </footer>
</body>
</html>

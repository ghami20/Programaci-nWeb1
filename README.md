<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Ejemplo con Bootstrap</title>
    <!-- CSS de Bootstrap -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Barra de navegación -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">
            Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Características</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Precios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Deshabilitado</a>
        </li>
      </ul>
    </div>
  </nav>
  
  <!-- Carrusel -->
  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Primer slide">
      </div>
      <div class="carousel-item">
        <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Segundo slide">
      </div>
      <div class="carousel-item">
        <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Tercer slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Anterior</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Siguiente</span>
    </a>
  </div>
  
  <!-- Sección de Tarjetas -->
  <div class="container my-4">
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/150" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Título de la Tarjeta 1</h5>
            <p class="card-text">Texto de ejemplo rápido para construir el título de la tarjeta y completar el contenido de la tarjeta.</p>
            <a href="#" class="btn btn-primary">Ir a algún lugar</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/150" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Título de la Tarjeta 2</h5>
            <p class="card-text">Texto de ejemplo rápido para construir el título de la tarjeta y completar el contenido de la tarjeta.</p>
            <a href="#" class="btn btn-primary">Ir a algún lugar</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/150" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Título de la Tarjeta 3</h5>
            <p class="card-text">Texto de ejemplo rápido para construir el título de la tarjeta y completar el contenido de la tarjeta.</p>
            <a href="#" class="btn btn-primary">Ir a algún lugar</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Sección de Tabla -->
  <div class="container my-4">
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Nombre</th>
          <th scope="col">Apellido</th>
          <th scope="col">Alias</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Larry</td>
          <td>el Pájaro</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
  
  <!-- Sección de Formulario -->
  <div class="container my-4">
    <form>
      <div class="form-group">
        <label for="exampleInputEmail1">Dirección de email</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Ingresa tu email">
        <small id="emailHelp" class="form-text text-muted">Nunca compartiremos tu email con nadie más.</small>
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1">Contraseña</label>
        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Contraseña">
      </div>
      <div class="form-group form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Recuérdame</label>
      </div>
      <button type="submit" class="btn btn-primary">Enviar</button>
    </form>
  </div>
  
  <!-- Jumbotron -->
  <div class="jumbotron">
    <h1 class="display-4">¡Hola, mundo!</h1>
    <p class="lead">Esta es una unidad heroica simple, un componente de estilo jumbotron para llamar la atención adicional a contenido o información destacados.</p>
    <hr class="my-4">
    <p>Usa clases de utilidad para tipografía y espaciado para separar el contenido dentro del contenedor más grande.</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Aprender más</a>
  </div>
  
  <!-- Botón para abrir Modal -->
  <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
    Lanzar modal de demostración
  </button>
  
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Título del Modal</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Cerrar">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          ...
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">Cerrar</button>
          <button type="button" class="btn btn-primary">Guardar cambios</button>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Barra de Progreso -->
  <div class="container my-4">
    <div class="progress">
      <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100" id="progressBar">25%</div>
    </div>
    <button class="btn btn-primary mt-3" onclick="increaseProgress()">Incrementar Progreso</button>
  </div>
  
  <!-- Pie de Página -->
  <footer class="bg-light text-center text-lg-start">
    <div class="container p-4">
      <div class="row">
        <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
          <h5 class="text-uppercase">Contenido del Pie de Página</h5>
          <p>
            Aquí puedes usar filas y columnas para organizar tu contenido del pie de página. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit.
          </p>
        </div>
  
        <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase">Enlaces</h5>
          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-dark">Enlace 1</a>
            </li>
            <li>
              <a href="#!" class="text-dark">Enlace 2</a>
            </li>
            <li>
              <a href="#!" class="text-dark">Enlace 3</a>
            </li>
            <li>
              <a href="#!" class="text-dark">Enlace 4</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
  
  <!-- JS de Bootstrap y dependencias -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    function increaseProgress() {
      var progressBar = document.getElementById("progressBar");
      var currentWidth = parseInt(progressBar.getAttribute("aria-valuenow"));
      var newWidth = currentWidth + 10;
      if (newWidth > 100) {
        newWidth = 100;
      }
      progressBar.style.width = newWidth + "%";
      progressBar.setAttribute("aria-valuenow", newWidth);
      progressBar.textContent = newWidth + "%";
    }
  </script>
  
  </body>
  </html>
  

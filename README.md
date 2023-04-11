# ejercicio-12
tarea de bootcamp
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elementos de Interés en Bootstrap</title>
</head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
rel="stylesheet" 
integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
 integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" 
 crossorigin="anonymous"></script>

<body>
    <div class="container">
        <div class="bg-ligth p-5 rounded-3">
            <div class="container-fluid py-5">
               <h1 class="display-5 fw-bold">custom jumbotron</h1>
               <p class="col-md-8 fs-4">Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                    Nulla odit quis omnis porro nesciunt ad corporis accusamus 
                    enim magnam nam voluptates rem maxime, 
                   est, quia doloremque veniam illum, perspiciatis libero?</p>
                   <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    Launch demo modal
                  </button>
                  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                    <div class="modal-dialog">
                      <div class="modal-content">
                        <div class="modal-header">
                          <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                          ...
                        </div>
                        <div class="modal-footer">
                          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                          <button type="button" class="btn btn-primary">Save changes</button>
                        </div>
                      </div>
                    </div>
                  </div>
              </div>
  </div>

  <div class="row">
    <div class="col">
      <input type="text" class="form-control" placeholder="Ingresa tu nombre" aria-label="Ingresa tu nombre">
    </div>
    <div class="col">
      <input type="text" class="form-control" placeholder="Numero de telefono" aria-label="Numero de telefono">
      <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label">Mensaje</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
      </div>
 </div>
  </div>

  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Abdias manuela piña coronado</h5>
          <p class="card-text">aprendiendo a programar en HTML gracias a openbootcamp</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">manuelian0902@gmail.com</small>
        </div>
      </div>
    </div>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Website</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color:rgb(0, 146, 243)/* Light gray background color */
    /* Added styles for image border and background color */
    }
    .carousel-inner img  {
      border: 1px solid #ff2600; /* Add a gray border */
      border-radius: 4px; /* Rounded corners */
      padding: 5px; /* Add some padding */
      background-color: #ff2600;/* Light gray background color */
    }

    .card img {
        border: 1px solid #ffe600; /* Add a gray border */
      border-radius: 4px; /* Rounded corners */
      padding: 5px; /* Add some padding */
      background-color:  #ffe600;/* Light gray background color */
    }
  </style>
</head>
<body>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Your Website</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="destination1.jpg" class="d-block w-100" alt="Image 1">
      </div>
      <div class="carousel-item">
        <img src="destination2.jpg" class="d-block w-100" alt="Image 2">
      </div>
      <div class="carousel-item">
        <img src="destination3.jpg" class="d-block w-100" alt="Image 3">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleSlidesOnly" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleSlidesOnly" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  <div class="card mt-3">
    <img src="image.jpg" class="card-img-top" alt="Card Image">
    <div class="card-body">
      <h5 class="card-title">Card Title</h5>
      <p class="card-text">BAGUIO CITY TOURIST SPOT and new places to visit...</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

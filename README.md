<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Bootstrap CSS Files -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css">
    <link rel="stylesheet" href="bootstrap/css/font-awesome-5.8.2.css">
    <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
    <link rel="stylesheet" href="bootstrap/css/mdb.css">
    <link rel="stylesheet" href="bootstrap/css/style.css">
    <title>Tour & Travel </title>
</head>
<body>
    <!-- Main Navbar -->
    <nav class="navbar navbar-expand-sm navbar-dark bg-teal">
        <div class="container">
            <a href="index.html" class="navbar-brand">
               <i class="fa fa-plane-departure"></i> Tour & Travel</a>
            <button class="navbar-toggler" data-toggle="collapse" data-target="#travel-navbar">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="travel-navbar">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item px-3">
                        <a href="#" class="nav-link">Home</a>
                    </li>
                    <li class="nav-item px-3">
                        <a href="#search" class="nav-link">Search</a>
                    </li>
                    <li class="nav-item px-3">
                        <a href="#places" class="nav-link">Visiting Spots</a>
                    </li>
                    <li class="nav-item px-3">
                        <a href="#gallery" class="nav-link">Gallery</a>
                    </li>
                    <li class="nav-item px-3">
                        <a href="#contact" class="nav-link">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Slider Section -->
    <section>
        <div class="carousel slide" id="travel-slider" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#travel-slider" data-slide-to="0" class="active"></li>
                <li data-target="#travel-slider" data-slide-to="1"></li>
                <li data-target="#travel-slider" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="images/slider_one.jpg" alt="" class="img-fluid w-100">
                    <div class="carousel-caption text-left animated zoomIn delay-1s">
                        <h5 class="display-4">Feel The JOY</h5>
                        <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur culpa eaque et eum maxime nisi perferendis quo ratione repellendus vitae.</p>
                        <button class="btn btn-teal">Read More</button>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="images/slider_two.jpg" alt="" class="img-fluid w-100">
                    <div class="carousel-caption text-right animated zoomIn delay-1s">
                        <h5 class="display-4">Ultimate Destination</h5>
                        <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur culpa eaque et eum maxime nisi perferendis quo ratione repellendus vitae.</p>
                        <button class="btn btn-teal">Read More</button>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="images/slider_three.jpg" alt="" class="img-fluid w-100">
                    <div class="carousel-caption text-left animated zoomIn delay-1s">
                        <h5 class="display-4">Be Relaxed in Nature</h5>
                        <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur culpa eaque et eum maxime nisi perferendis quo ratione repellendus vitae.</p>
                        <button class="btn btn-teal">Read More</button>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#travel-slider" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#travel-slider" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </section>
    
    <!-- Search Section -->
    <section id="search" class="p-3 bg-teal text-white">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h5 class="display-4">Search Your Destination</h5>
                    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. At dolorum eaque magnam molestiae nostrum officiis pariatur placeat quibusdam totam voluptatem!</p>
                    <div class="row">
                        <div class="col-md-6">
                            <form>
                                <div class="form-group">
                                    <input type="search" class="form-control" placeholder="Paris">
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="bg-light p-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="card text-center mt-3">
                        <div class="card-body">
                            <i class="fa fa-location-arrow fa-4x text-teal"></i>
                            <p class="h2">Pick Location</p>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad dolorum facere iusto libero nemo obcaecati quos ratione repellendus sit voluptatum.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card text-center mt-3">
                        <div class="card-body">
                            <i class="fa fa-building fa-4x text-teal"></i>
                            <p class="h2">Shop Travel</p>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad dolorum facere iusto libero nemo obcaecati quos ratione repellendus sit voluptatum.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card text-center mt-3">
                        <div class="card-body">
                            <i class="fa fa-plane-departure fa-4x text-teal"></i>
                            <p class="h2">Fly Cheap</p>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad dolorum facere iusto libero nemo obcaecati quos ratione repellendus sit voluptatum.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>






    <!-- Bootstrap Js Files -->
    <script src="bootstrap/js/jquery.js"></script>
    <script src="bootstrap/js/popper.js"></script>
    <script src="bootstrap/js/bootstrap.js"></script>
    <script src="bootstrap/js/mdb.js"></script>
</body>
</html>

# UTS_PPAW_F
IIS,MUGNI,SRI
index.html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">


    <!-- my fonts -->
    <link href="https://fonts.googleapis.com/css?family=Viga" rel="stylesheet">


    <!-- my css -->
    <link rel="stylesheet" href="style.css">

    <title>Peraktikum Pengembangan Aplikasi Web</title>
     </head>
  <body>
  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light ">
    <div class="container">
    <a class="navbar-brand" href="#">MugIsRi</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav ml-auto">
        <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
        <a class="nav-item nav-link" href="#">Pricing</a>
        <a class="nav-item nav-link" href="#">Features</a>
        <a class="nav-item nav-link" href="#">About</a>
        <a class="nav-item btn btn-primary tombol" href="#">Join Us</a>
      </div>
    </div>
  </div>
  </nav> 
   <!-- akhir navbar -->


<!-- jumbotron -->
<div class="jumbotron jumbotron-fluid">
    <div class="container">
      <h1 class="display-4">Fluid jumbotron</h1>
   <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
    </div>
  </div>
<!-- akhir jumbotron -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>




#style.css
  /* navbar */
.navbar-brand {
    font-family: viga;
    font-size: 32 px;
}
/* jumbotron */
.jumbotron{
    background-image: url(img/jumbotron-bg.jpg);
    background-size: cover;
    height:640px;
   
    
}
/* utylity */
.tombol {
    text-tansfrom: uppercase;
    border-radius: 40px;
}
/* desktop version */
@media (min-width: 992px) {
    
    .nav-link {
        text-transform: uppercase;
        margin-right: 30x;
    }

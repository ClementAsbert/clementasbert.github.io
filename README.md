
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
      rel="stylesheet" />
    <link rel="stylesheet" href="../css/style3.css" />
    <link
      href="https://fonts.googleapis.com/css2?family=Playwrite+IT+Moderna:wght@100&display=swap"
      rel="stylesheet" />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap"
      rel="stylesheet" />
    <link rel="stylesheet" href="../css/variable.css" />
    <title>AREMS</title>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-custom">
      <div class="container-fluid">
        <a class="navbar-brand text-white" href="index.html">Medina Sousse</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false">
                Monuments
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="ribat.html">Le Ribat</a>
                <a class="dropdown-item" href="grande_mosquee.html"
                  >La Grande Mosquée</a
                >
                <a class="dropdown-item" href="#">La Mosquée Bou Ftata</a>
                <a class="dropdown-item" href="#">La Casbah</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="aPropos.html">À propos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container-fluid">
      <div class="row">
        <div class="col-12 p-0">
          <div
            id="carouselExampleSlidesOnly"
            class="carousel slide custom-carousel"
            data-ride="carousel"
            data-interval="2000">
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img
                  class="d-block w-100"
                  src="../img/19f19060-2d3d-4a9d-84da-bb35e05bffdf.jpg"
                  alt="First slide" />
              </div>
              <div class="carousel-item">
                <img
                  class="d-block w-100"
                  src="../img/968ba3ec-c86d-4e89-bb4d-2281fbf48e7f.jpg"
                  alt="Second slide" />
              </div>
              <div class="carousel-item">
                <img
                  class="d-block w-100"
                  src="../img/c6ea1a45-988f-4b81-ad12-d0af0988bac9.jpg"
                  alt="Third slide" />
              </div>
            </div>
          </div>
        </div>

        <div class="col-12 container-title">
          <div class="wave-container">
            <svg
              class="wave-svg"
              id="visual"
              viewBox="0 0 900 100"
              width="900"
              height="100"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              version="1.1">
              <path
                d="M0 63L37.5 66.3C75 69.7 150 76.3 225 72.7C300 69 375 55 450 56C525 57 600 73 675 75.8C750 78.7 825 68.3 862.5 63.2L900 58L900 101L862.5 101C825 101 750 101 675 101C600 101 525 101 450 101C375 101 300 101 225 101C150 101 75 101 37.5 101L0 101Z"
                fill="#efbf6a"
                stroke-linecap="round"
                stroke-linejoin="miter"></path>
            </svg>
            <svg
              id="visual-overlay"
              class="wave-svg-overlay"
              viewBox="0 0 900 100"
              width="900"
              height="100"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              version="1.1">
              <path
                d="M0 61L30 55.3C60 49.7 120 38.3 180 44.7C240 51 300 75 360 81C420 87 480 75 540 66.3C600 57.7 660 52.3 720 49.2C780 46 840 45 870 44.5L900 44L900 101L870 101C840 101 780 101 720 101C660 101 600 101 540 101C480 101 420 101 360 101C300 101 240 101 180 101C120 101 60 101 30 101L0 101Z"
                fill="#efbf6a"
                stroke-linecap="round"
                stroke-linejoin="miter"></path>
            </svg>
          </div>
          <div class="title-content">
            <h1>MEDINA SOUSSE</h1>
            <h5>Patrimoine Mondiale de L'UNESCO</h5>
            <button class="arrow-button">
              <div class="arrow-down"></div>
            </button>
            <a href="ribat.html"
              ><p class="start-visit">Commencer la visite</p></a
            >
          </div>
          <div class="partner-logos">
            <img src="../img/epi.png" alt="Partner 1" class="img-fluid mx-2" />
            <img
              src="../img/esiea-logo.png"
              alt="Partner 2"
              class="mg-fluid mx-2" />
            <img
              src="../img/186489855_4091993964214757_4481731711065158020_n.jpg"
              alt="Partner 3"
              class="mg-fluid mx-2" />
          </div>
        </div>
      </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  </body>
</html>
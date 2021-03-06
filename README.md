# Web-Design-Challenge-Final
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <link rel="stylesheet" href="/Web-Pages/style.css">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home Page</title>
</head>

<body>
  <!-- Create Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light" id="navbar-box">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Latitude</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">Plots</a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <li><a class="dropdown-item" href="/Web-Pages/max_temp.html">Max Temperature</a></li>
              <li><a class="dropdown-item" href="/Web-Pages/humidity.html">Humidity</a></li>
              <li><a class="dropdown-item" href="/Web-Pages/cloudiness.html">Cloudiness</a></li>
              <li><a class="dropdown-item" href="/Web-Pages/wind.html">Wind Speed</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Web-Pages/comparison.html">Comparisons</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Web-Pages/data.html">Data</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container">
    <!-- Left Side -->
    <div class="row">
      <div class="col-8" id="left_side">
        <br><br>
        <h1>Summary: Latitude vs. X</h1>
        <hr>
        <div class="row">
          <img class="mr-3 img-fluid" style="width:auto; height:360px;" src="Resources/assets/images/Fig1.png"
            alt=" City Latitude vs. Max Temperature">
          <div class="col">
            <p>The purpose of this project was to analyse how weather changes as you get closer to the equator. To
              accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset over 500
              cities.</p>
          </div>
          <p>After assembling the dataset, we used Matplotlib to plot aspects of the weather vs. latitude.
            Factors we looked at included: temperature, cloudiness, wind speed, and humidity. This site provides the
            sources data and visualizations created as part of the analysis, as well as explanations and descriptions of
            any trends and correlations witnessed.</p>
        </div>
      </div>

      <!-- Right Side -->
      <div class="col-4 ml-auto" id="right_side">
        <br><br>
        <h1>Visualizations</h1>
        <hr>
        <div class="row">
          <div class="col">
            <h6>Max Temperature</h6>
            <a href="/Web-Pages/max_temp.html"><img class="mr-3 img-fluid" width="auto"
                src="Resources/assets/images/Fig1.png"
                alt="City Latitude vs. Max Temperature Image"></a>
          </div>

          <div class="col">
            <h6>Humidity</h6>
            <a href="/Web-Pages/humidity.html"><img class="mr-3 img-fluid" width="auto"
                src="Resources/assets/images/Fig2.png" alt="City Latitude vs. Humidity Image"></a>
          </div>
        </div>

        <div class="row">
          <div class="col">
            <h6>Cloudiness</h6>
            <a href="/Web-Pages/cloudiness.html"><img class="mr-3 img-fluid" width="auto"
                src="Resources/assets/images/Fig3.png"
                alt="City Latitude vs. Cloudiness Image"></a>
          </div>

          <div class="col">
            <h6>Wind Speed</h6>
            <a href="/Web-Pages/wind.html"><img class="mr-3 img-fluid" width="auto"
                src="Resources/assets/images/Fig4.png"
                alt="City Latitude vs. Wind Speed Image"></a>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
    crossorigin="anonymous"></script>
</body>

</html>

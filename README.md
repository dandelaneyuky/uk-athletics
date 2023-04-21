# uk-athletics

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8" />
  <University of Kentucky Athletics>Presentation</title>
  <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;800&display=swap" rel="stylesheet" />
  <style>
    /* Set margin/padding to fit border in box model */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    /* Define styles on body (and all descendants) */
    body {
      margin: 0;
      padding: 0;
      font-family: "Open Sans", sans-serif;
      font-weight: 400;
      color: rgb(32, 32, 32);
      background-color: rgb(236, 232, 228);
    }

    /* Define styles for the headings */
    h1 {
      font-size: 3rem;
      font-weight: 800;
      margin: 10px 0;
      padding: 0;
      color: rgb(0, 0, 0);
    }

    h2 {
      font-size: 2rem;
      font-weight: 800;
      margin: 0;
      padding: 0;
    }


    h3 {
      font-size: 1.5rem;
      font-weight: bold;
      margin-bottom: 10px;
    }

    /* Define styles for the paragraph */
    p {
      font-size: 1.3rem;
      font-weight: 400;
      margin: 0 0 10px 0;
      padding: 0;
    }

    a:link,
    a:visited {
      color: rgb(12, 73, 34);
    }

    a:hover {
      color: rgb(86, 86, 86);
      text-decoration: none;
    }

    section {
      width: 80%;
      margin: 0 auto;
    }

    footer {
      width: 80%;
      margin: 0 auto;
      color: rgb(100, 100, 100);
    }

    iframe {
      border: 1px solid rgb(200, 200, 200);
      border-radius: 10px;
      margin-top: 20px;
    }

    .caption {
      font-size: 0.8rem;
      font-weight: 400;
      font-style: italic;
      margin: 0;
      padding: 0;
      color: rgb(100, 100, 100);
    }

    .title {
      text-align: left;
      margin: 20px;
    }

    /* Set up a container for the two columns */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    /* Define styles for the left column */
    .left-column {
      flex-basis: 40%;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Define styles for the right column */
    .right-column {
      flex-basis: 55%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Round image corners for images inside the right-column */
    .right-column img {
      border-radius: 10px;
    }

    /* Media query for small screens */
    /* For screens up to 768px, apply these rules. */
    @media (max-width: 768px) {

      /* Change to a single column layout */
      .container {
        flex-direction: column;
      }

      /* Set full width for both columns */
      .left-column,
      .right-column {
        flex-basis: 100%;
      }
    }
  </style>
</head>

<body>
  <section>
    <iframe title="University of Kentucky Athletics" width="1024" height="576" src="https://ion.cesium.com/stories/viewer/?id=e4c45b6f-41ff-4cb1-92f7-3e8a2204a7a9" frameborder="0" allow="fullscreen" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe> 
    <p class="caption">Cesium slideshow</p>
    <div class="title">
      <h1>University of Kentucky</h1>
      <h2>Alumni Drive</h2>
    </div>
    <div class="container">
      <div class="left-column">
        <h3>Athletic Facilities</h3>
        <p>
          The University of Kentucky announced in May of 2017 that Commonwealth Stadium became known as Kroger Field. Home of Kentucky Football. 
          Kentucky baseball moved from Cliff Hagan Stadium to Kentucky Proud Park in 2019. Additonally, an image of Almuni Drive in 2002.
        </p>

        <p>
          The goal of this project is to visualize the UK Athletic facilities along Alumni Drive.
        </p>

        <p>
          Visualizations created from lidar data provided by
          <a href="https://kyfromabove.ky.gov/">KyFromAbove</a> in ArcGIS Pro, Blender and Cesium ion.
        </p>

        <p>
          Page and visualizations created by dandelaneyuky for GEO 409, Department of
          Geography, University of Kentucky. Spring 2023.
        </p>


      </div>
      <div class="right-column">
        <h3>Lidar Vizualization </h3>
        <img src="map1.jpg" alt="UK Football Stadium" width="100%" />
        <p class="caption">UK Football Stadium</p>
        <img src="map2.jpg" alt="UK Athletic Facilities on Alumni Drive" width="100%" />
        <p class="caption">UK Athletic Facilities on Alumni Drive</p>
        <img src="map3.jpg" alt="Alumni Drive in 2002" width="100%" />
        <p class="caption">Alumni Drive in 2002</p>
      </div>
    </div>
  </section>
  <footer>
    <hr />
    <img src="logo-color-400px.png" alt="UKy Arts and Sciences  " width="300px">

  </footer>
</body>

</html>
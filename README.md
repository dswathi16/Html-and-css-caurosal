# Html-and-css-caurosal
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carousel</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <style>
    .bb{
      height: 700px;
      width: 200px;
    }
  </style>
  </head>
<body>
    <div id="carouselExampleCaptions" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-oX_wL2YQ3DuMH9dQ1fjmu2FdInEyHc8byA&amp;s" class="d-block w-100 bb" alt="..." >
            <div class="carousel-caption d-none d-md-block">
              <h5>ARAKU VALLEY</h5>
              <p>The Araku Valley is a hill station near the Odisha state border, about 114 kilometres from Visakhapatnam City you can spend time amidst the beautiful nature.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i0.wp.com/weekendyaari.in/wp-content/uploads/2024/09/caves-1.jpg?resize=800%2C530&amp;ssl=1" jsaction="" class="d-block w-100 bb" alt="..." >
            <div class="carousel-caption d-none d-md-block">
              <h5>BORRA CAVES</h5>
              <p>The Borra Caves is one of the largest cave formations in India and has various famous legends associated with it, lying in the Ananthagiri Mountain Range of the Araku Valley.</p>
            </div>
          </div>
            <div class="carousel-item active">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwgotXlMWbw9U2MmV2CLiuVUOHNecVzEgfkQ&amp;s" class="d-block w-100 bb" alt="..." >
                <div class="carousel-caption d-none d-md-block">
                  <h5>UNDAVALLI CAVES</h5>
                  <p>The Undavalli Caves are date back to the 4-5th century and are related to the rulers of the Vishnukundina dynasty , located about 5 kilometres from the famous Prakasam Barrage.</p>
                </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>

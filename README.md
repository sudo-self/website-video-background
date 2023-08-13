# website-video-background
Website html & CSS 

How to create a video background on a website

x3 files

1. index.html

2. style.css

3. video.mp4


index.html 

  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Video Background</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Roboto&display=swap"
      rel="stylesheet"
    />
  </head>
</html>
<body>
  <div class="home">
    <video autoplay muted loop>
      <source src="ccmatrix.mp4" type="video/mp4" />
    </video>
  </div>
</body>

style.css

*,
::before,
::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Playfair Display, sans-serif;
  background: #f1f1f1;
}

CCmatrix.mp4 (in website root directory)

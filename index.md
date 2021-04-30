<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Fylo data storage component</title>
    <!-- google font  -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <!-- normialze css  -->
    <link rel="stylesheet" href="css/norm.css" />
    <!-- css style sheet -->
    <link rel="stylesheet" href="css/style.css" />

  </head>
  <body>
    <div class="con">
      <main>
        <div class="top">
          <div class="logo">
            <img src="images/logo.svg" alt="" />
          </div>
          <div class="images">
            <div class="img-con">
              <img src="images/icon-document.svg" alt="" />
            </div>
            <div class="img-con">
              <img src="images/icon-folder.svg" alt="" />
            </div>
            <div class="img-con">
              <img src="images/icon-upload.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="end">
          <p class="pfirst">
            You’ve used <span class="span"> 815 GB </span>of your storage
          </p>
          <div class="probar">
            <div class="bar">
              <div class="whitec"></div>
            </div>
            <p class="p">0 GB</p>
            <p class="p">1000 GB</p>
          </div>

          <p class="tooltip">185 <span> GB Left</span></p>
        </div>
      </main>
    </div>
    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Your Name Here</a>.
    </div>

  </body>
</html>

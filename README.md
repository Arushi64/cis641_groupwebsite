<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Syne"/>
    <title>Links website</title>
    <style>
      body {
        background-image: url(https://images.unsplash.com/photo-1534796636912-3b95b3ab5986?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1742&q=80); /* The image used for background*/
        background-repeat: no-repeat; /* Do not repeat the image */
        background-position: center; /* Center the image */
        background-size: cover; /* Resize the background image to cover the entire container */
        font-family: "Syne", sans-serif;
      }

      .container {
        width: 100%;
        padding-right: 15px;
        padding-left: 15px;
        margin-right: auto;
        margin-left: auto;
      }

      .image-container {
        text-align: center;
        width: 100%;
      }

      .links-container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 20px;
      }

      .link {
        min-width: 50% !important;
      }

      @media (min-width: 1200px) {
        .container {
          max-width: 1140px;
        }
      }
      @media (min-width: 992px) {
        .container {
          max-width: 960px;
        }
      }
      @media (min-width: 768px) {
        .container {
          max-width: 720px;
        }

        .link {
          width: 100%;
        }
      }
      @media (min-width: 576px) {
        .container {
          max-width: 540px;
        }
      }

      .w3-yellow,
      .w3-hover-purple:hover,
      .w3-text-black {
        color: rgba(255, 204, 217) !important;
        background-color: rgba(255, 255, 179, 0.3) !important;
      }
    </style>
  </head>

  <body class="w3-white">
    <!-- Content container -->
    <div class="container">
      <!-- Image and name container. Change to your picture here. -->
      <div class="image-container">
        <img
          src="https://media-exp1.licdn.com/dms/image/C4D03AQGzyMQEUhHZ4Q/profile-displayphoto-shrink_800_800/0/1620614194651?e=1671062400&v=beta&t=kpT9Vt0aMzK1HMDLcCydbFk6R4OQwsL8EYBJ_67U-BM"
          class="w3-margin"
          alt="Person"
          max-width="100%"
          height="150px"
          style="border-radius: 60%"
        />

        <!-- Content. Add bio. -->
        <div class="w3-text-white">
          <p class="w3-large"><strong>Portfolio</strong></p>
        </div>

        <!-- Links section 1. Replace the # inside of the "" with your links. -->
        <div class="links-container">
          <a href="aboutme.html" class="w3-button w3-hover-pink w3-large w3-round-xlarge w3-yellow link" target="_blank">About Me</a>
          <a href= "https://www.linkedin.com/in/arushi-sharmaa/" class="w3-button w3-hover-pink w3-large w3-round-xlarge w3-yellow link" target="_blank">LinkedIn</a>
          <a href= "term_project.html" class="w3-button w3-hover-pink w3-large w3-round-xlarge w3-yellow link" target="_blank">Term Project</a>
          <a href="https://pridhvi2297.github.io/Group.html/" class="w3-button w3-hover-pink w3-large w3-round-xlarge w3-yellow link" target="_blank"> Group Game Website</a>
          
        </div>
      </div>
    </div>

      <div class="w3-row">
        <div class="w3-col m8 s12">
          <p>
            <button class="w3-button w3-yellow w3-padding-large w3-round-xlarge">
              <b>READ MORE »</b>
            </button>
          </p>
        </div>
        <div class="w3-col m4 w3-hide-small">
          <p>
            <span class="w3-padding-large w3-right w3-text-white">
              <b>Comments</b>
              <span class="w3-badge w3-yellow">
                3
              </span>
            </span>
          </p>
        </div>
      </div>
      <!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
      <footer class="w3-container w3-center w3-padding-48 w3-margin-top">
        <a class="w3-margin-bottom" href="https://www.w3schools.com/spaces" title="This website was made with W3schools Spaces. Make your own free website today!" target="_blank">
          <img style="filter: brightness(0) invert(1);" src="https://spaces.w3schools.com/logo_4x.png" width="50" height="50">
        </a> 
      <!-- End footer -->
      </footer>
    </div>
  </body>
</html>

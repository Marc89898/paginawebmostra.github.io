<!DOCTYPE html>

<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="index.css">
  <title>NEW WEBSITE</title>
</head>

<body>
  <!-- PAGINA WEB DE TRAJES ELEGANTES --> 
  <div id="nav">
    <nav id="navegacion">
      <a class="btnbtn1" href="index.html">PRINICPAL</a>
      <a class="btnbtn2" href="Secundary.html">SHOP</a>

      <div id="botones1">
        <a class="botones" href="IniciarSesion.html">LOG IN</a>
        <a class="botones" href="register.html">REGISTER</a>
      </div>

    </nav>
  </div>
  <script src="main.js"></script>
  <script src="particles.min.js"></script>




  <div class="letrastitulo">
    <h1>NEW WEBSITE</h1>
  </div>


  <div id="particles-js"></div>


  <!-- APARTADO DEL ABOUT ME-->

  <div class="second">

    <h1 class="primert">ABOUT ME</h1>

    
    <div class="bdt">
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit excepturi aspernatur molestiae minus officia
        soluta ullam iste voluptas culpa voluptate deleniti porro necessitatibus optio fuga accusantium error adipisci,
        officiis omnis?
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit excepturi aspernatur molestiae minus officia
        soluta ullam iste voluptas culpa voluptate deleniti porro necessitatibus optio fuga accusantium error adipisci,
        officiis omnis?
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit excepturi aspernatur molestiae minus officia
        soluta ullam iste voluptas culpa voluptate deleniti porro necessitatibus optio fuga accusantium error adipisci,
        officiis omnis?
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit excepturi aspernatur molestiae minus officia
        soluta ullam iste voluptas culpa voluptate deleniti porro necessitatibus optio fuga accusantium error adipisci,
        officiis omnis?
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit excepturi aspernatur molestiae minus officia
        soluta ullam iste voluptas culpa voluptate deleniti porro necessitatibus optio fuga accusantium error adipisci,
        officiis omnis?

      </p>

    </div>

    <div class="container_slider">
      <div class="container">
        <input type="radio" name="slider" id="item-1" checked>
        <input type="radio" name="slider" id="item-2">
        <input type="radio" name="slider" id="item-3">

        <div class="cards">
          <label class="card" for="item-1" id="selector-1">
            <img src="a.jpg">
          </label>
          <label class="card" for="item-2" id="selector-2">
            <img src="b.jpg">
          </label>
          <label class="card" for="item-3" id="selector-3">
            <img src="c.jpg">
          </label>
        </div>
      </div>
    </div>

    
  </div>

  








  <!-- scripts -->

  <script>
    particlesJS(
      {
        "particles": {
          "number": {
            "value": 230,
            "density": {
              "enable": true,
              "value_area": 800
            }
          },
          "color": {
            "value": "#f2f2f2"
          },
          "shape": {
            "type": "triangle",
            "stroke": {
              "width": 0,
              "color": "#000000"
            },
            "polygon": {
              "nb_sides": 5
            },
            "image": {
              "src": "img/github.svg",
              "width": 100,
              "height": 100
            }
          },
          "opacity": {
            "value": 0.5,
            "random": false,
            "anim": {
              "enable": false,
              "speed": 1,
              "opacity_min": 0.1,
              "sync": false
            }
          },
          "size": {
            "value": 3,
            "random": true,
            "anim": {
              "enable": false,
              "speed": 40,
              "size_min": 0.1,
              "sync": false
            }
          },
          "line_linked": {
            "enable": true,
            "distance": 150,
            "color": "#ffffff",
            "opacity": 0.4,
            "width": 1
          },
          "move": {
            "enable": true,
            "speed": 6,
            "direction": "none",
            "random": false,
            "straight": false,
            "out_mode": "out",
            "bounce": false,
            "attract": {
              "enable": false,
              "rotateX": 600,
              "rotateY": 1200
            }
          }
        },
        "interactivity": {
          "detect_on": "canvas",
          "events": {
            "onhover": {
              "enable": true,
              "mode": "repulse"
            },
            "onclick": {
              "enable": true,
              "mode": "push"
            },
            "resize": true
          },
          "modes": {
            "grab": {
              "distance": 400,
              "line_linked": {
                "opacity": 1
              }
            },
            "bubble": {
              "distance": 400,
              "size": 40,
              "duration": 2,
              "opacity": 8,
              "speed": 3
            },
            "repulse": {
              "distance": 200,
              "duration": 0.4
            },
            "push": {
              "particles_nb": 4
            },
            "remove": {
              "particles_nb": 2
            }
          }
        },
        "retina_detect": true
      }
    )
  </script>

  <div class="cursor"></div>
  <div class="cursor2"></div>
  <script>
    var cursor = document.querySelector(".cursor");
    var cursor2 = document.querySelector(".cursor2");
    document.addEventListener("mousemove", function (e) {
      cursor.style.cssText = cursor2.style.cssText = "left: " + e.clientX + "px; top: " + e.clientY + "px;";
    });
  </script>


</body>

</html>

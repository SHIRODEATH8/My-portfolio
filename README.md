<!DOCTYPE html>
<html lang="en" dir="ltr">
    <head>
        <meta charset="UTF-8" />
        <title>Responsive Portfolio Website</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        
        <!-- Open Graph Meta Tags -->
        <meta property="og:title" content="Portfolio of Arian" />
        <meta property="og:description" content="Check out my portfolio showcasing my skills in 3D design, animation, and web development." />
        <meta property="og:image" content="URL_to_image.jpg" />
        <meta property="og:url" content="http://yourwebsite.com" />
        <meta property="og:type" content="website" />
        
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    </head>
    
  <head>
    <meta charset="UTF-8" />
    <title>Responsive Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>

    <!-- navgaition menu -->
    <nav>
      <div class="nav-container">
          <div class="logo" >
            <span>SHIRODEATH</span>
          </div>
          <div class="links">
              <div class="link"><a href="#">Home</a></div>
              <div class="link"><a href="#">About</a></div>
              <div class="link" ><a href="#">Skills</a></div>
              <div class="link" ><a href="#">Services</a></div>
              <div class="link" ><a href="#">Contact</a></div>
      </div>
      <i class="fa-solid fa-bars hamburg" onclick="hamburg()"></i>
  </div>
      <div class="dropdown">
          <div class="links">
              <a href="#">Home</a>
              <a href="#">About</a>
              <a href="#">Skills</a>
              <a href="#">Service</a>
              <a href="#">Contact</a>
              <i class="fa-solid fa-xmark cancel" onclick="cancel()"></i>
          </div>
      </div>
  </nav>
  <section>
      <div class="main-container">
          <div class="image">
              <img src="main.jpg_00000.jpg" alt="">
          </div>
          <div class="content">
              <h1 data-aos="fade-left" >Hey I'm <span>Arian</span></h1>
              <div class="typewriter" >I'm a <span class="typewriter-text"></span><label for="">|</label></div>
              <p >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugit quasi commodi quia rerum, iste corporis expedita in excepturi nesciunt repellendus quisquam amet provident ad mollitia debitis odit voluptatem necessitatibus tempora.</p>
              <div class="social-links">
                  <a href="https://www.youtube.com/@shirodeath"><i class="fa-brands fa-youtube"></i></a>
                  <a href="https://www.instagram.com/shirodeath/"><i class="fa-brands fa-instagram"></i></a>
                  <a href="#" ><i class="fa-brands fa-linkedin"></i></a>
                  <a href="#" ><i class="fa-brands fa-twitter"></i></a>
              </div>
              <div class="btn" >
                  <button>Hire me</button>
              </div>
          </div>
      </div>
  </section>


  <!-- About Section Start -->

  <section class="about" id="about">
      <div class="content">
        <div class="title"><span>About Me</span></div>
        <div class="about-details">
          <div class="left" >
            <img src="main.jpg_00000.jpg" alt="" />
          </div>
          <div class="right" >
            <div class="topic" >Designing Is My Passion</div>
            <p >
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, porro veritatis pariatur, nobis voluptatem ipsum repellat nemo quisquam error reprehenderit recusandae odio vel, suscipit. Voluptas mollitia accusantium quaerat aspernatur labore dolorum placeat ipsa sint nam perspiciatis eos consectetur veritatis debitis, quis aliquam unde sed maiores sit! Hic molestiae optio iste
              iure earum amet nostrum quaerat facere quae veniam maiores harum iusto aperiam vel inventore illo voluptatibus voluptates quo impedit voluptatum error vitae, omnis praesentium? Aperiam nulla non, nesciunt fuga rem perferendis alias et, temporibus, distinctio culpa unde a laborum libero ducimus. Facilis veniam sit praesentium, voluptatibus sint maxime iusto eaque.
            </p>
            <div class="button" >
              <button>Download CV</button>
            </div>
          </div>
        </div>
      </div>
    </section>


    <!-- My Skill Section Start -->
    <section class="skills" id="skills">
      <div class="content">
        <div class="title" ><span>My Skills</span></div>
        <div class="skills-details">
          <div class="text">
            <div class="topic" >Skills Reflects Our Knowledge</div>
            <p >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus natus tenetur tempora? Quasi, rem quas omnis. Porro rem aspernatur reiciendis ut praesentium minima ad, quos, officia! Illo libero, et, distinctio repellat sed nesciunt est modi quaerat placeat. Quod molestiae, alias?</p>
            <div class="experience">
              <div class="num">5</div>
              <div class="exp">
                Years Of <br />
                Experience
              </div>
            </div>
          </div>
          <div class="boxes">
            <div class="box">
              <div class="topic" >BLENDER 3D</div>
              <div class="per" >90%</div>
            </div>
            <div class="box">
              <div class="topic">UNREAL ENGINE 5</div>
              <div class="per">80%</div>
            </div>
            <div class="box">
              <div class="topic">HTML</div>
              <div class="per" >40%</div>
            </div>
            <div class="box">
              <div class="topic">ADOBE AFTER EFFECTS</div>
              <div class="per">100%</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- My Services Section Start -->
    <section class="services" id="services">
      <div class="content">
        <div class="title" ><span>My Services</span></div>
        <div class="boxes">
          <div class="box">
            <div class="icon">
              <i class="fas fa-desktop"></i>
            </div>
            <div class="topic">Web Devlopment</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box" >
            <div class="icon">
              <i class="fas fa-paint-brush"></i>
            </div>
            <div class="topic">Graphic Design</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box" >
            <div class="icon">
              <i class="fas fa-chart-line"></i>
            </div>
            <div class="topic">3D ANIMATION</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box" >
            <div class="icon">
              <i class="fab fa-android"></i>
            </div>
            <div class="topic">AFTER EFFECTS</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box" >
            <div class="icon">
              <i class="fas fa-camera-retro"></i>
            </div>
            <div class="topic">BLENDER 3D</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box" >
            <div class="icon">
              <i class="fas fa-tablet-alt"></i>
            </div>
            <div class="topic">ICON DESIGN</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Me section Start -->
    <section class="contact" id="contact">
      <div class="content">
        <div class="title" ><span>Contact Me</span></div>
        <div class="text">
          <div class="topic" >Have Any Project?</div>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam neque ipsum corrupti dolores, facere numquam voluptate aspernatur sit perferendis qui nisi modi! Recusandae deserunt consequatur voluptatibus alias repellendus nobis eligendi.</p>
          <div class="button" >
            <button>Let's Chat</button>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section Start -->
    <footer >
      <div class="text">
        <span>Created By <a href="#">ARIAN</a> | &#169; 2024 All Rights Reserved</span>
      </div>
    </footer>

    
    <script src="script.js"></script>
  </body>
</html> 

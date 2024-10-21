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







function hamburg(){
    const navbar = document.querySelector(".dropdown")
    navbar.style.transform  = "translateY(0px)"
}
function cancel(){
    const navbar = document.querySelector(".dropdown")
    navbar.style.transform  = "translateY(-500px)"
}

// for Typewriter effect

const texts = [
    "Web Developer",
    "VFX DESIGNER",
    "3D ARTIST",
    "CGI ARTS"
]

let speed = 100;

const textElements = document.querySelector(".typewriter-text")

let textIndex = 0;
let charcterIndex = 0;

function typeWriter() {
    if(charcterIndex < texts[textIndex].length){
        textElements.innerHTML += texts[textIndex].charAt(charcterIndex);
        charcterIndex++;
        setTimeout(typeWriter, speed); 
    }
    else{
        setTimeout(eraseText, 1000)
    }
}

function eraseText() {
    if(textElements.innerHTML.length > 0){
        textElements.innerHTML = textElements.innerHTML.slice(0,-1)
        setTimeout(eraseText, 50)
    }
    else{
        textIndex = (textIndex + 1) % texts.length;
        charcterIndex = 0;
        setTimeout(typeWriter,500)
    }
}

window.onload = typeWriter;







/* Google Font CDN Link */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  text-decoration: none;
  scroll-behavior: smooth;
}

body{
  width: 100%;
  height: auto;
  background-color: black;
  overflow-x: hidden;
}

/* Custom Scroll Bar CSS */
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
    background: #b74b4b;
    border-radius: 12px;
    transition: all 0.3s ease;
}

::-webkit-scrollbar-thumb:hover {
    background: #b74b4b;
}
/* navbar styling */
nav{
  width: 100%;
  height: 10vh;
  
}

.nav-container{
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.logo{
  color: white;
  font-size: 2rem;
  font-weight: bold;
}

.logo span{
  color: #b74b4b;
  text-shadow: 0 0 10px #b74b4b;
}

.hamburg,
.cancel{
  cursor: pointer;
  position: absolute;
  right: 15px;
  top: 10px;
  color: white;
  opacity: 0;
  pointer-events: none;
  font-size: clamp(2.5rem, 0.5rem + 5vw, 3rem);
}

.nav-container .links{
  display: flex;
}

.nav-container .links a{
  position: relative;
  font-size: 1.2rem;
  color: white;
  margin: 0 20px;
  text-decoration: none;
  font-weight: 550;
  transition: 0.3s linear;
}

.nav-container .links a::before{
  position: absolute;
  content: "";
  bottom: -3px;
  left: 0;
  width: 0%;
  height: 3px;
  background-color: #b74b4b;
  transition: 0.2s linear;
}

.nav-container .links a:hover::before{
  width: 100%;
}

.nav-container .links a:hover{
  color: #b74b4b;
}

.dropdown{
  z-index: 100;
  position: absolute;
  top: 0;
  transform: translateY(-500px);
  width: 100%;
  height: auto;
  backdrop-filter: blur(4px) brightness(40%);
  box-shadow:  0 0 20px black;
  transition: 0.2s linear;
}

.dropdown .links a{
  display: flex;
  color: white;
  text-decoration: none;
  justify-content: center;
  padding: 15px 0;
  align-items: center;
  transition: 0.2s linear;
}

.dropdown .links a:hover{
  background-color: #b74b4b;
}

section{
  width: 100%;
  min-height: 90vh;
}

section .main-container{  

  display: flex;
  justify-content:space-between ;
  padding-left: 100px;
  align-items: center;
}

.main-container .image{
  width: 500px;
  height: 80vh;
  border-radius: 100%;
  overflow: hidden;
  box-shadow: 0 0 50px #b74b4b;
}

.main-container .image img{
  width: 100%;
}

.main-container .image:hover{
  animation: animate 1.5s ease-in-out infinite;
}

@keyframes animate {
  0%{
      scale: 1;
  }
  
  50%{
      scale: 1.05;
  }
  
  100%{
      scale: 1;
  }
}

.main-container .content{
  color: white;
  width: 40%;
}

.content h1{
  font-size: clamp(1rem, 1rem + 5vw, 1.8rem);
}

.content h1 span{
  color: #b74b4b;
  text-shadow: 0  0 10px #b74b4b;
}

.content .typewriter{
  font-size: clamp(1rem, 1rem + 5vw, 2.5rem);
  font-weight: 600;
}

.content .typewriter-text{
  color: #b74b4b;
  text-shadow: 0 0 10px #b74b4b;
}

.content p{
  font-size: clamp(0.4rem , 0.2rem + 9vw, 1rem);
  margin: 10px 0;
}

.social-links i{
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 3rem;
  height: 3rem;
  background-color: transparent;
  border: 0.2rem solid #b74b4b;
  border-radius: 50%;
  color: #b74b4b;
  margin: 5px 15px;
  font-size: 1.5rem;
  transition: 0.2s linear;
}

.social-links i:hover{
  scale: 1.3;
  color: black;
  background-color: #b74b4b;
  filter: drop-shadow(0 0 10px #b74b4b);
}

.content button{
  width: 50%;
  height: 6vh;
  margin: 30px;
  background-color: #b74b4b;
  color: white;
  border: none;
  outline: none;
  font-size: 120%;
  font-weight: 700;
  border-radius: 5px;
  transition: 0.2s linear;
}

.content button:hover{
  scale: 1.1;
  color: #b74b4b;
  border: 2px solid #b74b4b;
  background-color: transparent;
  font-weight: 700;
  box-shadow: 0 0 40px #b74b4b;
}

/* About Section Styling */
/* Those Elements Where We Have Apply Same CSS,
I'm Selecting Directly 'Section Tag' and 'Class'  */

  section .content{
    width: 80%;
    margin: 0px auto;
    font-family: 'Poppins', sans-serif;
    }
  .about .about-details{
    display: flex;
    justify-content: space-between;
    align-items: center;
    }
  section .title{
      display: flex;
      justify-content: center;
      margin-bottom: 40px;
  }
  section .title span{
    color: white;
    font-size: 30px;
    font-weight: 600;
    position: relative;
    padding-bottom: 8px;
  }
  section .title span::before,
  section .title span::after{
    content: '';
    position: absolute;
    height: 3px;
    width: 100%;
    background: #b74b4b;
    left: 0;
    bottom: 0;
  }
  section .title span::after{
    bottom: -7px;
    width: 70%;
    left: 50%;
    transform: translateX(-50%);
  }
  .about .about-details .left{
    width: 45%;
  }
  .about .left img{
    height: 400px;
    width: 400px;
    object-fit: cover;
    border-radius: 12px;
  }
  .about-details .right{
    width: 55%;
  }
  section  .topic{
    color: white;
    font-size: 25px;
    font-weight: 500;
    margin-bottom: 10px;
  }
  .about-details .right p{
    text-align: justify;
  color: white;
  }
  section .button{
    margin: 16px 0;
}
section .button button{
  outline: none;
  padding: 8px 16px;
  border-radius: 4px;
  font-size: 25px;
  font-weight: 400;
  background: #b74b4b;
  color: #fff;
  border: 2px solid transparent;
  cursor: pointer;
  transition: all 0.4s ease;
  }
  section .button button:hover{
    border-color: #b74b4b;
    background-color: #fff;
    color: #b74b4b;
  }
  
  .skills{
    background: black;
    }
  .skills .content{
    padding: 40px 0;
  }
  .skills .skills-details{
    display: flex;
    justify-content: space-between;
    align-items: center;
 }
 .skills-details .text{
   width: 50%;
   }
   .skills-details p{
     color: white;
     text-align: justify;
     }
     .skills .skills-details .experience{
       display: flex;
       align-items: center;
       margin: 0 10px;
       }
.skills-details .experience .num{
  color: white;
  font-size: 80px;
}
.skills-details .experience .exp{
  color: white;
  margin-left: 20px;
  font-size: 18px;
  font-weight: 500;
  margin: 0 6px;
}
.skills-details .boxes{
  width: 45%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.skills-details .box{
  width: calc(100% / 2 - 20px);
  margin: 20px 0;
}
.skills-details .boxes .topic{
  font-size: 20px;
  color: #b74b4b;
}
.skills-details .boxes .per{
  font-size: 60px;
  color: #b74b4b;
}

.services .boxes{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.services .boxes .box{
  margin: 20px 0;
  width: calc(100% / 3 - 20px);
  text-align: center;
  border-radius: 12px;
  padding: 30px 10px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.12);
  cursor: default;
  color: white  ;
  transition: all 0.4s ease;
}
.services .boxes .box:hover{
  background: #b74b4b;
  color: #fff;
}
.services .boxes .box .icon{
  height: 50px;
  width: 50px;
  background: #b74b4b;
  border-radius: 50%;
  text-align: center;
  line-height: 50px;
  font-size: 18px;
  color: #fff;
  margin: 0 auto 10px auto;
  transition: all 0.4s ease;
}
.boxes .box:hover .icon{
  background-color: #fff;
  color: #b74b4b;
}
.services .boxes .box:hover .topic,
.services .boxes .box:hover p{
  color: white;
  transition: all 0.4s ease;
}
.services .boxes .box:hover .topic,
.services .boxes .box:hover p{
  color: #fff;
}
/* Contact Me CSS */
.contact{
  background: black;
}
.contact .content{
  margin: 0 auto;
  padding: 30px 0;
}
.contact .text{
  width: 80%;
  text-align: center;
  margin: auto;
}

footer{
  background: #b74b4b;
  padding: 15px 0;
  text-align: center;
  font-family: 'Poppins', sans-serif;
}
footer .text span{
  font-size: 17px;
  font-weight: 400;
  color: #fff;
}
footer .text span a{
  font-weight: 500;
  color: #FFF;
}
footer .text span a:hover{
  text-decoration: underline;
}
.scroll-button a{
  position: fixed;
  bottom: 20px;
  right: 20px;
  color: #fff;
  background: #b74b4b;
  padding: 7px 12px;;
  font-size: 18px;
  border-radius: 6px;
  box-shadow: rgba(0, 0, 0, 0.15);
  display: none;
}


@media (max-width: 768px) {/* Adjust Styles for mobile */}
  .about .about-details{
    justify-content: center;
    flex-direction: column;
  }
  .about .about-details .left{
    display: flex;
    justify-content: center;
    width: 100%;
  }
  .about-details .right{
    width: 90%;
    margin: 40px 0;
  }
  .services .boxes .box{
    margin: 20px 0;
    width: calc(100% / 2 - 20px);
  }
}

@media (max-width: 900px) {/* Adjust Styles for mobile */}
  .about .left img{
    height: 350px;
    width: 350px;
  }
}

@media (max-width: 968px) {/* Adjust Styles for mobile */}

  nav .logo{
    position: absolute;
    top: 16px;
    left: 15px;
    font-size: 1.5rem;
}

  section .main-container {
    padding-left: 0px;
    display: flex;
    flex-direction: column;
  }
  
  .nav-container .links{
    display: none;
  }
  
  .hamburg,
  .cancel{
    opacity: 1;
    pointer-events: visible;
  }
  
  .main-container .content{
    margin-top: 20px;
      width: 80%;
  }
  
  .social-links i{
    width: 2.5rem;
    height: 2.5rem;
    font-size: 1.5rem;
  }
  
  .main-container .image{
    z-index: -1;
    width: 50%;
      height: 60%;
  }
  
  .skills .skills-details{
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .skills-details .text{
    width: 100%;
    margin-bottom: 50px;
  }
  .skills-details .boxes{
    justify-content: center;
    align-items: center;
    width: 100%;
  }
  .services .boxes .box{
    margin: 20px 0;
    width: 100%;
  }
  .contact .text{
    width: 100%;
}
}

@media (max-width: 500px){/* Adjust Styles for mobile */}
  main-container .image{
        width: 50%;
        height: 60%;
        margin-bottom: 0px;
    }
    
  
  .skills-details .boxes .per{
    font-size: 50px;
    color: #b74b4b;
  }
}
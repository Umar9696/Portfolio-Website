<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- --------- UNICONS ---------- -->
    <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">

    <!-- --------- CSS ---------- -->
    <link rel="stylesheet" href="style.css">


    <!-- --------- FAVICON ---------- -->
    <link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">

    <title>Portfolio | Umar</title>
</head>
<body>
   <div class="container">
    <!-- --------------- HEADER --------------- -->
      <nav id="header">
        <div class="nav-logo">
            <p class="nav-name">Welcome</p>
            <span>.</span>
        </div>
        <div class="nav-menu" id="myNavMenu">
            <ul class="nav_menu_list">
                <li class="nav_list">
                    <a href="#home" class="nav-link active-link">Home</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#about" class="nav-link">About</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#projects" class="nav-link">Projects</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#contact" class="nav-link">Contact</a>
                    <div class="circle"></div>
                </li>
            </ul>
        </div>
        
        
        <div class="nav-menu-btn">
            <i class="uil uil-bars" onclick="myMenuFunction()"></i>
        </div>
      </nav>


    <!-- -------------- MAIN ---------------- -->
    <main class="wrapper">
       <!-- -------------- FEATURED BOX ---------------- -->
       <section class="featured-box" id="home">
          <div class="featured-text">
            
            <div class="featured-name">
                <p>HI👋🏻,there <br>I'm Umar Faruq <br><span class="typedText"></span></p>
            </div>
            
            <div class="featured-text-btn">
                
                <button class="btn blue-btn">Download CV <a href="https://drive.google.com/file/d/1wTCGE3-sLiJ74PaPpBe4voxVAm54svLV/view?usp=sharing"><i class="uil uil-file-alt"></i></button></a>
            </div>
            <div class="social_icons">
                <div class="icon"><a href="https://www.linkedin.com/in/umar-faruq-9079b2192" target="_blank"> <i class="uil uil-linkedin-alt"></i></div></a> 
                <div class="icon"><a href="https://github.com/Umar9696"><i class="uil uil-github-alt"></i></div></a>
                <div class="icon"><a href="https://www.instagram.com/faruq_far?igsh=bXRoa3l0MHZlNnIw"><i class="uil uil-instagram"></i></div></a>
                <div class="icon"><a href="https://wa.me/919742709696"><i class="uil uil-whatsapp"></i></div></a>
                
            </div>
          </div>
          <div class="featured-image">
            <div class="image">
                <img src="Umar.jpg" alt="avatar">
            </div>
          </div>
          <div class="scroll-icon-box">
            <a href="#about" class="scroll-btn">
                <i class="uil uil-mouse-alt"></i>
                <p>Scroll Down</p>
            </a>
          </div>

       </section>
       <!-- -------------- ABOUT BOX ---------------- -->
       <section class="section" id="about">
          <div class="top-header">
            <h1>About Me</h1>
          </div>
          <div class="row">
            <div class="col">
                <div class="about-info">
                    <h3>My introduction</h3>
                    <p>Im a recent graduate with a strong passion for IT Industry. <br>
                        I have completed my Bachelor's in Computer Science & Engineering from GM Institute of Technology Davangere in 2023, I am excited to start my career in IT sector. 
                        My academic journey has equipped me with a solid foundation in Core Java, Web Technologies like HTML, CSS, Java Script, and MySQL.
                    </p>
                   
                </div>
            </div>
            <div class="col">
                <div class="skills-box">
                    <div class="skills-header">
                        <h3>Skills</h3>
                    </div>
                    <div class="skills-list">
                        <span>Core Java</span>
                        <span>HTML/CSS</span>
                        <span>JavaScript</span>
                        <span>MySQL</span>
                        <span>Spring</span>
                        <span>React</span>
                    </div>
                </div>
                <div class="skills-box">
                    <div class="skills-header">
                        <h3>Education</h3>
                    </div>
                    <div class="skills-list">
                        <span>BE(2019-2023) <br>
                            Computer Science and Engineering<br>
                            GM Institute of Technology, Davangere
                            </span>
                        <span>2nd PU(2017-2019) <br>Sir MV PU College,Davangere
                           
                            </span>
                        
                        <span> 10th(2017) <br>
                            Taralabalu Central School,
                            Davangere</span>
                    </div>
                </div>
                <div class="skills-box">
                    <div class="skills-header">
                        <h3>Experience</h3>
                    </div>
                   
                </div>
            </div>
          </div>
       </section>

       <!-- -------------- PROJECT BOX ---------------- -->

       <section class="section" id="projects">
          <div class="top-header">
              <h1>Projects</h1>
          </div>
          <div class="project-container">
            <div class="project-box">
                <i class="uil uil-briefcase-alt"></i>
                <h3>Amazon Clone</h3>
                <label> <div class="featured-text-btn">
                
                    <button class="btn blue-btn"><a href=https://github.com/Umar9696/Amazon-Clone><svg xmlns="http://www.w3.org/2000/svg" width="12" height="16" id="link"><path fill-rule="evenodd" d="M11 10h1v3c0 .55-.45 1-1 1H1c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h3v1H1v10h10v-3zM6 2l2.25 2.25L5 7.5 6.5 9l3.25-3.25L12 8V2H6z"></path></svg></button></a>
                </div></label>
           
          
             </div>
            
            <div class="project-box">
                <i class="uil uil-users-alt"></i>
                <h3>Project</h3>
                <label>DESCRIPTION</label>
            </div>
            <div class="project-box">
                <i class="uil uil-award"></i>
                <h3>Project</h3>
                <label>DESCRIPTION</label>
            </div>
          </div>
       </section>

       <!-- -------------- CONTACT BOX ---------------- -->

       <section class="section" id="contact">
          <div class="top-header">
            <h1>Get in touch</h1>
            <span>contact me here</span>
          </div>
          <div class="row">
             <div class="col">
                <div class="contact-info">
                    <h2>Find Me <i class="uil uil-corner-right-down"></i></h2>
                    <p><i class="uil uil-envelope"></i> Email: faruqdhk886@gmail.com</p>
                    <p><i class="uil uil-phone"></i> Tel: +919742709696</p>
                </div>
             </div>
             <div class="col">
                <form  action="https://formspree.io/f/mrgnpnzg"
                method="POST">
                <div class="form-control">
                    <div class="form-inputs">
                        <input type="text" class="input-field" name="Name" placeholder="Name" autocomplete="off">
                        <input type="text" class="input-field" name="Email"placeholder="Email" autocomplete="off" >
                    </div>
                    <div class="text-area">
                        <textarea placeholder="Message" autocomplete="off"></textarea>
                        
                    </div>
                    <div class="form-button">
                        <button class="btn">Send <i class="uil uil-message"></i></button>
                    </div>
                </div>
             </div>
          </div>
       </section>
        </form>
    </main>


    <!-- --------------- FOOTER --------------- -->
    <footer>
        <div class="top-footer">
            <p>Umar Faruq</p>
        </div>
        <div class="middle-footer">
            <ul class="footer-menu">
                <li class="footer_menu_list">
                    <a href="#home">Home</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#about">About</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#projects">Projects</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </div>
        <div class="footer-social-icons">
            
            <div class="icon"><a href="https://www.linkedin.com/in/umar-faruq-9079b2192" target="_blank"> <i class="uil uil-linkedin-alt"></i></div></a> 
            <div class="icon"><a href="https://github.com/Umar9696"><i class="uil uil-github-alt"></i></div></a>
            <div class="icon"><a href="https://www.instagram.com/faruq_far?igsh=bXRoa3l0MHZlNnIw"><i class="uil uil-instagram"></i></div></a>
        </div>
        <div class="bottom-footer">
            <p>Copyright &copy; <a href="#home" style="text-decoration: none;">Umar Faruq</a> - All rights reserved</p>
        </div>
    </footer>

    </div>




    <!-- ----- TYPING JS Link ----- -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

       <!-- ----- SCROLL REVEAL JS Link----- -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- ----- MAIN JS ----- -->
    <script src="main.js"></script>
</body>
</html>

<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title></title>
  <style>
  :root{
    --body-color: #fe0c9c;
    --color-white: #fe0c9c;

    --text-color-second: rgb(68, 68, 68);
    --text-color-third: rgb(30, 159, 171);

    --first-color: rgb(110, 87, 224);
    --first-color-hover: rgb(40, 91, 212);

    --second-color: rgb(110, 87, 224);
    --third-color: rgb(192, 166, 49);
    --first-shadow-color: rgba(0, 0, 0, 0.1);
    --amos-kim:#ede9f0;
    --lay:#ff4d8a;

}
    *{
      margin: 0;
      padding: 0;
      font-family: 'poppins', sans-serif;
    }
    html{
      scroll-behavior: smooth;
    }
    #layout{
      width: 100%;
      height:3em;
      background-color: #ede9f0;
      text-align: center;
      text-transform: uppercase;
      font-smooth: smooth;
      padding: 50px;
      color: var(--lay);
      text-shadow: 0 0 20px red, 0 -10px 10px blue;
    }
    .layout{
      font-size: 60px;
    }
        .drawer-btn {
      position: fixed;
      top: 20px;
      left: 20px;
      width: 120px;
      height: 120px;
      background-color:white;
      color: red;
        color: blue;
      color:black;
      border: none;
      border-radius: 10%;
      display: flex;
      justify-content: center;
      align-items: center;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
      cursor: pointer;
      z-index: 1000;
    }

    .drawer-btn span {
      font-size: 30px;
      line-height:1 ;
    }

    .drawer {
      position: fixed;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background-color:#8333ea;
      color: white;
      transform: translateX(-100%);
      transition: transform 0.3s ease;
      overflow-y: auto;
      padding: 20px;
      z-index: 999;
      border:3px solid red;
      overdflow:hidden;
    }

    .drawer.open {
      transform: translateX(0);
    }

    /* Drawer content */
    .drawer h2 {
      margin-top: 8;
      color: #00ffff;
    }

    .drawer a {
      text-decoration: none;
      color: white;
      display: block;
      margin: 10px 0;
      padding: 10px;
      border-radius: 60px;
      transition: background-color 0.3s ease;
    }

    .drawer a:hover {
      background-color: whitesmoke;
    }

    /* Overlay */
    .overlay {
      position: fixed;
      top: ;
      left: 100px;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      display: none;
      z-index: 998;
    }

    .facebook.active {
      display: block;
    }
 
  #demo{
    position:relative;
    
    color:#00ff00;
  }
  #mom{
    color:#00ff00;
  }
  #sit{
    color:#00ff00;
  }
  #test, #text1, #text2, #text3, #text4, #text5,#about5, #text6{
    color:#00ff00;
  }
  .hello{
    color:#00ff00;
  }
       .button{
    background-color:blue;
    display:flex;
    over-flow:hidden;
    border:3px solid #ff00ff;
  }
  button:hover{
    background:linear-gradient(360deg,#ffff00);
    inset:5;
    transition: 0.9s;
  }
        body {
      background: #fff;
      color: #222;
      transition: background 0.3s, color 0.3s;
    }
    .dark-mode {
      background: #222;
      color: #fff;
    }
    #darkModeToggle {
      margin-bottom:10px;
      padding: 3px 10px;
      cursor: pointer;
    }
.align{
  text-align: center;
  text-transform: uppercase;
  margin-top: 7em;
  font-size: 40px;
  color: #85097d;
  font-weight: bold;
}
:root{
    --body-color: #faf7f8;
    --color-white: #925ff;

    --text-color-second: rgb(68, 68, 68);
    --text-color-third: rgb(30, 159, 171);

    --first-color: rgb(110, 87, 224);
    --first-color-hover: rgb(40, 91, 212);

    --second-color: rgb(110, 87, 224);
    --third-color: rgb(192, 166, 49);
    --first-shadow-color: rgba(0, 0, 0, 0.1);

}
  body{
    background: var(--body-color);
    
    display:inline-block;
}
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
 .project-container{
    display: flex;
    width: 102%;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
    text-align: center;
    left-margin:60px;
    margin-top: 400px;
}
/*color for 3 boxes*/
.project-box{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 30%;
    height: 550px;
    background: #fe0c9c;
    border-radius: 20px;
    box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
    overflow: hidden;
       left-margin:60px;

}
.project-box:hover{
  background-color: #6262aa;
  transition: 1.5s;
}
.project-box>i{
    font-size: 50px;
    color: #00B5E7;
    margin-bottom: 25px;
}
.project-box label{
    font-size: 15px;
    color: #777;
}
.project-box::after, .contact-info::after{
    content: "";
    position: absolute;
    bottom: -100%;
    background: var(--second-color);
    width: 100%;
    height: 100%;
    transition: .4s;
    z-index: 1;
}
.btn{
    font-weight: 500;
    padding: 12px 20px;
    background:red;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s;
}
.btn>i{
    margin-left: 10px;
}
.btn:hover{
    background: var(--second-color);
    color: var(--color-white);
}

/* ----- GLOBAL ICONS DESIGN ----- */
i{
    font-size: 16px;
}

/* ------- BASE -------- */
body{
    background:red);
}
.container{
    width: 100%;
    position: relative;
    overflow-x: hidden; /* not mandatory */
}

/* ----- NAVIGATION BAR ----- */
nav{
    position: fixed;
    display: flex;
    justify-content: space-between;
    width: 100%;
    height: 90px;
    line-height: 90px;
    background:blue);
    padding-inline: 9vw;
    transition: .3s;
    z-index: 100;
}
.nav-logo{
   position: relative;
}
.nav-name{
    font-size: 30px;
    font-weight: 600;
    color: var(--text-color-third);
}
.nav-logo span{
    position: absolute;
    top: -15px;
    right: -20px;
    font-size: 5em;
    color: var(--text-color-second);
}
.nav-menu, .nav_menu_list{
    display: flex;
}
.nav-menu .nav_list{
    list-style: none;
    position: relative;
}
.nav-link{
    text-decoration: none;
    color: var(--text-color-second);
    font-weight: 500;
    padding-inline: 15px;
    margin-inline: 20px;
}
.nav-menu-btn{
    display: none;
}
.nav-menu-btn i{
    font-size: 28px;
    cursor: pointer;
}
.active-link{
    position: relative;
    color: var(--first-color);
    transition: .3;
}
.active-link::after{
    content: '';
    position: absolute;
    left: 50%;
    bottom: -15px;
    transform: translate(-50%, -50%);
    width: 5px;
    height: 5px;
    background: var(--first-color);
    border-radius: 50%;
}


/* ----- WRAPPER DESIGN ----- */
.wrapper{
    padding-inline: 10vw;
}

/* ----- FEATURED BOX ----- */
.featured-box{
    position: relative;
    display: flex;
    height: 100vh;
    min-height: 700px;
}

/* ----- FEATURED TEXT BOX ----- */
.featured-text{
    position: relative;
    display: flex;
    justify-content: center;
    align-content: center;
    min-height: 80vh;
    flex-direction: column;
    width: 50%;
    padding-left: 20px;
}
.featured-text-card span{
    background: var(--third-color);
    color: var(--color-white);
    padding: 3px 8px;
    font-size: 12px;
    border-radius: 5px;
}
.featured-name{
    font-size: 50px;
    font-weight: 600;
    color: var(--text-color-second);
    margin-block: 20px;
}
.typedText{
    text-transform: capitalize;
    color: var(--text-color-third);
}
.featured-text-info{
    font-size: 15px;
    margin-bottom: 30px;
    color: var(--text-color-second);
}
.featured-text-btn{
    display: flex;
    gap: 20px;
}
.featured-text-btn>.blue-btn{
    background: var(--first-color);
    color: var(--color-white);
}
.featured-text-btn>.blue-btn:hover{
    background: var(--first-color-hover);
}
.social_icons{
    display: flex;
    margin-top: 5em;
    gap: 30px;
}
.icon{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    box-shadow: 0px 2px 5px 0px rgba(0, 0, 0, 0.25);
    cursor: pointer;
}
.icon:hover{
    color: var(--first-color);
}

/* ----- FEATURED IMAGE BOX ----- */
.featured-image{
    display: flex;
    justify-content: right;
    align-content: center;
    min-height: 80vh;
    width: 50%;
}
.image{
    margin: auto 0;
    width: 380px;
    height: 380px;
    animation: imgFloat 7s ease-in-out infinite;
}
.image img{
    width: 380px;
    height: 380px;
    object-fit: contain;
}
@keyframes imgFloat {
    50%{
        transform: translateY(10px);
    }
}
.scroll-btn{
   position: absolute;
   bottom: 0;
   left: 50%;
   translate: -50%;
   display: flex;
   justify-content: center;
   align-items: center;
   width: 150px;
   height: 50px;
   gap: 5px;
   text-decoration: none;
   color: var(--text-color-second);
   background: var(--color-white);
   border-radius: 30px;
   box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.25);
}
.scroll-btn i{
    font-size: 20px;
}

/* ----- MAIN BOX ----- */
.section{
    padding-block: 5em;
}
.row{
    display: flex;
    justify-content: space-between;
    width: 100%;
    gap: 50px;
}
.col{
    display: flex;
    width: 50%;
}

/* -- ## --- RESUABLE CSS -- ## -- */
.top-header{
    text-align: center;
    margin-bottom: 5em;
}
.top-header h1{
    font-weight: 600;
    color: var(--text-color-second);
    margin-bottom: 10px;
}
.top-header span{
    color: #999;
}
h3{
    font-size: 20px;
    font-weight: 600;
    color: var(--text-color-second);
    margin-bottom: 15px;
}

/* ----- ABOUT INFO ----- */
.about-info{
    position: relative;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding-block: 30px 70px;
    padding-inline: 20px;
    width: 100%;
    background: var(--color-white);
    box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px;
    border-radius: 20px;
}
.about-info p{
    text-align: center;
    font-size: 15px;
    color: #777;
}
.about-btn button{
    position: absolute;
    right: 20px;
    bottom: 20px;
    background: var(--first-color);
    color: var(--color-white);
    border-radius: 30px;
}
.about-btn button:hover{
    background: var(--first-color-hover);
}

/* ----- ABOUT / SKILLS BOX ----- */
.skills-box{
    margin: 10px;
}
.skills-header{
    margin-bottom: 30px;
}
.skills-list{
    display: flex;
    flex-wrap: wrap;
    gap: 5px;
}
.skills-list span{
    font-size: 14px;
    background: var(--first-color);
    color: var(--color-white);
    padding: 2px 10px;
    border-radius: 5px;
}

/* ----- PROJECTS BOX ----- */
.project-container{
    display: flex;
    width: 100%;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
}
.project-box{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 30%;
    height: 250px;
    background: var(--color-white);
    border-radius: 20px;
    box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
    overflow: hidden;
}
.project-box>i{
    font-size: 50px;
    color: #00B5E7;
    margin-bottom: 25px;
}
.project-box label{
    font-size: 15px;
    color: #777;
}
.project-box::after, .contact-info::after{
    content: "";
    position: absolute;
    bottom: -100%;
    background: var(--second-color);
    width: 100%;
    height: 100%;
    transition: .4s;
    z-index: 1;
}
.project-box:hover.project-box::after,
.contact-info:hover.contact-info::after{
    bottom: 0;
}
.project-box:hover.project-box i,
.project-box:hover.project-box>h3,
.project-box:hover.project-box>label{
    color: var(--color-white);
    z-index: 2;
}

/* ----- CONTACT BOX ----- */
.contact-info{
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px 30px;
    width: 100%;
    height: 315px;
    background: var(--second-color);
    border-radius: 10px;
    box-shadow: 1px 8px 10px 2px var(--first-shadow-color);
    overflow: hidden;
}
.contact-info>h2{
    color: var(--color-white);
    margin-bottom: 20px;
}
.contact-info>p{
    display: flex;
    align-items: center;
    gap: 10px;
    color: var(--color-white);
    margin-block: 5px;
}
.contact-info p>i{
    font-size: 18px;
}
.contact-info::after{
    background: var(--color-white);
}
.contact-info:hover.contact-info h2,
.contact-info:hover.contact-info p,
.contact-info:hover.contact-info i{
    color: #777;
    z-index: 2;
}

/* ----- CONTACT FORM ----- */
.form-control{
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 100%;
}
.form-inputs{
    display: flex;
    gap: 10px;
    width: 100%;
}
.input-field{
    width: 50%;
    height: 55px;
    background: transparent;
    border: 2px solid #AAA;
    border-radius: 10px;
    padding-inline: 20px;
    outline: none;
}
textarea{
    width: 100%;
    height: 250px;
    background: transparent;
    border: 2px solid #AAA;
    border-radius: 10px;
    padding: 15px 20px;
    outline: none;
    resize: none;
}
.form-button>.btn{
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--second-color);
    color: var(--color-white);
}
.form-button>.btn:hover{
    background: #00B5E7;
}
.form-button i{
    font-size: 18px;
    rotate: -45deg;
}
footer{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    row-gap: 30px;
    background: #F8F8F8;
    padding-block: 40px 60px;
}
.top-footer p{
    font-size: 25px;
    font-weight: 600;
}
.middle-footer .footer-menu{
    display: flex;
}
.footer_menu_list{
    list-style: none;
}
.footer_menu_list a{
    text-decoration: none;
    color: var(--text-color-second);
    font-weight: 500;
    margin-inline: 20px;
}
.footer-social-icons{
    display: flex;
    gap: 30px;   
}
.bottom-footer{
    font-size: 14px;
    margin-top: 10px;
}


/* ----- MEDIA QUERY == 1024px / RESPONSIVE ----- */
@media only screen and (max-width: 1024px){
    .featured-text{
        padding: 0;
    }
    .image, .image img{
        width: 320px;
        height: 320px;
    }
}

/* ----- MEDIA QUERY == 900px / RESPONSIVE ----- */
@media only screen and (max-width: 900px) {
    .nav-button{
        display: none;
    }
    .nav-menu.responsive{
        left: 0;
    }
    .nav-menu{
        position: fixed;
        top: 80px;
        left: -100%;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background: rgba(255, 255, 255, 0.7);
        backdrop-filter: blur(20px);
        width: 100%;
        min-height: 450px;
        height: 90vh;
        transition: .3s;
    }
    .nav_menu_list{
        flex-direction: column;
    }
    .nav-menu-btn{
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .featured-box{
        flex-direction: column;
        justify-content: center;
        height: 100vh;
    }
    .featured-text{
        width: 100%;
        order: 2;
        justify-content: center;
        align-content: flex-start;
        min-height: 60vh;
    }
    .social_icons{
        margin-top: 2em;
    }
    .featured-image{
        order: 1;
        justify-content: center;
        min-height: 150px;
        width: 100%;
        margin-top: 65px;
    }
    .image, .image img{
        width: 150px;
        height: 150px;
    }
    .row{
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 50px;
    }
    .col{
        display: flex;
        justify-content: center;
        width: 100%;
    }
    .about-info, .contact-info{
        width: 100%;
    }
    .project-container{
        justify-content: center;
    }
    .project-box{
        width: 80%;
    }

}

/* ----- MEDIA QUERY == 540px / RESPONSIVE ----- */

@media only screen and (max-width: 540px){
    .featured-name{
        font-size: 40px;
    }
    .project-box{
        width: 100%;
    }
    .form-inputs{
        flex-direction: column;
    }
    .input-field{
        width: 100%;
    }
}
img{
    margin-left: 70px;
    border:5px solid #00ff5b;
    width:780px;
    height:600px;
    transition: 0.8s;
}
img:hover{
    border-radius: 10px 190px 10px 190px;
    transition:0.8s;
    
}
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

/* ----- VARIABLES ----- */

  </style>
</head>
<body>
  <!--layout-->
<div id="layout" class="layout"><p>welcome</p>


<!--drawer-->
 <button class="drawer-btn" onclick="toggleDrawer()">
    <span>&#9776;</span> <!-- Unicode for the "hamburger" menu icon -->
  </button>
   <div class="drawer" id="drawer">
         <h2><footer style="margin-top: 150px;">2025 &copy; AMOS KIM Dev.Team </footer></h2>
<button type="button" onclick="myFunction()"><span>WHITE HACKING</span></button>
  <p id="demo"></p>
      <button type="button" onclick="myFunction()">BLACKHAT</button>
    <P id="mom"></P>
        <button type="button" onclick="myFunctio()">HOSTING</button>
  <p id="sit"></p>
       <button  type="button" onclick="kenya()">CERTIFICATION</button>
  <p id="test"></p>
    <button type="button" onclick="kenya1()">Software Testing Tools</button>
    <P id="test1"></P>
    <button type="button" onclick="kenya2()">CARDING</button>
    <P id="test2"></P>
        <button type="button" onclick="kenya3()">OVPN NET</button>
    <p id="test3"></p>
    <button type="button" onclick="kenya4()">UNLOCKING TOOLS</button>
    <p id="test4"></p>
        <button type="button" onclick="kenya5()"><CHAT ONE</button>
    <p id="test5"></p>
    <button id="darkModeToggle">Toggle Dark Mode</button>
  <div class="content">
   
  </div>
  <button type="button" onclick="enya6()">ANONYMOUS</button>
    <p id="tst6"></p>
    <button type="button" onclick="kenya6()">ABOUT</button>
    <p id="test6"></p>
    </div>
    <div class="facebook" id="facebook" onclick="toggleDrawer()"></div>
            </div>
            <p class="align">the black tech</p>
                                     <section class="section" id="projects">
                <div class="top-header">
                    <h1 style="text-align: center; margin-top: 20px;">Projects</h1>
                </div>
                <div class="project-container">
                    <div class="project-box">
                        <i class="uil uil-briefcase-alt"></i>
                        <h3 style="font-weight: bold;">we provode free internet for all of our customers. Thanks for supportng us as the team tech Black TECH i would like to ammend this to our customer that we are  upgrading our social media to  BLACT TECH KIM  WHERE ARE THE FILE WILL BE CHEAP AND AFFORDABLE make your payment early so that you will not have any issual make the payment using this number</h3>
                        <label>15+ Finished Projects</label>
                    </div>
                    <div class="project-box">
                        <i class="uil uil-users-alt"></i>
                        <h3>book your files early enough so that the payment will not rise we also sell premium account on netflix so you can account on us the netflix is paid ones per year so you dont have to worry about expeiry the netflix come in upgraded way you can download and save to you local storage it support all the android apart from IOS but we are going to upgrade it</h3>
                        <label>25+ Happy Clients</label>
                    </div>
                    <div class="project-box">
                        <i class="uil uil-award"></i>
                        <h3>We provide all network accessory our NET is world wide that we even provide calls that last fo longtime they all affordable and cheap if you fell that you have question you can ask on our platform or for more info contact our agent TOP BOY </p>       </h3>
                        <label>7+ Years in the field</label>
                                  </div>
                </div>
            </section>
                    <pre>
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
            
        </pre>
                        <p style="text-align:center;color:dodgerblue;font-size:50px;">THE BLACK TECH SERVICES</p>
                        <table>
                            <tr>
                                <th></th>
                                <th colspan="60px"></th>
                  <pre>
                      
                      
                      

      
                        <p style="text-align:center;color: #ff00ff;font-size: 100px;font-size: 4em;margin-top: em;"><i> our goals is to satsisfy you are in your dream </i></p>
                        
                        <table>
                            <tr style="display:colum;border:5 solid red;margin:px;" >
                
                
                </main>
                
  <p style="margin-top: 19em;"></p>
                  <div class="row">
                    <div class="col">
                        <div class="about-info">
                            <h3>My introduction</h3>
                            <p>I am well-versed in HTML, CSS and JavaScript , and other cutting edge
                                frameworks and libraries,which allows me to implement interactive features.
                                Additionally, I have experirence working with content management systems (CMS) like
                                WordPress.
                            </p>
                            <div class="about-btn">
                                <button class="btn">Download CV <i class="uil uil-import"></i></button>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="skills-box">
                            <div class="skills-header">
                                <h3>Frontend</h3>
                            </div>
                            <div class="skills-list">
                                <span>HTML</span>
                                <span>CSS</span>
                                <span>Bootstrap</span>
                                <span>JavaScript</span>
                                <span>Vue</span>
                                <span>React</span>
                                <span>Angular</span>
                            </div>
                        </div>
                        <div class="skills-box">
                            <div class="skills-header">
                                <h3>Backend</h3>
                            </div>
                            <div class="skills-list">
                                <span>PHP</span>
                                <span>JAVA</span>
                                <span>Python</span>
                                <span>C++</span>
                            </div>
                        </div>
                        <div class="skills-box">
                            <div class="skills-header">
                                <h3>Database</h3>
                            </div>
                            <div class="skills-list">
                                <span>MySQL</span>
                                <span>PostgreSQL</span>
                                <span>MongoDB</span>
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
                        <h3>Completed</h3>
                        <label>15+ Finished Projects</label>
                    </div>
                    <div class="project-box">
                        <i class="uil uil-users-alt"></i>
                        <h3>Clients</h3>
                        <label>25+ Happy Clients</label>
                    </div>
                    <div class="project-box">
                        <i class="uil uil-award"></i>
                        <h3>Experience</h3>
                        <label>7+ Years in the field</label>
                    </div>
                </div>
            </section>

            <!-- -------------- CONTACT BOX ---------------- -->

            <section class="section" id="contact">
                <div class="top-header">
                    <h1>Get in touch</h1>
                    <span>Do you have a project in your mind, contact me here</span>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="contact-info">
                            <h2>Find Me <i class="uil uil-corner-right-down"></i></h2>
                            <p><i class="uil uil-envelope"></i> Email: amoskim028@gmail.com</p>
                            <p><i class="uil uil-phone"></i> +254 0708865591</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="form-control">
                            <div class="form-inputs">
                                <input type="text" class="input-field" placeholder="Name">
                                <input type="text" class="input-field" placeholder="Email">
                            </div>
                            <div class="text-area">
                                <textarea placeholder="Message"></textarea>
                            </div>
                            <div class="form-button">
                                <button class="btn">Send <i class="uil uil-message"></i></button>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

        </main>


        <!-- --------------- FOOTER --------------- -->
        <footer>
            <div class="top-footer">
                <p>AMOS KIM.</p>
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
                <div class="icon"><i class="uil uil-instagram"></i></div>
                <div class="icon"><i class="uil uil-linkedin-alt"></i></div>
                <div class="icon"><i class="uil uil-twitter"></i></div>
                <div class="icon"><i class="uil uil-github-alt"></i></div>
            </div>
            <div class="bottom-footer">
                <p>Copyright &copy; <a href="#home" style="text-decoration: none;">AMOS KIM</a> - All rights reserved
                </p>
            </div>
        </footer>

    </div>
<img src="Picsart_25-05-27_19-12-06-936.jpg">



    <!-- ----- TYPING JS Link ----- -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <!-- ----- SCROLL REVEAL JS Link----- -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- ----- MAIN JS ----- -->
    <script src="script.js"></script>
  <script>
  /* ----- NAVIGATION BAR FUNCTION ----- */
function myMenuFunction(){
    let menuBtn = document.getElementById("myNavMenu");

    if(menuBtn.className === "nav-menu"){
      menuBtn.className += " responsive";
    } else {
      menuBtn.className = "nav-menu";
    }
  }

/* ----- ADD SHADOW ON NAVIGATION BAR WHILE SCROLLING ----- */
  window.onscroll = function() {headerShadow()};

  function headerShadow() {
    const navHeader =document.getElementById("header");

    if (document.body.scrollTop > 50 || document.documentElement.scrollTop >  50) {

      navHeader.style.boxShadow = "0 1px 6px rgba(0, 0, 0, 0.1)";
      navHeader.style.height = "70px";
      navHeader.style.lineHeight = "70px";

    } else {

      navHeader.style.boxShadow = "none";
      navHeader.style.height = "90px";
      navHeader.style.lineHeight = "90px";

    }
  }


/* ----- TYPING EFFECT ----- */
 let typingEffect = new Typed(".typedText",{
    strings : ["Designer","Youtuber","Developer"],
    loop : true,
    typeSpeed : 100, 
    backSpeed : 80,
    backDelay : 2000
 })


/* ----- ## -- SCROLL REVEAL ANIMATION -- ## ----- */
 const sr = ScrollReveal({
        origin: 'top',
        distance: '80px',
        duration: 2000,
        reset: true     
 })

/* -- HOME -- */
sr.reveal('.featured-text-card',{})
sr.reveal('.featured-name',{delay: 100})
sr.reveal('.featured-text-info',{delay: 200})
sr.reveal('.featured-text-btn',{delay: 200})
sr.reveal('.social_icons',{delay: 200})
sr.reveal('.featured-image',{delay: 300})


/* -- PROJECT BOX -- */
sr.reveal('.project-box',{interval: 200})

/* -- HEADINGS -- */
sr.reveal('.top-header',{})

/* ----- ## -- SCROLL REVEAL LEFT_RIGHT ANIMATION -- ## ----- */

/* -- ABOUT INFO & CONTACT INFO -- */
const srLeft = ScrollReveal({
  origin: 'left',
  distance: '80px',
  duration: 2000,
  reset: true
})

srLeft.reveal('.about-info',{delay: 100})
srLeft.reveal('.contact-info',{delay: 100})

/* -- ABOUT SKILLS & FORM BOX -- */
const srRight = ScrollReveal({
  origin: 'right',
  distance: '80px',
  duration: 2000,
  reset: true
})

srRight.reveal('.skills-box',{delay: 100})
srRight.reveal('.form-control',{delay: 100})



/* ----- CHANGE ACTIVE LINK ----- */

const sections = document.querySelectorAll('section[id]')

function scrollActive() {
  const scrollY = window.scrollY;

  sections.forEach(current =>{
    const sectionHeight = current.offsetHeight,
        sectionTop = current.offsetTop - 50,
      sectionId = current.getAttribute('id')

    if(scrollY > sectionTop && scrollY <= sectionTop + sectionHeight) { 

        document.querySelector('.nav-menu a[href*=' + sectionId + ']').classList.add('active-link')

    }  else {

      document.querySelector('.nav-menu a[href*=' + sectionId + ']').classList.remove('active-link')

    }
  })
}

window.addEventListener('scroll', scrollActive)

    <script>
      function myFunction(){
document.getElementById("demo").innerHTMl=("hwlljhffgggddhjsjdhsjdgfhfhdudhdufhdgdodhfydhryjggg");
  }
    function myFunction (){
    document.getElementById("demo").innerHTML=("<p>Nmap</p>Metasploit<p>Airclack-Ng</p>Wireshark<p></p>open VAS<p>SQLmap</p>NetStumber<p>EttetCap</p><p>maltego</p><p>nikto</p><p>Burp suit</p><p>John The Ripper</p><p>Angry Ip Scanner</p><p>Acunetix</p><p>Invicti(formerly NetSpark)</p><p>intruder</p><p>Remcos conclusion</p>");
  }
      function myFuncti(){
      document.getElementById("mom").innerHTML=("<d2>HACKING TOOLS</d2><p>hacking</p>");
    }
  function myFunctio (){
    document.getElementById("sit").innerHTML=("<p>UNLIMITED SSH</p><p>did.ecitizen.go.ke</p><header>CAPPED HOST</header><p>ncpwd.fuzu.com</p><p>betika.com</p><p>coregateway.app.dlight.com <header>AIRTEL</header><p>viton.com</p><p>104.18.8.127</p></p>");
  }
  function kenya1(){
      document.getElementById("test1").innerHTML=("<p>Test Management Tools</p><p>Cross Browser Testing Tools</p><p>Best ETL Testing Tools</p><p>Mobile Testing Tools</p><p>Regression Testing Tools</p><p>Defect Tracking Tools</p><p>GUI Testing Tools</p><p>Requirements Management Tools</p>");
    }
    function kenya2(){
      document.getElementById("test2").innerHTML=("<p>Identity card 30 USDT per Id</p><p>visa card</p>");
    }
        function kenya3(){
      document.getElementById("test3").innerHTML=("<p>NORD VPN</p>");
    }
    function kenya4(){
      document.getElementById("test4").innerHTML=("TFT TOOLS <P>MdmFix tools</P><p>Pandora</p><p>XTM ADB Tool v1.2 </p><p>MRT Tool V6.0  With 1 Year Free</p><p>XTM ADB TOOL V1.1  www.firmwarebd.com </p><p> FRP MTK </p><p>XTM MRT 3.95</p>");
    }
    function kenya5(){
      document.getElementById("test5").innerHTML=("<p>CHAT ZONE</p>");
    }
    const toggleButton = document.getElementById('darkModeToggle');
    toggleButton.addEventListener('click', () => {
      document.body.classList.toggle('dark-mode');
    });
    function enya6() {
      document.getElementById("tst6").innerHTML=("hello their");
    }
    function kenya6() {
      document.getElementById("test6").innerHTML=("ghhhvvvh");
    }
    function toggleDrawer() {
      const drawer = document.getElementById('drawer');
      const facebook = document.getElementById('facebook');
      drawer.classList.toggle('open');
      facebook.classList.toggle('active');
    }
    </script>

</body>

</html>

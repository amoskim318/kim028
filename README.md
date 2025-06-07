<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />

        <meta name="keywords" content="Document" />

        <meta name="description" content="Your Description..." />
        <title>web</title>
      <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link
            rel="stylesheet"
            href="/resources/swiper-js/swiper-bundle.min.css" />
        <link
            rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" />
        <link rel="stylesheet" href="/resources/css/loader.css" />
        <link rel="stylesheet" href="/resources/css/hamburger.css" />
        <link rel="stylesheet" href="/resources/css/home.css" />
        <link rel="stylesheet" href="/resources/css/about.css" />
        <link rel="stylesheet" href="/resources/css/services.css" />
        <link rel="stylesheet" href="/resources/css/portfolio.css" />
        <link rel="stylesheet" href="/resources/css/comments.css" />
        <link rel="stylesheet" href="/resources/css/contact.css" />
        <link href="/resources/mapbox-gl/mapbox-gl.css" rel="stylesheet" />
        <link rel="stylesheet" href="/resources/css/style.css" />
        <link
            rel="shortcut icon"
            href="/resources/img/favicon.ico"
           type="image/x-icon" />
             <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
     <!-- CSS -->
     <link rel="stylesheet" href="./style.css">
     <!-- Add favicon -->
     <link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="style.css">
	 <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
     <!-- CSS -->
     <link rel="stylesheet" href="./style.css">
     <!-- Add favicon -->
     <link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">
    <style>
      body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      overflow-x: hidden;
      background-color: rebeccapurple;
  
      opacity:5;
      display:flex;
            height:360000px;
    }
    .asa{
      background-color: blueviolet;
      width:1300px;
      height:80px;
    }

    /* Drawer button */
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

    /* Drawer container */
    .drawer {
      position: fixed;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background-color:#000000;
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
      background-color: #444;
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
  #test{
    color:#00ff00;
  }
  #test1{
    color:#00ff00;
  }
  #test2{
    color:#00ff00;
  }
  #test3{
    color:#00ff00;
  }
  #test4{
    color:#00ff00;
  }
  #test5{
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
    background:linear-gradient(360deg,#000000,#ffff00);
    inset:5;
  }
  #test6{
    color:#00ff00;
  }
  #about5{
    color:#00ff00;
  }
        iumg{
            position:relative;
            width:100%; 
            height:400px;
            top:60px;
            border-radius:10px;
            margin-left:px;
            margin-top:80px;
          
        }
        .insi{
            color:dodgerblue;
            text-align:center;
            width:300px;
            height:300px;
            background-color:blue;
            margin-left:220px;
            padding-top:20px;
            border-radius:20px;
            border:3px solid red;
        }
        .in{
            width:400px;
            height:500px;
            background-color:whitesmoke;
            place-content:center;
    justify-content:center;
           place-item:center;
            text-align:center;
            left:200px;
            position:absolute;
        }
        submit{
            background-color:green;
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
        ody{
      font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    text-align: center;
}

.dropdown {
    position:relative ;
    display: inline-block;
    padding-left:300px ;
}

.dropbtn {
    background-color: #4CAF50;
    color: white;
    padding: 10px 200px;
    font-size: 16px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    padding-right:300px ;
    z-index:1 ;
}

.dropdown-content a {
    color: black;
    padding: 12px 306px 100px ;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
    display: block;
}

.selected-fruit {
    margin-top: 20px;
    font-size: 20px;
}

.appl{
    font-size:50px;
   display:flex;
    width:30px;
    
}  
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

/* ----- VARIABLES ----- */
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
    background: white;
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
.uv{
  min-height: 700px;
  z-index: 100px;
  font-weight: 700px;
  margin-top: 2em;
  font-size: 6em;
  text-align: center;
}
                .row{
    display: flex;
    justify-content: space-between;
    width: 100%;
    gap: 50px;
  place-items:center;
    justify-content:center;
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
hd{
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
    background: white;
    box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px;
    border-radius: 20px;
}
.about-info:hover{
  background: linear-gradient( #f869d5, #5650de);
  transition: 9s;
}
img{
  width: 600px;
  height: 900px;
  border-radius: 30px;
}
{
    
    display:flex;
    gap:28px;
    flex-wrap:wrap;
    
  }
  #po{
    text-align:center;
    font-size: 40px;
    
  }
  .box1{
    display: inline-block;
    color:#00ff00;
    background-color:#000;
    width:400px;
    height:500px;
    margin-bottom: 15px;
    padding-top:180px;
    border-radius:20px;
    margin-left: 1pc;
    box-shadow: 0 0 15px #ff00ff,0 15px 15px #ff00ff;
  }
  .box1:hover{
    background: linear-gradient(#00ff00, #ff00ff);
  }
  .box::after{
    background: linear-gradient(#00ff00, #ff00ff);
    z-index: 2;
  }
    </style>
</head>
<body>
    <div class="asa">
        
    </div>
 <button class="drawer-btn" onclick="toggleDrawer()">
    <span>&#9776;</span> <!-- Unicode for the "hamburger" menu icon -->
  </button>
   <div class="drawer" id="drawer">
    <h2><footer style="margin-top: 150px;">2025 &copy; AMOS KIM Dev.Team </footer></h2>
<button style="font-size:13px;padding:17px 140px;" type="button" onclick="myFunction()"><span style="text-align:center;font-size: 50px;">WHITE HACKING</span></button>
  <p id="demo"></p>
      <button style="padding:17px 195px;"type="button" onclick="myFunction()"> <Span style="font-size: 50px;">BLACKHAT</span></button>
    <P id="mom"></P>
        <button style="padding:17px 210px;" type="button" onclick="myFunctio()"><span style="font-size: 50px;">HOSTING</span></button>
  <p id="sit"></p>
       <button style="padding:17px 154px;" type="button" onclick="kenya()"><span style="font-size: 50px;">CERTIFICATION</span></button>
  <p id="test"></p>
    <button style="padding:17px 87px; font-size:50px;" type="button" onclick="kenya1()">Software Testing Tools</button>
    <P id="test1"></P>
    <button style="padding:17px 210px;"type="button" onclick="kenya2()"><span style="font-size: 50px;">CARDING</span></button>
    <P id="test2"></P>
        <button style="padding:17px 210px;" type="button" onclick="kenya3()">O <span style="font-size: 50px;">VPN NET</span></button>
    <p id="test3"></p>
    <button style="padding:17px 112px; font-size:50px;" type="button" onclick="kenya4()">UNLOCKING TOOLS</button>
    <p id="test4"></p>
        <button style="padding:17px 190px;" type="button" onclick="kenya5()"><span style="font-size: 50px;">CHATZ ONE</span></button>
    <p id="test5"></p>
    <button id="darkModeToggle"><span style="font-size: 50px;padding: 24px 129px;">Toggle Dark Mode</span></button>
  <div class="content">
   
  </div>
  <button style="padding:17px 140px;" type="button" onclick="enya6()"><span style="font-size: 50px; padding: 40px;">ANONYMOUS </span></button>
    <p id="tst6"></p>
    <button style="padding:17px 240px;" type="button" onclick="kenya6()"><span style="font-size: 50px;">ABOUT</span></button>
    <p id="test6"></p>
    </div>
    <div class="facebook" id="facebook" onclick="toggleDrawer()"></div>
  <div style="position:absolute;display:flex;margin:24px 10px;font-size:300px;" class="s-icon">
        <a href="about.html">
            <i style="padding:30px 100px;font-size:90px;"class="fa fa-home"></i>
        </a>
        <div class="s-name"></div>
        <div style="display:flex;"class="s-icon">
            <a href="contact.html">
                <i style="padding:30px 100px;font-size:90px;" class="fa fa-user-plus"></i>
            </a>
            <div class="s-name"></div>
            <div  style="display:flex;"class="s-icon">
                <a href="#">
                    <i style="padding:30px 100px;font-size:90px;" class="uil uil-github-alt"></i>
                </a>
                <div class="s-name"></div>
                <div style="display:flex;position:relative;" class="s-icon">
                    <a href="#">
                        <i style="padding:30px 100px;font-size:90px;" class="fa fa-users"></i>
                       
                    </a>
                    <div class="s-name"></div>
                </div>
            </div>
        </div>
    </div>
    <nav>
    <div class="asa"> <p style="text-align: center;">WELCOME </p>
</body>
    
        <p class="abo"></p>
        <br>
    </div>
      
        <p style="color:red;"><br>
        <pre>
            <br />
            
            
            
            
            
            
            
            
            
            <br />
        </pre></p>
        <p style="color:#ff00ff;text-align:center;font-size: 50px;position: relative;top: 50px;gap: 2px;"><i> THE BLACK TECH</i></p>
      
        
                        <
                        </div> 
                        <br>
                        <pre>.             
                        <br />
                        <br />
                        <br />
                        <br>
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        <br />
                        </pre>
                         <section class="section" id="projects">
                <div class="top-header">
                    <h1 style="text-align: center;">Projects</h1>
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
                      
                      
                      
                      
                      
                      
                      
                      
                      
                      
                      
                      
                      
                  </pre>              <div class="container">
        <h1>Select Your Server</h1>
        <div class="dropdown">
            <button id="dropdownButton" class="dropbtn">Select SERVER</button>
            <div id="dropdownContent" class="dropdown-content">
                <a href="#" onclick="selectServer('SSH WEBSOCKET @50 ksh')">SSH WEBSOCKET @50 ksh</a>
                <a href="#" onclick="selectServer('SLOW DNS @50 ksh')">SLOW DNS @50 ksh</a>
                <a href="#" onclick="selectServer('V2RAY @50 ksh')">V2RAY @50 ksh</a>
                <a href="#" onclick="selectServer('vmess @50 ksh ')">VMESS @50 ksh</a>
                <a href="#" onclick="selectServer('UDP  @50 ksh')">UDP@ 50 ksh</a>
                <a href="#" onclick="selectserver('ssh TROJAN @50 ksh')">ssh trojan  @50 ksh</a>
                <a  href="#" onclick="selectServer('Unlimited bandwith @150 ksh')">Unlimited bandwith @50 ksh</a>
            </div>
        </div>
        <div id="selectedServer" class="selected-server"></div>
    </div>
      </tr>
                        </table>
                    
                        <br>
                        <br>
                        <br>
                        
                        <p style="text-align:center;color: #ff00ff;font-size: 100px;font-size: 4em;margin-top: 10em;"><i> our goals is to satsisfy you are in your dream </i></p>
                        
                        <table>
                            <tr style="display:colum;border:5 solid red;margin:px;" >
                
                            </tr>
                            <tr>
                        
                    
                   </tr>
                        </table>
                        <div class="move">
                <p class="uv">OUR PRODUCT </p>

 
  <main class="wrapper">
  <section class="section" id="about">
                <div class="top-header">
                    <h1></h1>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="about-info">
                            <hd> file</hd>
                            <p> <img src="/IMG_20250603_205659.png">
                            </p>
                            <div class="about-btn">
                                <button class="btn">Download file <i 

# web-development-practice
my first vweb development coding practice

 <! DOCTYPE html>
<html>
<head>
     <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
        <title style="color: aquamarine">NYUNWAS COMPUTER TRAINING INSTITUDE.</title>  
    <link href="https://fonts.googleapis.com/family=lobster" rel="stylesheet" href="https://kit.fontawesome.com/58cf4edc3c.js">
    <script src="https://kit.fontawesome.com/58cf4edc3c.js" crossorigin="anonymous"></script>

    <link rel="stylesheet" styletype="text/css" href="style.css">
       
      <style>
        
     body{
     
          background-color:hotpink;
          font-family:monospace;
          color:green;
          }
          
                 h6{
                    font-family:lobster, monospace;
                    text-align:center;
                    font-size: 14px;
                    }  
            h1{
                
                text-align: center;
                text-underline-position: below;
                color:white;
              }
        
        .navbar{
            color:red;
            font-size: 10px;
            text-align:left;
               }
        *{
            padding: 0;
            margin: 0;
            text-decoration: none;
            list-style: none;
            box-sizing: border-box;
        }
        
        nav{
            
            background:LightBlue;
            height: 80px;
            width: 100%;
        }
        
        label.logo{
            
            color: Red;
            width: 35px;
            height: 20px;
            padding: 0 100px;
            tex-align: right;
                }
        
      
        nav ul l1 a{
            
            color: white;
            font-size: 17px;
            padding: 7px 13px;
            border-radius: 7px;
            text-transform: uppercase;
            padding-right: 0px;
            text-align: right;
        }
          
        a.active,a:hover{
            
            background: pink;
            transition:  .5s;
            
              }
          
       .header{
                   color:white;
                   padding-left:2px;
                   text-align:left ;
               }
          
       .checkbtn{
                font-size: 30px;
                float: right;
                line-height: 80px;
                margin-right: 40px;
                color:red;
                cursor: pointer;
                display:inline-flex;
                text-align: right;
                }
          #check{
              
              display: none;
          }
          
        .logo{
            font-size:30px;
            color: white;
            background: url(health.cdr);
              }
          
          .picture{
              border-radius: 50%;
              border-color: aquamarine;
              position:flexible;
              width: 300px;
              height: 300px;
              border-width: thick;
              padding: 50px;
              place-content: flex-end;
              padding: 70px 30px;
              text-align: center;
              }
          
          .log{
              
              display:block;
              background-color:blue;
              color: white;
              top: 30%;
              left: 50%;
              position: absolute;
              transform:translate(450pX);
              margin-left:auto;
              margin-top: 50px;
              text-align:right;
              }
          
          h2{
              display: block;
              color: white;
              text-align: center;
          }
          div.c{
              display:block;
              color: white;
              top: 20%;
              left: 50%;
              position: absolute;
              transform:translate(245pX);
              margin-left:auto;
              margin-top: 50px;
              text-align:right;
                }

         
            selection{
                
                background: url(project/custom.jpg) no-repeat;
                background-size: cover;
                height: calc(100vh-80px);       
            }
          
          @media screen and (max-width:1024px){
             nav ul l1 a{
                 width: 60px;
                  
              }
          }

          
          @media screen and (max-width:133px){
             nav ul l1 a{
                 position: absolute;
                 right: 0px;
                 height: 50vh;
                 top: 8vh;
                 display: flex;
                 flex-direction: column;
                 float: right;
                 text-align: left;
              }
              .log{
                  display:block;
                  border-top:0px;
                  flex-direction:column;
                  position: absolute;
                  text-align: center;
              }

          }

        </style>
    
    </head>
    
    <body>
    <p style="color: black; animation-delay:2s;"><h1><b>  WELCOME TO OUR ITC TRAINING CONSULTANCY</b></h1></p>
        <p><i><h6 style="background-color: blue; color: white;">We are hightly excited to have you here, feel free and learn conveniently with us. we promise to assist you get in to your web development and other IT career.</p></i></h6>
    </body>
        <body>
            <nav class="navbar">

                <div class="header">
                <div class ="header-right">
                <a href="NE.html" class="logo">TMD</a>

                <input type="checkbox" id="check">
                <label for="check" class="checkbtn">
                <i class="fa-solid fa-bars" ></i>
            <div>
                <div id="navmenu">
        <ul>
          <section>

            <l1><a class="active"><a href="mark.html"> home </a></a></l1>
            <l1><a href="styl.html" class="nav-link">About</a></l1>
            <l1><a href="style.html" claa="nav-link">Contact Us</a></l1>
            <l1> <a href="domba.html" class="nav-link" aria-flowto="project/TS3.jpg" class="nav-link">Our Programs</a></a></l1>
            </section>
        </ul>
            </nav>
                <section>
                    <img src="project/TS2.jpg" width=400px; height=400px;>
                    <img src="project/TS1.jpg" width=400px; height=400px;>
                    <img class="picture" src="project/TS3.jpg" width=400px; heigh=400px;>
                    
                </section> 
                    
                <section>
                    <div class="c"><h2> DO you have an account with us ?<br> click on the link below to long in.</h2></div><br>
                        <a class="log" href="login.html">LOGIN HERE </a> 
                </section>
                    <script src="script.js"></script>
        </body>
   </header>
             
    </main>

    </htlm>

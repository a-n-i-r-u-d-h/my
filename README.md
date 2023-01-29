<!DOCTYPE HTML>
<html>
  <head>
    <title>Protifoilo</title>
  </head>
  <style>
    html{
      margin:0;
        padding:0;
    }
    header{
      width:100vw;
      height:80px;
      position:scroll;
      top:0;
      background-color:white;
      border-bottom: 1px solid red;
      z-index:1;
       }
    nav{
      height: 100%;
      display:flex;
      justify-content: space-evenly;
      align-items:center;
      overflow:hidden;
    }
    nav-link{
      text-transform:uppercase;
      color:orange;
      font:20px sans-serif;
      padding:100% 25px;
    }
    nav-linkhover{
      background-color:red;
     color:white;
    }
    body{
      font-family:Arial,Helvetica,sans-serif;
      font-size:20pt
      
    }
    h1{
      font-size:25pt
     color:orange
        text:aligin: center;
      padding; 18px 0 18px 0;
      margin:0 0 10px 0;
    }
    h1 span {
      border: 1px solid orange red;
      padding: 10px
    }
    p {
      padding:0;
      margin:0;
    }
    img-circle{
      border:3px solid white;
      border-radius: 50%;
    }
    section{
      background-color:#fff;
      padding:15px;
      margin-bottom:10px;
      border-radius:10px;
    }
    #header{
      background-image: url("https://uploads-ssl.webflow.com/5e4dfa5d58d02b574c094981/5e61b936452770f1cc437223_Render%20Engin%10Blur.jpg");
      background-size: cover;
    }
    #header img{
      display: block;
      width: 80px;
      height: 80px;
      margin: auto;
    }
    #header p{
      font-size:25pt;
      color: red;
      padding-top: 5px;
      margin:0;
      font-weight: bold;
      text-align: center;
    }
    selected{
      background-color:#f36f48;
      font-weight:bold;
      color:white;
    }
    gallery{
      display: flex;
      flex-wrap: wrap;
      /*Compensate for excess margin on outer gallery flex item*/
      margin:-1rem -1rem;
    }
    gallery-item{
      /*Minimumwidth of 24rem and grow to fit avalaible space*/
      flex:1 0 24rem;
      /* Margin value should be half of grid-gap value as margin anflex items don`t callapse*/
      overflow: hidden;
    }
    gallery-image{
      display: block;
      width: 100%;
       height: 100%;
      object-fit: cover;
      transition: transform 400ms ease-out
    }
    gallery-image:hover{
      transform: scale( 1.15)
    }
    li{
      margin-bottom: 15px;
      font-weight:bold;
    }
    progress{
      width:70%;
       height: 20px;
      color: orange;
      background: #000;
    }
    hr{
       border:0;
      height:1px;
      background:#f36f48;
    }
    form{
      text-align:center;
      margin-top: 0;
    }
    submit{
      background-color: orange;
      padding; 12px 45px;
      border-radius:5px;
      cursor:#ffffff;
      border:none;
      outline: none;
      margin:0;
      font-weight:bold
    }
    submit:hover{
      background-color:black;
    }
    textarea{
           height:100px;
    }
    input,textarea{
      margin-bottom:10px
        font-size:11pt;
      padding: 15px 10px 10px;
       border : 1px solid #cecece;
      background-color:#efefef;
        color:#787575;
      border-radius:5px;
      width:70%;
      outline:none;
    }
    face{
      transform:scale(0.4);
      margin:0 auto;
      display:block;
      margin-top:-35px
     margin-bottom:-25px;
    }
    #contacts img{
    height: 50px;
      width: 50px;
      margin-left: 7px;
      margin-right:7px;
    }
    #contact a{
      text-decoration:none;
    }
    #contacts img:hover{
      opacity: 0.8;
    }
    #contact{
      text-align: center;
    }
    copyrigt:{
       font-size: 18px;
         text-align: center;
      padding-bottom: 10px;
      color:black;
    }
  </style>
  <body>
    <header>
      <nav id="navbar">
        <a herf="#" class="nav-ink">ABOUT ME</a>
        <a harf="#"work class="nav-link">My project </a>
        <a harf="#"skills class="nav-link">My skills</a>
        <a harf="#"contact class="nav-link">Contact me</a>
        </nav>
    </header>
    <!--header image star-->
    <div id="header" class="section">
      <img alt="" class="https://cdn.ces.tech/ces/media/topics/space-tech/space-770x616.png" >
      <!--change the srcurl and add your image here-->
      <p>student name goes  here with image in above circle</p>
      <!--write the student name in the above page -->
      <!--header image end-->
      <!--about me section start-->
 <!--header image end-->

<!--About Me section start-->

<div class="section"> 
  <h1 id=#><span> About Me</span></h1>

<p>

Hey! I'm <b> Shraddha B Tiwari</b> I am a 'Secretary' in shiv shakti chritable trust I am the chief editor of s Bharat channel I am  self employee of Shiv Shakti Enterprises I am the self employee of Shraddha Enterprises I would like to do work in Sanatan Dharm I would like to work for humanity my ambition is to bring my news channel as India's best news channel I obey my mother my father and my teacherI like to give social serviceplease support my news channel and my ambition to achieve it thank you.

<p>

<!-- fill the above paragraph tag with information about you-->
  
  </div>

<!--About Me section and -->

<!--My projects section start--> <div class="section">

<h1 idework><span>My Projects</span></h1>

<div class="gallery">

<div class="gallery-item">

<img class="gallery-image" src="https://yt3.googleusercontent.com/ytc/AL5GRJUgm6chmCItOwdvrlWZ8uTliunC_2SPUmAqIkKh=s176-c-k-c0x00ffffff-no-rj-mo" heigth="200" width="400">

</div>

<div class="gallery-item">

<img class="gallery-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxtZzo1VF5G4oYzgWT1r63m7pqhNITaEDAAQ&usqp=CAU" heigth="200" width="400">


</div>

<div class="gallery-item">

<img class="gallery-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRR3I2qL5e6JH_IKgfa-tg93FtHJh7T1jhohw&usqp=CAU"heigth="200" width="400">

</div>

<div class="gallery-item">

<img class="gallery-item" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSSYZ0E6g5vOnMGTx8iKif9HEG_vLBIe8HSgg&usqp=CAU"heigth="200" width="400">

<div class="gallery-item">

<img class="gallery-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjhp9F7aTH3zbrFanYfh__hO-h5P_yNGbIvA&usqp=CAU"heigth="200" width="400">



</div>
      <div class="section">
        <h1 id skills><span>My skills</span></h1>
          <ul>
            <li> Hindi M.A<br/>
              <progress min="0" max="100"value="100"></progress>
              </li>
              <li>ENGLISH Speaking course<br/>
              <progress min="0" max="100"value="20"></progress>
            </li>
                <li> Journalist course<br/>
              <progress min="0" max="100"value="100"></progress>
                  </li>
            </ul>
              <div class="section">
                <h1 id="contact"><span>Contact me</span><h1>
                  <form action="mailto:someone@example.com" method="post"enctype="text/plain"> 
                    <input name="name" placeholder="Name"type="text" required/><br/>
                    <input name="email" placeholder="Email"type="email" required/><br/>
                      <textarea name="message" placeholder="Message" required/><br/ >   
                    <input type="submit"value="SEND" class="submit"/>
                    </form>
                  </div>
                  <div class="section" id="contact">
                    <h1><span> Follow Me </span></h1>
                    <div>
                      <a herf="http://Facebook.com/">
                       <img alt="Facebook" src="https://wwww.sololearn.com/Upload/icons/facebook.png"/> 
                      </a>
                       <a herf="http://twitter.com/">
                   <img alt="Twitter" src= "https://wwww.sololearn.com/Upload/icons/twitter.png"/> 
                      </a>
                    </div>
                  </div>
                  <div class="copyright">
                    &copy;2023 A sincere web devloper.All right reserved
                  </div>
                      
                  
  </body>
</html>

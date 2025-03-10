
# Simple-profile-card
// .html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile card</title>
    <link rel="stylesheet" href="profile card.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>
<body>
    <div class="container">
   <div class="card">
   <div class="circle"> <img src="successful-businessman-photo-removebg-preview.png" alt=""></div>
   <div class="details">
    <h3  class= "name">Vinny Anand Dinakaran
        
    </h3>
    <p  id="desig"   style="position: relative; top: 75px; right: 95px; font-size: 13px; color: black;">
        Front-End Developer </p><br>
        <p class="line"><b>_________</b></p>

    <p class="about">I’m a web developer with years of experience<br>
       in creating and managing websites.
      My skills  <br>include coding
         in HTML,CSS, and JavaScript.</p>
   </div>
    <div class="icons">
        <a href=""><i class="fa-brands fa-twitter"></i></a>
        <a href=""><i class="fa-brands fa-facebook"></i></a>
        <a href=""><i class="fa-brands fa-youtube"></i></a>
        <a href=""><i class="fa-brands fa-instagram"></i></a>
    </div>

   </div>
    </div>
</body>
</html>






// .css code

@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-align: center;
    justify-content: center;
   
}
.container{
    width: 100%;
    height: 100%;
    min-height: 100vh;
    text-align: center;
    justify-content: center;
   
}
 .container > .card{
    width: 28%;
    height: 34vh;
    background: linear-gradient(135deg, #7FA6E8, #C9FEFF);
    position: relative;
    top:190px;
    left: 35%;
   
   
}
.circle{
    width: 23%;
    height: 15vh;
    background-color: #EAEAEA;
    border-radius: 10px;
    position: relative;
    top: 55px;
    left: 15px;
}
.circle > img{
    width: 20vh;
    height: 14vh;
    position: relative;
    top: 7px;
}
.details{
    text-align: center;
    justify-content: center;
    color: whitesmoke;
    position: relative;
   bottom: 120px;
    left: 80px;
}
.name{
    font-family: Arial,  sans-serif;
     color: #E63946;
     font-size: medium;
     position: relative;
     top: 75px;
     right: 65px;
}
.line{
    position: relative;
    top: 42px;
    right: 113px;
    color: #EAEAEA;
}
.about{
    font-size: 12px;
    position: relative;
    right: 40px;
    top: 45px;
     color: black;
}
.icons{
    position:relative;
    bottom: 50px;
    left: 20px;
    display: flex;
    gap: 25px;
}
a:hover{
   opacity: 0.2;
   width: 2pc;
}
.card:hover{
    box-shadow: 10px 10px 5px 0px rgba(164,219,232,0.75);
-webkit-box-shadow: 10px 10px 5px 0px rgba(164,219,232,0.75);
-moz-box-shadow: 10px 10px 5px 0px rgba(164,219,232,0.75);
}
@media (max-width: 600px) {
    .container {
        width: 100%;
        min-height: 20vh;
    }
    .card{
        width: 40%;
        min-height:15vh ;
    }
    .circle{
        width: 23%;
        height: 10vh;
    }
    .circle > img{
        width: 10vh;
        height: 8vh;
    }
    .name, .about{
        font-size: 8px; 
    }
    .icons{
        display: flex;
        gap: 8px;
    }
    

}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Codewithrahul Happy Holi 2024</title>

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <nav class="navbar navbar-expand-lg fixed-top">
      <div class="container">
          <a class="navbar-brand text-white" href="#">
           <div class="log">Jai Shree Ram </div>
          </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" >
        <span class="navbar-toggler-icon"></span>
      </button>
   
      <div class="collapse navbar-collapse" >
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="btn btn-light" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#">About</a>
            </li>
           
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              More
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        
      </div>
      </div>
    </nav>

    <div class="myinfo">
      <h1 class="holi">Hey there!</h1>
      <h1>i am Rahul</h1>
          <p>Wishing you and your loved ones a very colourful Holi<br>May you forget all your worries and enjoy this day to the fullest.<br> <h2 class="hue">Happy Holi!</h2></p>

              <a href="#" class="btn btn-danger mr-3 hue">contact</a>
              <a href="#" class="btn btn-light">Login</a>
      </div>

      <video autoplay loop play-inline muted  >
          <source src="Happy Holi 2024 By CWS.mp4">
              video is not load
          </video>
<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    user-select: none;
    font-family: poppins, sans-serif;

}
body{
    overflow: hidden;
    background: rgb(0, 0, 0);
    background-size: cover;
    
}
.navbar{
    margin-top: 10px;
}
.logo{
    width: 40px;
    height: 40px;
    filter:drop-shadow(0 0 10px white);
}

.myinfo
{
    position: relative;
    top: 200px;
    left: 150px;
    width: 500px;
    color:white;
    text-shadow: 5px 5px 10px rgba(0, 0, 0, 0.73);
   


}

.nav-link
{
    color:white;
}
.nav-item{
color: white;
margin-left: 20px;
}
.btn{
    border:none;
    color:white;
    background: transparent;
    border: 1px solid white;
    border-radius: 50px;
}
.holi{
   
    color:transparent;
    background-clip: border-box;
    color: whitesmoke;
    /* list-style: none; */
    font-size: 20px;
    font-weight: bold;
    /* position: relative; */
    /* top: 0; */
}
h1{
    font-size: 90px;
    font-weight: bold;
}

.nav-link:hover
{
   color: rgb(255, 0, 0);
   text-shadow: 0 0 20px black;
}
video
{
    position: absolute;
    left:00px;
    bottom: 00px;
    z-index: -2;
    height: auto;
    /* width: 100%; */
    min-width: 100%;
    min-height: 100%;
    filter: blur(100);
}
.hue{
    color: rgb(240, 81, 2);
    
    font-weight: bold;
    animation: hue 5s infinite;
}

@keyframes hue{
    0%{
        -webkit-filter: hue-rotate(0deg);
    }
    100%{

        -webkit-filter: hue-rotate(700deg);
    }
}
</style>
  
</body>

</html>

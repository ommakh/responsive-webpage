# responsive-webpage
responsive web page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive </title>
  
</head>
<style>
  *{
    margin: 0cm;
    padding: 0%;
    box-sizing: border-box;
}
a{
  text-decoration: none;
}
header{
    height: 100vh;
    width: 100vw;
    background-image: url("ghar\ 5.jfif");
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    background-size: cover;
    justify-content: center;
    background-position: bottom;
}
.header-content h2{
  font-size: 4vmin;

}

.firstimg{
  height: 30vh;
  width: 30vw;
  display: flex;
  background-repeat: no-repeat;
  display: flex;
  align-items: center;
  background-size: cover;
  justify-content: center;
  background-position: bottom;

}
.header-content{
  margin-bottom: 150px;
  color: antiquewhite;
  text-align: center;

}
.header-content{
  font-size: 4vmin;
}
.line{
  width: 150px;
  background-color:red;
  margin: 10px auto;
  border-radius: 5px;

}
.header-content h3{
  font-size: 7vmin;
  margin-top: 50px;
  margin-bottom: 30px;

}
ul{
  list-style: none;
}
.navbar{
  position: absolute;
  top: 0;
  bottom: 0;
  display: flex;
  width: 100%;
  justify-content: space-between;
  padding: 30px;
  color: azure;
}
.navlinks{
  margin: 0 30px auto;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;

  
}
li{
  margin: 0 20px;
}
.menubtn{
  position: absolute;
  cursor: pointer;
  display: none;
  top: 30px;
  width: 40px;
  right: 30px;
}
.explore{
  padding-top: 100px;
  padding-bottom: 100px;
  text-align: center;
}
.explore .p{
  padding-bottom: 10px;
}
.ctn{
  padding: 8px 15px;
  border-radius: 30px;
  background-color: red;
  color: white;

}
.tour .image-gallery{
  display: flex;
  flex-wrap: wrap;
  align-items: center;

}
.image-gallery img{
 width: 250px;
 margin: 10px;
 align-items: center;
 max-width: 300px;
}
.tour .row .col{
  width: 50%;

}
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}
.content-col{
  width: 40%;
}
.content-col{
  font-size: 7vmin;
  color: #484872;


}
.content-col p{
  padding: 0;
  margin: 30px auto;

}
.image-col{
  width: 60%;
}
.htag{
  padding-bottom: 20px;
}
.headline{
  text-align:right ;
  
}
.footer{
  padding-top: 40px;
  width: 100%;
  height: 200px;
  margin: 0%;
  background: #484872;
  text-align: center;
}
.footer p{
  color: white;
  margin: 20px auto;
   

}


@media only screen and (max-width:500px) {
  .menubtn{
    display: block;
  }
  .navbar{
  padding: 0;
  color: black;
  }

  .logo{
    position: absolute;
    top: 30px;
    left: 30px;
  }
  .navlinks{
    flex-direction: column;
    width: 100%;
    height: 100vh;
    justify-content: center;
    background: white;
    margin-top: -800px;
    transition: all 0.5s ease;
    display: inline-flex;


  }
  .mobilemenu{
    margin-top: 0px;
    border-bottom-right-radius: 30%;
    border-bottom-left-radius: 30%;
  }
  .tour .image-gallery{
  display: flex;
  flex-wrap: wrap;
  align-items: center;

}
.image-gallery img{
 width: 25px;
 margin: 10px;
 align-items: center;
 max-width: 30px;
}


}
</style>
<body>
  <nav class="navbar">
    <h1 class="logo">ADVENCTURE</h1>
    <ul class="navlinks">
      <li>HOME</li>
      <li><a href="gallary.html"></a> GALLARY</li>
      <li>CONTACT</li>
      <li>ABOUT</li>
      
    </ul>
    <img class="menubtn" src="meny btn 2.png" alt="menu button">

  </nav>

  <header>
    <div class="header-content">
      <h3>Tourism and tours</h3>
      <div class="line"></div>
      <h1>A wonderfull gift</h1>
    </div>
  </header>
  <div class="explore"> 
    <h1 class="htag"> EXPLORE THE WORLD</h1>
    <a href="#" class="ctn">learn more</a>
  </div>
  
    <div class="col image-col">
      <div class="image-gallery">
        <img src="ghar.1.jfif">
        <img src="ghar.2.jfif">
        <img src="ghar.3.jfif">
        <img src="ghar4.jfif">
        <br>
        <section class="tour">
          <div class="row">
            <div class="col "></div>
            <h1 class="headline">UPCOMING <br>
              <p><i>We have very nice destination to visit.<br>
                Our upcoming destination are Germany,France,Itly,Rome
              </i></p>
      
            </h1>
          </div>
  
      </div>
  
    </section>

      </div>
      
  <section class="footer">
    <footer>
      <h1><p> all rights belong to om makh </p></h1>
    </footer>

  </section>
 
</body>
<script>
  const menubtn = document.querySelector('.menubtn')
  const navlinks = document.querySelector('.navlinks')
  menubtn.addEventListener('click',()=>{
    navlinks.classList.toggle('mobilemenu')
  })


</script>
</html>

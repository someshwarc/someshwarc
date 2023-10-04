<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        header{
            height: 100vh;
            background: url(./carousel-1.jpg);
            background-size: cover;
            color: white;
            font-size: 40px;
            
        }
        header::after{
            content: "";
            position: absolute;
            background:url(./overlay-bottom.png);
            z-index: 1;
            width: 100%;
            height: 15px;
            bottom: 0;
        }
        li{
            display: inline;
            padding: 10px;
            font-size:20px;
        }
        ul{
            position: absolute;
            right: 20px;
            top: 10px;
        }
   
        h2{
            color: white;
            padding: 20px;
            left: auto;
            text-shadow: 5px 8px 5px rgb(24, 21, 21);
        }
        a{
            color: white;
            list-style: none;
            text-decoration: none;
        }
        a:hover{
            color: goldenrod;
            transition: all;
        }
        .title{
            position: absolute;
            top: 40%;
            left: 40%;
        }
        .title h4{
            font-size: 30px;
            font-weight: bold;
            color: goldenrod;
            
        }
        .cof h3{
            position: absolute;
            font-size: 90px;
            font-weight: bold;
            color: white;
            left: -20%;
            text-shadow: 3px 3px 3px rgb(10, 10, 10);
        }
        .sin h5{
            position: fixed;
            color: white;
            top: 60%;
            left: 42%;
            font-size: 40px;
            text-shadow: 4px 4px 3px red;

        }
        .containar {
            height: 100vh;

        }
        .section-title {
            position: relative;
            padding: 80px 0 35px 0;
            text-align: center;

        }

        .section-title::after {
            position: absolute;
            content: "";
            width: 2px;
            height: 70px;
            top: 0;
            left: 50px;
            margin-left: 1px;
            background: rgb(242, 163, 5);
        }
       


    .Since1950{position:absolute;
               margin:300px;
        
    
    }
    </style>
</head>
<body>
    <header>
        <nav>
        <h1>KOFFEE</h1>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Service</a></li>
            <li><a href="#">Menu</a></li>
            <li class="nav item dropdown"><a class="dropdown-toggle" href="#">Page</a>
    </nav></header>

        <div class="title cof sin ">
            <h4>We Have Been Serving</h4>
            <h3>COFFEE</h3>
           <div class="Since 1950">* Since 1950 *</div>
        </div>
           <div class="section-title">
       <div class="container">
            <h4 class="text-primary text-uppercase" style="letter-spacing: 5px;">ABOUT US</h4>
            <h1>Serving Since 1950</h1>
            </div><br><br>
            <section>
                
        <div class="section1">
          <h1 style="text-align: left;font-size: 30px;">Our Story</h1><br>
         <p><h3> Eos kasd eos dolor vero vero
            lorem stet diam rebum. Ipsum amet sed vero dolor sea
            Takimata sed vero vero no sit sed, justo clita duo
            no duo amet et, nonumy kasd sed dolor eos diam lorem eirmod. Amet sit 
            amet amet no. Est nonumy sed labore eirmod sit magna. Erat at est justo
             sit ut. Labor diam sed ipsum et eirmodul</p></h3></section>
        
           <button class="B1">Learn More</button>
            <img class="margin-bottom" src="./about.png" width="400px"height=400px>
            
        </div>
        <div class="section2">
    </div>
    <div class="box3"></div><h1 style="text-align: left;font-size: 35px;"></h1><br>
 
        <h1>Our Vision</h1><br>
        <p> lorem justo sanctus clita. Erat lorem labore ea,
             justo dolor lorem ipsum ut sed eos, ipsum et dolor 
             kasd sit ea justo. Erat justo sed sed diam. 
             Ea et erat ut sed diam sea ipsum est dolor</p>
    <ul type="none">
        <li>&#10004 Lorem ipsum dolor sit amet</li><br>
        <li>&#10004 Lorem ipsum dolor sit amet</li><br>
        <li>&#10004 Lorem ipsum dolor sit amet</li><br>
    </ul><br>
    <button class="B2">Learn More</button>
        
    </div>
</div>
</div>
</section>
   </body>
   </html>

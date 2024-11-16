<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planet Shop</title>
    <style>
        <style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');
            
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-weight:bold;
            color:rgba(255, 255, 255, 0.734);
        }
        body{
            font-family: "Open Sans", sans-serif; ;
            background-color:rgb(23, 55, 55);
        }
        header{
            height:70px;
            display:flex;
            justify-content:space-around;
            align-items:centre;
            border-bottom:rgba(255, 255, 255, 0.734)




        }
        ul{
            display: flex ;
            list-style-type: none;
        }
        ul li a{
            margin: 0 5px;
            border:2px solid black;
            padding: 0px 10px;
            text-decoration:none;

        }
        .Logo{
            border:2px solid rgb(13, 0, 128);
            padding: 10px 5px;

        }
        .Signup{
            background-color:bisque;
            color:red;
        }
        main{
            display:flex;
            height:auto;
            justify-content:space-evenly;
            align-items: centre;
            margin:0 150px;
        }
        .contentLeft{
            flex:1; 
        }
        .contentmid{
            flex:2;
        }
        .contentright{
            flex:1;
        }
        .btn{
            padding: 15px 30px;
            background: none;
            outline: none;
            color:bisque;
            border-radius:50px;
            font: weight 700px;

        }
    </style>
</head>
<body>
    <header>
        <div class="Logo"></div>
        <nav>
            <ul>
                <Li>
                    <a href="#">Home</a>
                    <a href="#">Offers</a>
                    <a href="#">Buy Now </a>
                    <a href="#">Sell Now</a>
                    <a href="#">About Us</a>
                    <a href="#" class="signup">Sign up</a>
                </Li>
        
            </ul>
        </nav>
    </header>
    <main>
        <div class="contentleft">
            <h2>Mercury</h2>
        </div>
          
        <div class="contentmid">
            <p>Mercury is the first planet from the Sun and the smallest in the Solar System.
                 In English, it is named after the ancient Roman god Mercurius
                </p>
                <button class="btn"> Buy Now</button>
        </div>

        <div class="contentright">
            <img src="https://img.freepik.com/free-vector/world-travel-planet-logo-negative-space-style_126523-784.jpg">
</body>
</html>

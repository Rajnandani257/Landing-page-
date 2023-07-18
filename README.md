# Landing-page code-
#HTML file


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing page</title>
    <style type="text/css">
        *{padding:0;margin:0;box-sizing: border-box;}
        header{
            width: 100%;
            height:100vh;
            background-image: url('images/amaz.jpg');
            background-size: cover;
            font-family: sans-serif;
        }

        nav{
            width: 100%;
            height:100px;
            color:black;
            display:flex;
            justify-content: space-around;
            align-items: center;
        }
        .logo{
            font-size: 5em;
            font-style:italic ;
            letter-spacing: 2px;
            color:darkorange;
        }
        .menu a{
            text-decoration: none;
            color: black;
            padding: 10px 20px;
            font-size: 30px;
            position: relative;

        }

        .menu a:before{
            content:'';
            position: absolute;
            top:0;
            left:0;
            width:0%;
            height:100%;
            border-bottom: 2px solid red;
            transition: 0.4sec linear;
        }

        .menu a:hover:before{
             width:90%
        }
        .signup a{
            text-decoration: none;
            color: black;
            padding: 10px 20px;
            font-size: 20px;
            background: red;
            border-radius: 8px;
            transition: 0.4sec;

        }


        .signup a:hover{
            background: transparent;
            border:1px solid red;

        }
        .h-txt{
            max-width: 650px;
            position: absolute;
            top: 50%;
            left:50%;
            transform: translate(-50%,-50%);
            text-align:center;
            color:rgb(9, 1, 41);


        }
        .h-txt span{
            letter-spacing: 5px;

        }
        .h-txt h1{
            font-size: 3.5em;
        }
        .h-txt a{
            text-decoration: none;
            background-color:rgb(241, 208, 144);
            color:rgba(48, 1, 3, 0.863);
            padding: 10px 20px;
            letter-spacing: 5px;
            transition: 0.4sec;
        }
        .h-txt a:hover{
            background: transparent;
            border:1px solid red;

    </style>

</head>
<body>
    <header>
        <nav>
            <div class="logo">Yum</div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">Categories</a>
                <a href="#">Best offer</a>
                <a href="#">Our Site</a>
                <a href="#">Contact</a>
            </div>
            <div class="signup">
                <a href="#">Signup</a>
            </div>
        </nav>

        <section class="h-txt">
            <span><i>Enjoy</i></span>
            <h1>Yum World</h1>
            <br>
            <a href="#"><b>Order your Delicious Food</b></a>
            
        </section>
    </header>
    
</body>
</html>




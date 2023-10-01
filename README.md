<!DOCTYPE html>
<html>

<head>
    <title>Simple Landing Page Using html css in hindi</title>
    <style type="text/css">
            = {
            padding: 0;
            margine: 0;
            box-sizing: border-box;
        }
        
        header {
            width: 100%;
            height: 100vh;
            background: linear-gradient(rgba(37, 36, 36, 0.8), rgba(0, 0, 0, 0.2)), url('img/nbg.jpg');
            background-size: cover;
            font-family: sans-serif;
        }
        
        nav {
            width: 100%;
            height: 100px;
            background: rgb(170, 214, 108);
            color: black;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        
        .logo {
            font-size: 2em;
            letter-spacing: 2px;
        }
        
        .menu a {
            text-decoration: none;
            color: black;
            padding: 10px 20px;
            font-size: 20px;
            position: relative;
        }
        
        .menu a::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 0%;
            height: 100%;
            border-bottom: 2px solid indianred;
            transition: 0.4s linear;
        }
        
        .menu a:hover::before {
            width: 90%;
        }
        
        .register a {
            text-decoration: none;
            color: black;
            padding: 10px 20px;
            font-size: 20px;
            background-color: indianred;
            border-radius: 8px;
            transition: 0.4s;
        }
        
        .register a:hover {
            background: transparent;
            border: 1px solid indianred;
        }
        
        .h-txt {
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: black;
        }
        
        .h-txt span {
            letter-spacing: 5px;
        }
        
        .h-txt h1 {
            font-size: 3.5em;
        }
        
        .h-txt a {
            text-decoration: none;
            background-color: rgb(173, 205, 92);
            color: black;
            padding: 10px 20px;
            letter-spacing: 5px;
            transition: 0.4s;
        }
        
        .h-txt a:hover {
            background: transparent;
            border: 1px solid rgb(102, 93, 93);
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="logo">
                LUCIFER-$
            </div>
            <div class="menu">
                <a herf="#">Home</a>
                <a herf="#">Hill station</a>
                <a herf="#">Best Offer</a>
                <a herf="#">Our Sites</a>
                <a herf="#">Contact</a>
            </div>
            <div class="register>
       <a herf=" # ">Register</a>
     </div>
  </nav>
  <section class="h-txt ">
	<span>Enjoy</span>
	<h1>International Lucifer-$ Travel Agency</h1>

	<br>
	<a herf="# ">Book Your Trip</a>
	</section>

</header>
</body>
</html>

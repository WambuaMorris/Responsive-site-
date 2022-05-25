# Responsive-site-
Awesome responsive project
INDEX.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Acme web Design | Welcome</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding"><h1><span class = "highlight">Acme</span> Web Design</h1> </div>
            <nav><ul>
                <li class="current"> <a href="index.html">Home</a></li>
                <li> <a href="about.html">About</a></li>
                <li> <a href="services.html">Services</a></li>
             </ul></nav>
        </div>
    </header>
<section id = "showcase">
    <div class="container">
        <h1>Affordable professional websites</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae mollitia necessitatibus saepe! Quisquam fugit aut aliquam eos obcaecati tempora vitae?</p>
    </div>
</section>
<section id="newsletter">
    <div class="container">
        <h1>Subscribe to our newsletter!</h1>
        <form >
            <input type="email" name="" id="" placeholder="Enter email">
            <button type="submit" class="submit-button">Subscribe</button>
        </form>
    </div>
</section>

<section id="boxes">
    <div class="container">
        <div class="box">
            <img src="logohtml.png" alt="">
            <h3>HTML5 Markup</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi!</p>
        </div>
        <div class="box">
            <img src="csslogo.png" alt="">
            <h3>CSS3 Styling</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi!</p>
        </div>
        <div class="box">
            <img src="graphicdesignlogo.png" alt="">
            <h3>Graphic Design</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi!</p>
        </div>
    </div>
</section>
<footer>
    <p>Acme Web Design, Copyright &copy; 2022</p>
</footer>

</body>
</html>

ABOUT.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Acme web Design | About</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding"><h1><span class = "highlight">Acme</span> Web Design</h1> </div>
            <nav><ul>
                <li > <a href="index.html">Home</a></li>
                <li class="current"> <a href="about.html">About</a></li>
                <li> <a href="services.html">Services</a></li>
             </ul></nav>
        </div>
    </header>

<section id="newsletter">
    <div class="container">
        <h1>Subscribe to our newsletter!</h1>
        <form >
            <input type="email" name="" id="" placeholder="Enter email">
            <button type="submit" class="submit-button">Subscribe</button>
        </form>
    </div>
</section>

<section id="main">
    <div class="container">
    <article id="main-col">
        <h1 class="page-title" >About us</h1>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae excepturi id repudiandae ut omnis molestiae beatae quo reprehenderit consequuntur quia, totam animi debitis tempora non autem accusamus doloribus eligendi inventore minima hic ipsam? Aut laudantium deleniti quas temporibus qui placeat animi quis adipisci tenetur, praesentium illum. Quam at ratione beatae mollitia totam consequatur natus, quidem quibusdam necessitatibus culpa voluptatibus id voluptas impedit perspiciatis ea inventore! Accusamus quasi itaque impedit eveniet repellendus quaerat incidunt, non earum. Corrupti quasi consequuntur repellendus explicabo sit possimus dolorum, voluptate praesentium quis nostrum ipsum, quidem amet?</p>
    </article>
</div>
    <div class="dark">
    <aside id="sidebar">
        <h3>What we Do</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae asperiores quos libero repellendus beatae reiciendis totam accusamus fugiat. Unde sit provident animi, ipsam deleniti ducimus delectus quae itaque commodi reiciendis?</p>
    </aside>
</div>
</section>


<footer>
    <p>Acme Web Design, Copyright &copy; 2022</p>
</footer>

</body>
</html>

SERVICES.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Acme web Design | Services</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding"><h1><span class = "highlight">Acme</span> Web Design</h1> </div>
            <nav><ul>
                <li > <a href="index.html">Home</a></li>
                <li > <a href="about.html">About</a></li>
                <li class="current"> <a href="services.html">Services</a></li>
             </ul></nav>
        </div>
    </header>

<section id="newsletter">
    <div class="container">
        <h1>Subscribe to our newsletter!</h1>
        <form >
            <input type="email" name="" id="" placeholder="Enter email">
            <button type="submit" class="submit-button">Subscribe</button>
        </form>
    </div>
</section>

<section id="main">
    <div class="container">
    <article id="main-col">
        <h1 class="page-title" >Services</h1>
        <ul id="services">
            <li><h3>Website Design</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam enim sint tempora eveniet suscipit ut hic iste asperiores corporis sequi?</p>
                <p>Pricing: $1000 - $3000</p>
            </li>
            <li><h3>Website Maintenance</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam enim sint tempora eveniet suscipit ut hic iste asperiores corporis sequi?</p>
                <p>Pricing: $250 per month</p>
            </li>
            <li><h3>Website Hosting</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam enim sint tempora eveniet suscipit ut hic iste asperiores corporis sequi?</p>
                <p>Pricing: $25 per Month </p>
            </li>
        </ul>
    </article>
</div>
    <div class="dark">
    <aside id="sidebar">
        <h3>Get a quote</h3>
        <form class="quote">
            <div>
                <label>Name</label><br>
                <input type="text" placeholder="EnterName">
            </div>
            <div>
                <label>E-mail</label><br>
                <input type="email" placeholder="E-mail">
            </div>
            <div>
                <button class="submit-button">Submit</button>
            </div>

        </form>
    </aside>
</div>
</section>


<footer>
    <p>Acme Web Design, Copyright &copy; 2022</p>
</footer>

</body>
</html>

STYLE.CSS

body{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 15px;
    line-height: 1.5;
    padding: 0;
    margin: 0;
    background-color: #f4f4f4;
}
.container
{
    width: 80%;
    margin: auto;
    overflow: hidden;

}
.submit-button{
    height: 38px;
    background: #e8491d;
    border: none;
    padding-left: 20px;
    padding-right: 20px;
    color: #ffffff;
}
.dark{
    background: #35424a;
    color: #ffffff;
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 15px;
}

 ul{
    margin: 0;
    padding: 0;
    
}
header{
    background-color: #35424a;
    color: #ffffff;
    padding-top:30px;
    min-height: 70px;
    border-bottom: #e8491d 3px solid;
}
header a{
    color: #ffffff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}

header li{
 float: left;
 display: inline;
 padding: 0 20px 0 20px;
}
#branding{
    float: left;
}
header #branding h1{
    margin: 0;
}
header nav{
    float: right;
    margin-top: 10px;
}
header .highlight, header .current a{
color:#e8491d ;
font-weight: bold;
}
header a:hover{
    color:#cccccc;
    font-weight: bold;
}
#showcase{
    min-height :400px;
    background: url("showcase.jpg") no-repeat 0 -100px ;
    text-align: center;
    color: #ffffff;
}
#showcase h1{
    margin-top: 100px;
    font-size:55px ;
    margin-bottom: 10px;
}
#showcase p{
    font-size: 20px;
}
#newsletter{
    padding: 15px;
    color: #ffffff;
    background: #35424a;

}
#newsletter h1{
   float: left;

}
#newsletter form{
   float: right;
}
#newsletter input[type = "email"]{
    padding:4px ;
    height: 25px;
    width: 250px;
 }
 #boxes{
     margin-top: 20px;
 }
 #boxes .box{
    float: left;
    text-align: center;
    width:30%;
    padding: 10px;
}
#boxes .box img{
    width: 90px;
}

/*main-col*/
article #main-col{
    float: left;
    width: 65%;
}
/*sidebar*/
 aside #sidebar {
    float: right;
    width: 30%;
    margin-top: 10px;
  
}
aside #sidebar .quote input, aside #sidebar .quote textarea{
    width: 90%;
    padding: 5px;
}
ul #services li{
    list-style: none;
    padding: 20px;
    background: #cccccc solid 1px;
    margin-bottom: 5px;
    background:#e6e6e6 ;
}
footer{
    padding: 20px;
    margin-top: 50px;
    color: #ffffff;
    background-color: #e8491d;
    text-align: center;
}
@media (max-width: 768px){
    header #branding
    header nav,
    header nav li
    #newsletter h1
    #newsletter form
    #boxes .box
    article #main-col
    article #sidebar{
        float: none;
        text-align: center;
        width:100%;
    }
    header{
        padding-bottom:20px;
    }
    #showcase h1{
        margin-top:40px;
    }
    #newsletter button , quote button{
        display: block;
        width: 100%;
    }
    #newsletter form input[type = "email"] {
        width:100%;
        margin-bottom: 5px;
    }
}



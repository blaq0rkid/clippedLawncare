<style>
    /*Basic CSS Resets*/
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
body{
    background-color: #edeff0;
    font-family: 'Roboto', sans-serif;
}
/*header*/
header{
    background-color: #FBF9FF;
    box-shadow: 0px 0px 20px rgba(0,0,0,.2);
}
header .logo{
    font-size: 1.5em;
    font-family: 'Raleway', sans-serif;
}

header li{
    display: inline-block;
}
header a{
    display: inline-block;
    color: #0D1413;
    text-decoration: none;
    padding: 10px;
    transition: background-color 0.4s;
}
header nav a:hover,
header .active a{
    background-color: rgba(0,0,0,.05);
}
/****header*/
.container{
    max-width: 1000px;
    margin: auto;
    padding: 10px;
}
/*showcase*/
#showcase{
    height: 300px;
    background-image: url(../img/garden.jpg);
    background-attachment: fixed;
    background-size: cover;
    position: relative;
}
#showcase h1{
    text-align: center;
    background-color: rgba(0,0,0,.3);
    color: #fff;
    padding: 20px;
    position: absolute;
    top: 120px;
    width: 80%;
    left: 10%;
}
/****showcase*/

#contact{
    background-color: #fff;
    padding: 10px;
    
}
#contact .container{
    max-width: 600px;
    margin: auto;
}
#contact h2{
    font-size: 1.5em;
    padding: 20px 0px;
    text-align: center;
}
#contact p{
    padding: 10px 0px;
    font-style: italic;
}
#contact form input,
#contact form textarea{
    padding: 10px;
    margin: 5px 0px;
    width: 100%;
    border: 2px solid transparent;
    outline: none;
    background-color: #edeff0;
    transition: all 0.4s;
}

#contact form input:hover,
#contact form textarea:hover{
    background-color: #fff;
    border: 2px solid #edeff0;
}
#contact button{
    padding: 10px;
    margin: 10px 0px 20px;
    border: 2px solid transparent;
    background-color: #55C18F;
    color: #fff;
    transition: all 0.4s;
}
#contact button:hover{
    background-color: #fff;
    color:  #55C18F;
    border: 2px solid  #55C18F;
}


/*footer*/
footer{
    background-color: #0D1413;
    color: #fff;
}
footer div{
    padding: 10px;
}
footer ul{
    list-style-type: none;
}
footer a{
    color: #fff;
    padding: 10px 0px;
}
footer p{
    padding: 10px 0px;
}
.news-letter input{
    padding: 10px;
    width: 100%;
}
.news-letter button{
    border: none;
    width: 40%;
    margin: 20px 0px;
    padding: 15px;
    background-color: #55C18F;
    color: #fff;
    transition: box-shadow 0.5s;
}

.news-letter button:hover{
    box-shadow: 0px 0px 10px rgba(0,0,0,.3);
}
/****footer*/


/*media queries for tablets*/
@media screen and (min-width: 750px){
    header .logo{
        display: inline-block;
        width: 30%;
    }
    header nav{
        display: inline-block;
        width: 60%;
    }
    
    
    footer .services-links,
    footer .get-in-touch{
        margin: 20px;
        width: 40%;
        display: inline-block;
    }
    footer .services-links a{
        padding: 5px 0px;
        display: inline-block;
    }
    footer .news-letter{
        margin: 10px 20px;
    }
    footer .news-letter input{
        width: 70%;
    }
    
    footer .news-letter button{
        margin-left: 10px;
        width: 20%;
        padding: 12px;
    }
    footer .copyright{
        text-align: center;
    }
}
</style>

<header>
    <div class="container">
        <div class="logo">
            <a href="home.html">My Garden</a>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                
                <li><a href="services.html">Services</a></li>
                <li class=active><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </div>
    
</header>
<section id="showcase">
    <div class="container">
        <h1>Contact Us</h1>
    </div>
    
</section>
<section id="contact">
    <div class="container">
        <h2>Get in Touch</h2>
        <p>We are available 24/7 e-mail. You can also use our quick contact form to ask a question about our services and projects.</p>
        <form action="">
            <input type="text" placeholder="First name">
            <input type="tel" placeholder="Phone number">
            <input type="email" placeholder="E-mail">
            <textarea placeholder="Your message"></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>
    
</section>
<section id="map">
    <div class="mapouter"><div class="gmap_canvas"><iframe width="100%" height="500" id="gmap_canvas" src="https://maps.google.com/maps?q=paris&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe></div><a href="https://www.embedgooglemap.net">embedgooglemap.net</a><style>.mapouter{overflow:hidden;height:500px;width:100%;}.gmap_canvas {background:none!important;height:500px;width:100%;}</style></div>
</section>

<footer>
    <div class="container">
        <div class="services-links">
            <h3>Services</h3>
            <ul>
                <li><a href="">Fall &amp; spring clean up</a></li>
                <li><a href="">Lawn care</a></li>
                <li><a href="">Landscape design &amp; installation</a></li>
                <li><a href="">Plants, flowers, soils and mulches</a></li>
            </ul>
        </div>
        <div class="get-in-touch">
            <p>44 Shirley Ave. West Chicago, IL 60185</p>
            <p>1-(900)-123-4567</p>
            <p>Email: Mygarden@gmail.com</p>
        </div>
        <div class="news-letter">
            <form action="">
                <input type="email" placeholder="Enter your email">
                <button type="submit">Subscribe</button>
            </form>
        </div>
        <div class="copyright">
            <p>Copyright &copy; 2018 Hichem Med.</p>
        </div>
    </div>
    
</footer>
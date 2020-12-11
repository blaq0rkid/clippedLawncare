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

/*welcome*/
#welcome{
    text-align: center;
    background-color: #55C18F;
    color: #fff;
    padding: 20px 10px;
}
#welcome h1{
    font-size: 2em;
    padding: 20px;
}

.service{
    margin: 30px 0px;
    background-size: cover;
    padding: 20px;
    
}
.service .call-to-action{
    width: 100%;
    padding: 15px;
    margin: 15px 0px ;
    border: none;
    background-color: #55C18F;
    color: #fff;
    border-radius: 0px 50px;
    cursor: pointer;
    transition: all 0.4s;
}
.service .call-to-action:hover{
    color: #55C18F;
    background-color: #fff; 
}
.service.one{
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(../img/s1.jpeg);  
}
.service.two{
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(../img/s2.jpeg);  
}
.service.three{
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(../img/s3.jpeg);  
}
.service h3{
    font-size: 1.3em;
    padding: 10px;
    border-bottom: 1px solid;
    margin-bottom: 5px;
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
    .service{
        width: 47.5%;
        margin: 10px 0px;
        float: left;
    }
    .service.two{
        margin-right: 5%;
    }
    .service.one{
        width: 100%;
    }
    .services-container{
        max-width: 800px;
        margin: auto;
    }
    .services-container:after{
        content: '';
        display: block;
        clear: both;
    }
    .service .call-to-action{
        margin: 15px 0px;
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

<svelte:head>
	<title>Clipper's Lawncare</title>
	<link href="https://fonts.googleapis.com/css?family=Raleway|Roboto" rel="stylesheet">
</svelte:head>

<body>
    <section id="showcase">
        <div class="container">
            <h1>Services</h1>
        </div>
        
    </section>
      <section id="welcome">
        <div class="services">
            <div class="container">
                <h1>The best services that you can find!</h1>
                <div class="services-container">
                    <div class="service one">
                        <h3>Consultation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum cupiditate inventore laborum harum ad, tempore necessitatibus amet, autem nihil enim expedita aliquid mollitia nostrum quisquam beatae aliquam iusto repellendus nam.</p>
                        <button class="call-to-action">Read more</button>
                    </div>
                    <div class="service two">
                        <h3>Concept Design</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                        <button class="call-to-action">Read more</button>
                    </div>
                    <div class="service three">
                        <h3>Documentation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                        <button class="call-to-action">Read more</button>
                    </div>
                </div>
            </div>
        </div>
       
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
    
</body>
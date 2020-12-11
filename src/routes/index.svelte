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

/*intro*/
#intro{
    min-height: 60vh;
    text-align: center;
    background-image: url(../img/garden.jpg);
    background-size: cover;
    background-attachment: fixed;
}
#intro .text-intro{
    background-color: rgba(0,0,0,.3);
    color: #fff;
}
#intro h2{
    margin-top: 100px;
    padding: 10px;
    font-family: 'Raleway', sans-serif;
}
#intro h3{
    padding: 5px;
}
#intro .text-btn a{
    display: inline-block;
    width: 40%;
    margin: 50px 0px;
    padding: 15px;
    text-decoration: none;
    background-color: #55C18F;
    color: #fff;
    transition: box-shadow 0.5s;
    
}
#intro .text-btn a:hover{
    box-shadow: 0px 0px 10px rgba(0,0,0,.3);
}
/* ***Intro*/
.container{
    max-width: 1000px;
    margin: auto;
    padding: 10px;
}

/*welcome*/
#welcome{
    text-align: center;
    background-color: #55C18F;
    color: #fff;
    padding: 20px 10px;
}
#welcome h1{
    font-size: 2em;
    padding: 5px;
}
#welcome p{
    padding: 10px;
}
.service{
    margin: 20px 0px;
}
.service h3{
    font-size: 1.3em;
    padding: 10px;
    border-bottom: 1px solid;
    margin-bottom: 5px;
}
.work{
    min-height: 250px;
    margin: 20px auto;
    width: 90%;
    position: relative;
    box-shadow: 0px 0px 10px rgba(0,0,0,.1);
}
.work.one{
    background-image: url(../img/s1.jpeg);
    background-size: cover;
}
.work.two{
    background-image: url(../img/s2.jpeg);
    background-size: cover;
}
.work.three{
    background-image: url(../img/s3.jpeg);
    background-size: cover;
}
.work.four{
    background-image: url(../img/s4.jpeg);
    background-size: cover;
}
.work-title{
    position: absolute;
    width: 100%;
    bottom: 0px;
    background-color: rgba(0,0,0,.3);
    color: #fff;
    padding: 20px 5px;
}

/****welcome*/

/*blog*/
#blog{
    text-align: center;
    padding: 20px 10px;
}

#blog h2{
    padding: 10px;
    font-size: 1.5em;
}
#blog .blog-call-to-action a,
#blog .article-call-to-action a{
    display: inline-block;
    width: 40%;
    margin: 10px 0px 20px;
    padding: 15px;
    text-decoration: none;
    background-color: #55C18F;
    color: #fff;
    transition: box-shadow 0.5s;
}
#blog .blog-call-to-action a:hover,
#blog .article-call-to-action a:hover{
    box-shadow: 0px 0px 10px rgba(0,0,0,.3);
}
#blog .article{
    margin: 20px auto;
    width: 90%;
    background-color: #fff;
    box-shadow: 0px 0px 10px rgba(0,0,0,.2);
}
#blog .article-date{
    font-style: italic;
    padding: 10px;
    background-color: #0D1413;
    color: #fff;
}
#blog .article-title {
    font-size: 1.3em;
    padding: 10px;
}
#blog .article-text {
    padding: 10px;
}
/****blog*/

/*testimonial*/
#testimonials{
    background-color: #fff;
    text-align: center;
    padding: 20px 10px;
}
#testimonials h2{
    padding: 10px;
    font-size: 1.5em;
}
#testimonials h3{
    padding: 5px;
    font-size: 1.3em;
    font-style: italic;
}
#testimonials .testimonial{
    margin: 30px auto;
    width: 90%;
}
.testimonial p{
    padding: 10px;
}
.testimonial .testimonial-text{
    font-style: italic;
}
.testimonial .testimonial-author h4,
.testimonial .testimonial-author h5{
    padding: 5px;
}
#testimonials .testimonial img{
    height: 150px;
    width: 150px;
    border-radius: 50%;
    margin: 10px 0px;
}

/****testimonial*/

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
    #intro{
        min-height: 80vh;
    }
    #intro h2{
        margin-top: 250px;
    }
    #intro h3{
        padding: 15px;
    }
    .service{
        width: 70%;
        max-width: 600px;
        margin: 20px auto;
    }
    .work, #blog .article,
    #testimonials .testimonial,
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
    
    <section id="intro">
        <div class="container">
            <div class="text-intro">
                <h2>Professional Gardening, Landscaping & Maintenance Services</h2>
                <h3>The best solution for YOU</h3>
            </div>
            <div class="text-btn">
                <a href="#">View Projects</a>
            </div>
        </div>
        
    </section>
    <section id="welcome">
        <div class="services">
            <div class="container">
                <h1>Welcome to My Garden</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Veritatis dolore tempora, possimus saepe, labore sed excepturi sunt autem, alias minus maiores nesciunt similique optio rem earum asperiores ratione blanditiis et!</p>
                <div class="services-container">
                    <div class="service">
                        <h3>Consultation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum cupiditate inventore laborum harum ad, tempore necessitatibus amet, autem nihil enim expedita aliquid mollitia nostrum quisquam beatae aliquam iusto repellendus nam.</p>
                    </div>
                    <div class="service">
                        <h3>Concept Design</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                    </div>
                    <div class="service">
                        <h3>Documentation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="works">
            <div class="container">
                <div class="works-container">
                    <div class="work one">
                        <div class="work-title">
                            <h3>Fall &amp; spring clean up</h3>
                        </div>
                    </div>
                    <div class="work two">
                        <div class="work-title">
                            <h3>Lawn care</h3>
                        </div>
                    </div>
                    <div class="work three">
                        <div class="work-title">
                            <h3>Landscape design &amp; installation</h3>
                        </div>
                    </div>
                    <div class="work four">
                        <div class="work-title">
                            <h3>Plants, flowers, soils and mulches</h3>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </section>
    <section id="blog">
        <div class="container">
            <h2>Latest from the blog</h2>
            <div class="blog-call-to-action">
                <a href="">Visit our Blog</a>
            </div>
            <div class="blog-articles-container">
                <div class="article">
                    <div class="article-date">
                        <p>Jan 20, 2018</p>
                    </div>
                    <div class="article-title">
                        <h3>5 Most important things to know!</h3>
                    </div>
                    <div class="article-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae nisi ducimus dolorem sequi blanditiis repellendus, nihil sunt fuga dolor, eaque labore repellat iste unde ipsa accusantium deserunt quas ut perspiciatis.</p>
                    </div>
                    <div class="article-call-to-action">
                        <a href="">Read more</a>
                    </div>
                </div>
                <div class="article">
                    <div class="article-date">
                        <p>Jan 20, 2018</p>
                    </div>
                    <div class="article-title">
                        <h3>5 Most important things to know!</h3>
                    </div>
                    <div class="article-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae nisi ducimus dolorem sequi blanditiis repellendus, nihil sunt fuga dolor, eaque labore repellat iste unde ipsa accusantium deserunt quas ut perspiciatis.</p>
                    </div>
                    <div class="article-call-to-action">
                        <a href="">Read more</a>
                    </div>
                </div>
                <div class="article">
                    <div class="article-date">
                        <p>Jan 20, 2018</p>
                    </div>
                    <div class="article-title">
                        <h3>5 Most important things to know!</h3>
                    </div>
                    <div class="article-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae nisi ducimus dolorem sequi blanditiis repellendus, nihil sunt fuga dolor, eaque labore repellat iste unde ipsa accusantium deserunt quas ut perspiciatis.</p>
                    </div>
                    <div class="article-call-to-action">
                        <a href="">Read more</a>
                    </div>
                </div>
                <div class="article">
                    <div class="article-date">
                        <p>Jan 20, 2018</p>
                    </div>
                    <div class="article-title">
                        <h3>5 Most important things to know!</h3>
                    </div>
                    <div class="article-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae nisi ducimus dolorem sequi blanditiis repellendus, nihil sunt fuga dolor, eaque labore repellat iste unde ipsa accusantium deserunt quas ut perspiciatis.</p>
                    </div>
                    <div class="article-call-to-action">
                        <a href="">Read more</a>
                    </div>
                </div>
            </div>
        </div>
        
    </section>
    <section id="testimonials">
        <div class="container">
            <h2>Testimonials</h2>
            <h3>What our clients think</h3>
            <div class="testimonials-container">
                <div class="testimonial">
                    <div class="testimonial-img">
                        <img src="img/face1.jpeg" alt="">
                    </div>
                    <div class="testimonial-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A sit illum laboriosam fuga id deleniti error obcaecati consectetur, voluptate repudiandae voluptas, quasi quisquam quo praesentium. Temporibus, dicta delectus porro aspernatur.</p>
                    </div>
                    <div class="testimonial-author">
                        <h4>John Doe</h4>
                        <h5>Business man</h5>
                    </div>
                </div>
                <div class="testimonial">
                    <div class="testimonial-img">
                        <img src="img/face2.jpeg" alt="">
                    </div>
                    <div class="testimonial-text">
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A sit illum laboriosam fuga id deleniti error obcaecati consectetur, voluptate repudiandae voluptas, quasi quisquam quo praesentium. Temporibus, dicta delectus porro aspernatur.</p>
                    </div>
                    <div class="testimonial-author">
                        <h4>John Doe</h4>
                        <h5>Business man</h5>
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
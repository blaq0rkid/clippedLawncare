<style>
	/*Basic CSS Resets*/
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
body{
	margin-top: 6%;
    background-color: #edeff0;
    font-family: 'Roboto', sans-serif;
}

/*intro*/
#intro{
    min-height: 80vh;
    text-align: center;
    background-image: url(https://images.unsplash.com/photo-1571192776145-9f563c1df686?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NHx8Z2FyZGVufGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
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
    background-image: url(https://images.unsplash.com/photo-1552274229-96d9de3ebd7a?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OXx8ZmFsbCUyMHlhcmR8ZW58MHx8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
    background-size: cover;
}
.work.two{
    background-image: url(https://images.unsplash.com/photo-1553524808-eef8eb03cf29?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MXx8bGF3bnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
    background-size: cover;
}
.work.three{
    background-image: url(https://images.unsplash.com/photo-1595387426463-bef727e35bb3?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTN8fGxhbmRzY2FwZSUyMGRlc2lnbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
    background-size: cover;
}
.work.four{
    background-image: url(https://images.unsplash.com/photo-1550642254-711b7ce3971c?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NXx8Zmxvd2VyJTIwYmVkc3xlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
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
        </div>        
    </section>
    <section id="welcome">
        <div class="services">
            <div class="container">
                <h1>Welcome to Your Landscaping Solution</h1>
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
</body>
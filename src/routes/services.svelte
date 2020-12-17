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
.container{
    max-width: 1000px;
    margin: auto;
    padding: 10px;
}
/*showcase*/
#showcase{
    height: 300px;
    background-image: url(https://images.unsplash.com/photo-1578302758063-0ef3e048ca89?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NXx8Z2FyZGVufGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
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
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(https://images.unsplash.com/photo-1549276755-1bbd36282c6f?ixid=MXwxMjA3fDB8MHxzZWFyY2h8N3x8Z2FyZGVufGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);  
}
.service.two{
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(https://images.unsplash.com/photo-1550948390-6eb7fa773072?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTF8fGdhcmRlbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);  
}
.service.three{
    background-image:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.6)), url(https://images.unsplash.com/photo-1558293842-c0fd3db86157?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NjB8fGdhcmRlbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);  
}
.service h3{
    font-size: 1.3em;
    padding: 10px;
    border-bottom: 1px solid;
    margin-bottom: 5px;
}

/*media queries for tablets*/
@media screen and (min-width: 750px){

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
                        <button class="call-to-action">Call Us For A Consultation</button>
                    </div>
                    <div class="service two">
                        <h3>Concept Design</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                        <button class="call-to-action">Call Us For A Consultation</button>
                    </div>
                    <div class="service three">
                        <h3>Documentation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum expedita itaque deserunt incidunt ex nam quia architecto ea earum vero at optio laboriosam quas, beatae reiciendis aperiam libero blanditiis tempore.</p>
                        <button class="call-to-action">Call Us For A Consultation</button>
                    </div>
                </div>
            </div>
        </div>       
    </section>
</body>
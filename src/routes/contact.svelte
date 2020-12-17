<script>
	import Newsletter from '../components/Newsletter.svelte';
</script>

<style>
    /*Basic CSS Resets*/
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
.container{
    max-width: 1000px;
    margin: auto;
    padding: 10px;
}
/*showcase*/
#showcase{
    height: 300px;
    background-image: url(https://images.unsplash.com/photo-1561468528-e7b3a39e0e66?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OHx8Z2FyZGVuJTIwZmxvd2Vyc3xlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
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

/*media queries for tablets*/
@media screen and (min-width: 750px){
   
}
</style>

<svelte:head>
	<title>Clipper's Lawncare</title>
	<link href="https://fonts.googleapis.com/css?family=Raleway|Roboto" rel="stylesheet">
</svelte:head>

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
<Newsletter />

<section id="map">
    <!-- svelte-ignore a11y-missing-attribute -->
    <div class="mapouter">
        <div class="gmap_canvas">
            <iframe width="100%" height="500" id="gmap_canvas" src="https://maps.google.com/maps?q=paris&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
            </iframe>
        </div>
        <a href="https://www.embedgooglemap.net">embedgooglemap.net</a>
        <style>.mapouter{overflow:hidden;height:500px;width:100%;}.gmap_canvas {background:none!important;height:500px;width:100%;}</style>
    </div>
</section>
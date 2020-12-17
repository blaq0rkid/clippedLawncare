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
    background-image: url(https://images.unsplash.com/photo-1463554050456-f2ed7d3fec09?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTV8fGdhcmRlbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60);
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

/*few words about us*/
#few-words-about-us h2{
    font-size: 1.5em;
    text-align: center;
    padding: 20px;
    margin-bottom: 10px;
    border-bottom: 1px solid rgba(0,0,0,.1);
}
#few-words-about-us p{
    padding: 10px;
}
.call-to-action{
    text-align: center;
}
.call-to-action a{
    display: inline-block;
    margin: 10px 0px 20px;
    padding: 15px;
    text-decoration: none;
    background-color: #55C18F;
    color: #fff;
    transition: box-shadow 0.5s;
}

.call-to-action a:hover{
    box-shadow: 0px 0px 10px rgba(0,0,0,.3);
}
/*** few wors about us*/

/*company history*/
#our-history{
    background-color: #fff;
}
#our-history h2{
    font-size: 1.5em;
    text-align: center;
    padding: 20px;
    margin-bottom: 10px;
    border-bottom: 1px solid rgba(0,0,0,.1);
}
.event{
    padding: 10px 0px;
    margin: 10px 0px;
}
.event h3{
    font-style: italic;
    padding: 5px 0px;
    color: #55C18F;
}
.event h4{
    padding: 5px 0px;
    color: #55C18F;
}
.event p{
    padding: 5px 0px;
}
/***company history*/

/*Our team*/
#our-team h2{
    font-size: 1.5em;
    text-align: center;
    padding: 20px;
    margin-bottom: 10px;
    border-bottom: 1px solid rgba(0,0,0,.1);
}
.member{
    margin: 20px 0px;
    text-align: center;
    background-color: #fff;
    padding: 10px;
}
.member .member-img{
    height: 275px;
    width: 310px;
    border-radius: 50%;
}
.member .member-name{
    padding: 10px;
}
/**** our team*/

/*faq*/
#faq{
    background-color: #fff;
}
#faq h2{
    font-size: 1.5em;
    text-align: center;
    padding: 20px;
    margin-bottom: 10px;
    border-bottom: 1px solid rgba(0,0,0,.1);
}
.faq{
    padding: 10px 0px;
    margin: 10px 0px;
}
.faq .question{
    font-style: italic;
    font-size: 1.2em;
    padding: 10px 0px;
    font-weight: bold;
}
.faq span{
    padding-right: 10px;
}
/****faq*/

/*media queries for tablets*/
@media screen and (min-width: 750px){

    #our-history .event,
    #our-team .member,
    #faq .faq{
        display: inline-block;
        width: 40%;
        margin: 4.6%;
    }
    #few-words-about-us .box{
        max-width: 500px;
        margin: auto;
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
            <h1>About Us</h1>
        </div>
        
    </section>
    <section id="few-words-about-us">
        <div class="container">
            <div class="box">
                <h2>A bit about us</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur officia, ea, rerum voluptatem similique nam pariatur, aliquid possimus perspiciatis enim consequuntur animi quisquam praesentium fugit. Saepe unde tempore dolores libero?</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maxime consequuntur sint facilis nobis cum nostrum soluta quisquam numquam accusamus inventore asperiores enim debitis repellendus illum doloremque repellat laudantium modi, voluptate.</p>
            </div>
            <div class="box">
                <h2>Dreams come true</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos saepe totam, ad magnam ipsa beatae nobis a, sed iure sit architecto nemo molestiae nisi eveniet ratione assumenda explicabo nam omnis?</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem placeat asperiores ipsam, quas possimus cumque dicta voluptatibus fugiat minus accusamus ullam saepe nisi maiores quia. Nobis eum reprehenderit suscipit accusamus.</p>
            </div>
        </div>
        
    </section>
    <section id="our-history">
        <div class="container">
            <h2>Company History</h2>
            <div class="events-container">
                <div class="event">
                    <h3>1998</h3>
                    <h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum harum mollitia asperiores ratione libero eligendi officia dolor eos doloremque veritatis inventore ut, ducimus a exercitationem quo, beatae, eaque. Reiciendis, numquam.</p>
                </div>
                <div class="event">
                    <h3>2005</h3>
                    <h4>Lorem ipsum dolor sit amet, corporis dolorum praesentium, sint illum.</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum harum mollitia asperiores ratione libero eligendi officia dolor eos doloremque veritatis inventore ut, ducimus a exercitationem quo, beatae, eaque. Reiciendis, numquam.</p>
                </div>
                <div class="event">
                    <h3>2011</h3>
                    <h4>Lorem ipsum dolor sit amet, corporis dolorum praesentium, sint illum.</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum harum mollitia asperiores ratione libero eligendi officia dolor eos doloremque veritatis inventore ut, ducimus a exercitationem quo, beatae, eaque. Reiciendis, numquam.</p>
                </div>
                <div class="event">
                    <h3>2017</h3>
                    <h4>Lorem ipsum dolor sit amet, corporis dolorum praesentium, sint illum.</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum harum mollitia asperiores ratione libero eligendi officia dolor eos doloremque veritatis inventore ut, ducimus a exercitationem quo, beatae, eaque. Reiciendis, numquam.</p>
                </div>
            </div>
        </div>
        
    </section>
    <section id="our-team">
        <div class="container">
            <h2>Our Team</h2>
            <div class="members-container">
                <div class="member">
                    <img class="member-img" src="https://images.unsplash.com/photo-1573496799515-eebbb63814f2?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MXx8cHJvZmVzc2lvbmFsJTIwd29tYW58ZW58MHx8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60" alt="">
                    <h4 class="member-name">Jessa Doe</h4>
                    <h6 class="member-job">Owner</h6>
                </div>
                <div class="member">
                    <img class="member-img" src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixid=MXwxMjA3fDB8MHxzZWFyY2h8M3x8cHJvZmVzc2lvbmFsJTIwd29tYW58ZW58MHx8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60" alt="">
                    <h4 class="member-name">Tessa Lee</h4>
                    <h6 class="member-job">Architect</h6>
                </div>
                <div class="member">
                    <img class="member-img" src="https://images.unsplash.com/photo-1563122870-6b0b48a0af09?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MzJ8fHByb2Zlc3Npb25hbCUyMG1hbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60" alt="">
                    <h4 class="member-name">Mike Gregoire</h4>
                    <h6 class="member-job">Designer</h6>
                </div>
                <div class="member">
                    <img class="member-img" src="https://images.unsplash.com/photo-1474176857210-7287d38d27c6?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NDh8fHByb2Zlc3Npb25hbCUyMG1hbnxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60" alt="">
                    <h4 class="member-name">Lee Ram</h4>
                    <h6 class="member-job">Manager</h6>
                </div>
            </div>
        </div>
        
    </section>
    <section id="faq">
        <div class="container">
            <h2>FAQ</h2>
            <div class="faq-container">
                <div class="faq">
                    <div class="question">
                        <p><span>Q:</span>What does a landscape design cost?</p>
                    </div>
                    <div class="answer">
                        <p><span>A:</span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo pariatur illum alias quaerat quas sunt, quibusdam temporibus, neque doloribus fuga provident ullam magni iste, eius fugit laborum voluptates doloremque veniam.</p>
                    </div>
                </div>
                <div class="faq">
                    <div class="question">
                        <p><span>Q:</span>How do I choose a landscape designer?</p>
                    </div>
                    <div class="answer">
                        <p><span>A:</span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab aliquid quaerat magni expedita officia fuga harum esse! Necessitatibus quasi veniam suscipit. Dolore incidunt, dolorum vel, labore voluptate laboriosam? Corporis, corrupti.</p>
                    </div>
                </div>
                <div class="faq">
                    <div class="question">
                        <p><span>Q:</span>What about the budget for my landscape installation?</p>
                    </div>
                    <div class="answer">
                        <p><span>A:</span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis quisquam quidem architecto quibusdam dolores veniam molestiae, culpa, vero nobis dolorum, tempore, laborum magni blanditiis commodi quae impedit alias et veritatis.</p>
                    </div>
                </div>
                <div class="faq">
                    <div class="question">
                        <p><span>Q:</span>How do I choose a landscape designer?</p>
                    </div>
                    <div class="answer">
                        <p><span>A:</span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Similique veritatis, itaque totam. Necessitatibus, error, mollitia laborum eius atque quia officiis quibusdam autem voluptate magnam consequuntur beatae suscipit incidunt odit rem.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</body>
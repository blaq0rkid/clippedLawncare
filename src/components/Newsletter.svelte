<style>    
.news-letter {
    text-align: center;
}
.news-letter input{
    padding: 10px;
    width: 60%;
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
@media screen and (min-width: 750px){
/*    
    .get-in-touch{
       margin: 20px;
       width: 40%;
       display: inline-block;
   } */
    .news-letter{
       margin: 10px 20px;
   }
   footer .news-letter input{
       width: 60%;
   }
   
   footer .news-letter button{
       margin-left: 10px;
       width: 20%;
       padding: 12px;
   }
}
</style>

<div class="news-letter">
    <h2>Get Our Periodic Newsletter</h2>
    <form action="">
        <input type="email" placeholder="Enter your email">
        <button type="submit">Subscribe</button>
    </form>
</div>
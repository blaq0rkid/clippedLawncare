<script>
	export let segment;
</script>

<style>
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
</style>

<header>
    <div class="container">
        <div class="logo">
            <li><a aria-current="{segment === undefined ? 'page' : undefined}" href=".">Clipper's Lawncare</a></li>        
        </div>
    </div>    
</header>
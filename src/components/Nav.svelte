<script>
	export let segment;
</script>

<style>
	/*Basic CSS Resets*/
	*{
		margin: 0px;
		padding: 0px;
		box-sizing: border-box;
	}
	
	/*header*/
	header{
		text-align: center;
		position: fixed;	
		top: 8%;	
		width: 100%;
		z-index: 100;
		background-color: #FBF9FF;
		box-shadow: 0px 0px 20px rgba(0,0,0,.2);
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
	
	/*media queries for tablets*/
	@media screen and (min-width: 750px){
		/* header .logo{
			display: inline-block;
			width: 30%;
		} */
		header nav{
			display: inline-block;
			width: 60%;
		}		
	}
	</style>

<header>
	<div class="container">		
		<nav>
			<ul>
				<li><a aria-current="{segment === undefined ? 'page' : undefined}" href=".">Home</a></li>
				<li><a aria-current="{segment === 'services' ? 'page' : undefined}" href="services">Services</a></li>			   
				<li><a aria-current="{segment === 'about' ? 'page' : undefined}" href="about">About</a></li>
				<li><a aria-current="{segment === 'contact' ? 'page' : undefined}" href="contact">Contact</a></li>
			</ul>
		</nav>
	</div>
	
</header>
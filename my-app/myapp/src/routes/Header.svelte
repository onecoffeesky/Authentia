<script>
	import { page } from "$app/stores";
	import logo from "$lib/images/svelte-logo.svg";
	import github from "$lib/images/github.svg";
</script>

<body>
	<header>
		<nav>
			<div class="one">
				<img
					class="logo"
					src="C:\Users\Adrián Ramírez\Desktop\vamos a ver si es cierto, señores, vamos a ver si es cierto\my-app\myapp\static\favicon.png"
					alt="logo"
				/>
				<li class="wrlogo">Authentia</li>
			</div>
			<div class="two">
				<li>Home</li>
				<li>About</li>
				<li>Services</li>
			</div>	
		</nav>
	</header>
</body>

<style>
	body {
		margin: 0;
		padding: 0;
	}
	.wrlogo{
		align-items: flex-start;
	}

	header {
		background-color: #333;
		color: #fff;
		padding: 20px;
	}
	.logo {
		align-items: flex-start;
	}

	nav ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		text-align: left;
	}

	nav ul li {
		display: inline;
	}

	nav ul li {
		color: #fde4c3;
		text-decoration: none;
		margin-right: 10px;
	}
</style>

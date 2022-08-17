<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<img class="logo" src="Logo.png"/>
	<h1 class="title">REALTOR AI</h1>
	<h2>
		The Real Estate Agents best Assistant
	</h2>

	<div id="demo">
		Demo
	</div>

	<h1> 
		Interessted? 
		<br>Keep informed!
	</h1>

	<div id="registerArea">
		<input>
		<button id="registerButton">Register</button>
	</div>
	
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.logo {
		width: 49%;
    	margin-left: -59px;
	}

	.title {
		font-weight: 700;
		font-size: 4rem;
		margin: 0;
	}

	#registerButton {
		
	}

	#demo {

	}
</style>

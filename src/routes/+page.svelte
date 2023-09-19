<script>
	let name = 'Galego';
	// let minhaFoto = 'src/lib/images/profilepic.jpg'
	import minhaFoto from '$lib/images/profilepic.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>Hello, {name.toLowerCase()}</h1>
	<img src = {minhaFoto} alt = 'foto de {name}' class = 'profileImage'/>
</section>

<style>
	.profileImage {
		height: 64px;
		width: 64px;
	}
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>

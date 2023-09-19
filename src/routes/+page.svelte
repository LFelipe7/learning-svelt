<script>
  import "../app.css";
  import ClassificationCard from "./ClassificationCard.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
  <!-- <img src = {minhaFoto} alt = 'foto de {name}' class = 'profileImage'/> -->

  <div class="grid grid-cols-2 gap-x-40 gap-y-20">
    <ClassificationCard />
    <ClassificationCard coffeeClassification="Duro" />
    <ClassificationCard coffeeClassification="Riado" />
    <ClassificationCard coffeeClassification="Rio" />
    <ClassificationCard coffeeClassification="Verde" />
    <ClassificationCard coffeeClassification="Secador" />
  </div>
</section>

<style>
	.profileImage {
		height: 64px;
		width: 64px;
	}
	/* p {
		color: goldenrod;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
		background-color: aqua;
	} */
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

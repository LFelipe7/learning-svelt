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
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0.6;
  }
</style>

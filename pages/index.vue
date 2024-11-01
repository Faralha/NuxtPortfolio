<template>
	<div class="wrapper">
		<div
			class="container d-flex flex-column justify-content-center align-items-center"
			style="height: 100vh">
			<h1>Faralha's Portfolio.</h1>
			<p>It is currently under development for an uncertain amount of time.</p>

			<div class="d-flex gap-4">
				<NuxtLink to="/aresta">Aresta 17</NuxtLink>
				<a href="https://tropicasweets.com" target="_blank">Tropica Sweets</a>
				<a href="https://academy.alterkaiscans.my.id" target="_blank"
					>Alterkai TL Academy</a
				>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
  .wrapper {
    background-color: black;
    opacity: 90%;
    color: white;
  }

  p {
    opacity: 60%;
  }

  a {
    color: inherit;
    opacity: 85%;
    font-weight: bold;

    padding: 5px 10px 5px 10px;
    border: 0.5px solid white;
    border-radius: 5px;
    transition: all 0.2s ease-in;
  }

  a:hover {
    background-color: white;
    color: black;
  }
</style>

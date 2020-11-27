<script>
	export let status;
	export let error;

	const dev = process.env.NODE_ENV === 'development';
</script>

<style>
	h1, p {
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>{status}</title>
</svelte:head>

<main class="bg-white">
	<div class="container jumbotron mb-0">
		<h1>{status}</h1>

		<p>Página não encontrada!</p>

		<h3><a href="http://localhost:3000/cadastrado">Novo Link para Cadastrados</a></h3>

		{#if dev && error.stack}
			<pre>{error.stack}</pre>
		{/if}

	</div>
</main>

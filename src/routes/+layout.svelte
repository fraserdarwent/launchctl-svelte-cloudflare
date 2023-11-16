<script>
	import '@fontsource-variable/roboto-flex';
</script>

<svelte:head>
	<title>Hello, My Svelte World!!</title>
</svelte:head>

<main>
	<slot />
</main>

<style lang="scss">
	// Reset
	:global(*) {
		margin: 0;
	}

	:global(body) {
		font-family: 'Roboto Flex Variable', sans-serif;
		background-color: #ffb9d9;
	}

	main {
		max-width: 1000px;
		margin: 50px auto;
	}
</style>

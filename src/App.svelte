<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<b> This is an extra line of text that was not in the template before,</b>
	<c> Although I don't really know how it works I just copied the other code with text to create these</c>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<d> Trying to figure out how to start text on a new line on the page because sometimes it works and sometimes it doesn't</d>
	<e> This version has been uploaded to Git</e>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #881b23;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
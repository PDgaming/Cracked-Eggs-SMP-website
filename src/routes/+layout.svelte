<script>
	import Header from "./components/header.svelte";
</script>

<div class="app">
	<Header></Header>
	<main>
		<slot />
	</main>
</div>

<style>
	.app {
		min-height: 100vh;
		background-color: rgb(24, 24, 24);
	}
	main {
		flex: 1;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
	}
</style>

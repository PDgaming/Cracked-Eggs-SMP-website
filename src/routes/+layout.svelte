<script>
	import "./styles.css";
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
	}
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

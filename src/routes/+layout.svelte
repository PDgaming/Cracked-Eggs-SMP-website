<script>
	import "./styles.css";
	import Header from "./components/header.svelte";
</script>

<div class="app">
	<Header></Header>
	<main>
		<slot />
	</main>

	<footer>
		<p>*It's Still in Development</p>
	</footer>
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

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>

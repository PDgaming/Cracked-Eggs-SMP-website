<script>
	import "./styles.css";
</script>

<div class="app">
	<main>
		<slot />
	</main>

	<footer>
		<p>*It's Still in Development</p>
	</footer>
</div>

<style>
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

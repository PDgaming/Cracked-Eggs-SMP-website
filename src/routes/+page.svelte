<script>
	import { goto } from "$app/navigation";

	function play() {
		goto("/play");
	}
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<center>
	<h1>Official Cracked Eggs Website</h1>
	<button on:click={play}>Play</button>
</center>

<style>
</style>

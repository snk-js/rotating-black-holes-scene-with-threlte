<script lang="ts">
	import App from '$lib/components/App.svelte';
</script>

<div>
	<App />
</div>

<style>
	:global(body) {
		margin: 0;
	}

	:global(body, html) {
		margin: 0;
	}

	div {
		width: 100vw;
		height: 100vh;
		background: black;
		background: radial-gradient(ellipse at top, #121d2a, #05080f50),
			radial-gradient(ellipse at bottom, #000000, #000000);
	}
</style>

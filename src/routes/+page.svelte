<script lang="ts">
	import Weather from './weather.svelte';
	import Calendar from './calendar.svelte';
</script>

<div class="container">
	<header>
		<Weather />
	</header>
	<main>
		<Calendar />
	</main>
</div>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		overflow: hidden;
		background-color: #999;
	}
	:global(body + div) {
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
	.container {
		box-sizing: border-box;
		display: grid;
		gap: 10px;
		grid-template-rows: auto 1fr;
		grid-template-areas: 'header' 'main';
		overflow: hidden;
		padding: 10px;
		width: 100vw;
		height: 100vh;
	}
	header {
		grid-area: header;
		overflow: hidden;
		border-radius: 0.25em;
		max-width: 100%;
	}
	main {
		box-sizing: border-box;
		grid-area: main;
		max-height: 80vh;
	}
</style>

<script lang="ts">
	import './layout.css';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={"/favicon.png"} />
	<title>Edward Smale</title>
</svelte:head>

{@render children()}

<style>
	:global(html, body) {
		font-family: "Abhaya Libre", serif;
	}

	:global(a) {
		color: #ffe4e6;
		font-weight: 800;
	}

	:global(a:hover) {
		text-decoration: underline;
	}

	:global(h1) {
		font-size: 2.5rem;
		font-family: 'Aguafina Script', handwriting;
	}

	:global(h2) {
		font-size: 1.5rem;
		font-weight: 800;
	}
</style>
<script lang="ts">
	import './layout.css';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="/square.png" />
</svelte:head>

{@render children()}

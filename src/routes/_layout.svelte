<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
	main {
		@apply relative bg-white p-8 max-w-4xl mx-auto my-0;
		box-sizing: border-box;
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>
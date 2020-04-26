<script>
	import Tailwindcss from './Tailwindcss.svelte';

	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<Tailwindcss />

<div class="p-2 border bg-white rounded-lg shadow-2xl">
	<h1>Hello {name}!</h1>
</div>

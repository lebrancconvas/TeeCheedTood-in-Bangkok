<script lang="ts">
	import Router from 'svelte-spa-router';
	import Home from './routes/Home.svelte';
	import Location from './routes/Location.svelte';

	const routes = {
		"/": Home,
		"/location": Location
	}
</script>

<main>
	<Router {routes}/>
</main>

<style>

</style>
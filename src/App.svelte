<script>
	export let name
	console.log('App')
	import Playground from './components/Playground.svelte';
	const pointsArray = [[[5, 10], [10, 40], [40, 30], [60, 5], [90, 45], [120, 10], [150, 45], [200, 10]]]
</script>

<style>
</style>

<Playground pointsArray={pointsArray}/>




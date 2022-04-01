<script>
	import Todo from './Todo.svelte';
</script>

<main>
	<h1>To Do App</h1>
	<Todo />
	
</main>

<style>
	main {
		color: rgb(0, 0, 0);
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: rgb(255, 255, 210);
	}

	h1 {
		font-family: "Rock3D";
		color: #000000;
		text-transform: lowercase;
		font-size: 2em;
		font-weight: 90;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
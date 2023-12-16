<script>
	import Title from '$lib/Title.svelte';
	import '../styles/global.css';
</script>

<header>
	<Title title="Ninja Gaming Guides" />
</header>
<main>
	<slot />
</main>

<footer>
	<p>ML 2023</p>
</footer>

<style>
	header {
		background: #333;
		color: #fff;
		padding: 20px;
		display: flex;
		justify-content: center;
	}

	main {
		max-width: 800px;
		margin: 0 auto;
		padding: 20px;
	}

	footer {
		background: #333;
		color: #fff;
		padding: 20px;
		text-align: center;
	}
</style>

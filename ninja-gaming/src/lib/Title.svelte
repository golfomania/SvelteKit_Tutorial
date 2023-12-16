<script>
	export let title = 'Ninja gaming';
</script>

<div class="title">
	<img src="/controller.svg" alt="site logo" />
	<h1>{title}</h1>
</div>

<style>
	.title {
		display: flex;
		align-items: center;
		margin-bottom: 40px;
	}
	.title img {
		display: inline-block;
		filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(90%);
	}
	.title h1 {
		margin-left: 20px;
	}
</style>

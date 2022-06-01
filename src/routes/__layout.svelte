<script lang="ts">
	import '../app.css';
</script>

<main>
	<slot />
</main>

<footer></footer>

<style>
	@font-face {
		font-family: 'CGA Thin';
		src: url('Web437_IBM_CGAthin.woff') format('woff');
	}
	
	@font-face {
		font-family: 'CGA Thin';
		src: url('Web437_IBM_CGA.woff') format('woff');
		font-weight: bold;
	}
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

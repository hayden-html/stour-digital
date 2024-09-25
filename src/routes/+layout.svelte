<script>
	// You can add any additional logic here if needed
	import '../../global.css';
	// This can be false if you're using a fallback (i.e. SPA mode)
	export const prerender = true;
</script>

<main class="main">
	<slot />
</main>

<style>
	.main {
		background-color: grey;
	}
</style>

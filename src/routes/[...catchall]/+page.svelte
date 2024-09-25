<script>
	// You can add any additional logic here if needed
	import '../../global.css';
</script>

<main class="main">
	<section class="section">
		<div class="container">
			<h1 class="title">404 - Page Not Found</h1>
			<p class="message">Sorry, the page you are looking for does not exist.</p>
			<a href="/" class="home-link">Go to Home</a>
		</div>
	</section>
</main>

<style>
	.main {
		background-color: grey;
	}
	.section {
		height: 100dvh;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.container {
		text-align: center;
	}

	.title {
		font-size: 3rem;
		color: #ebebeb;
		margin-bottom: 16px;
	}

	.message {
		font-size: 1.5rem;
		color: #ebebeb;
		margin-bottom: 32px;
	}

	.home-link {
		font-size: 1.2rem;
		color: #ffffff;
		background-color: #007acc;
		padding: 10px 20px;
		text-decoration: none;
		border-radius: 5px;
	}
	.home-link:hover {
		background-color: #005fa3;
	}
</style>

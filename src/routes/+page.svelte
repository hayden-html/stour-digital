<script>
	// Suggested code may be subject to a license. Learn more: ~LicenseLog:3528049025.
	import logo from '../assets/logo.svg';
	import '../global.css';
</script>

<main class="main">
	<section class="section">
		<div class="container">
			<img src={logo} alt="Stour Digital Logo" class="logo" />
			<p class="soon">Website Coming Soon</p>
		</div>
	</section>
</main>

<style>
	.section {
		height: 100dvh;
	}

	.container {
		max-width: 1200px;
		margin: auto;
		padding: 10vh 16px;
		text-align: center;
	}
	.logo {
		width: clamp(280px, 80vw, 800px);
		margin-bottom: 32px;
	}

	.soon {
		color: #ebebeb;
		font-size: 2rem;
	}
</style>

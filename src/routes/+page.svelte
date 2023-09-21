<body>
	<section class="banner-container first">
		<h1>Client Onboardings made Easy</h1>
		<h2>Powered by AI</h2>
	</section>
</body>

<style>
	:root {
		font-family: 'Raleway', sans-serif;
	}

	section {
		height: 90vh;
		width: 90vw;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.banner-container {
		background-image: url('images/lights.svg');
		background-repeat: no-repeat;
		background-size: 100vh;
	}
	body {
		background: black;
		color: white;
	}

	h1,
	h2 {
		position: relative;
		top: 400px;
	}

	@media (max-width: 610px) {
		h1,
		h2 {
			top: 350px;
			font-size: 1.4em;
		}
	}
	@media (max-width: 434px) {
		h1,
		h2 {
			top: 300px;
			font-size: 1em;
		}
	}
</style>

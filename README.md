<html>
<head>
	<title></title>
	<style>
		body {
			background-color: #131516;
			font-family: 'Montserrat', sans-serif;
			color: #fff;
		}

		.container {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			height: 100vh;
		}

		.name {
			font-size: 7em;
			font-weight: 800;
			text-transform: uppercase;
			text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #30f8b3, 0 0 70px #30f8b3, 0 0 80px #30f8b3, 0 0 100px #30f8b3;
			transition: all 1s ease-in-out;
			cursor: pointer;
			animation: glow 3s ease-in-out infinite;
			margin-bottom: 1em;
			position: relative;
			z-index: 2;
		}

		.name:hover {
			transform: rotateY(180deg);
			color: #30f8b3;
		}

		.name:before {
			content: "Carlo";
			font-size: 0.8em;
			position: absolute;
			top: 0;
			right: 50%;
			transform: translateX(50%);
			letter-spacing: 0.3em;
			font-weight: 400;
			z-index: -1;
		}

		.name:after {
			content: "Agbong";
			font-size: 0.8em;
			position: absolute;
			top: 0;
			left: 50%;
			transform: translateX(-50%);
			letter-spacing: 0.3em;
			font-weight: 400;
			z-index: -1;
		}

		@keyframes glow {
			0% {
				box-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #30f8b3, 0 0 70px #30f8b3, 0 0 80px #30f8b3, 0 0 100px #30f8b3;
			}

			100% {
				box-shadow: 0 0 20px #fff, 0 0 40px #fff, 0 0 50px #fff, 0 0 80px #30f8b3, 0 0 130px #30f8b3, 0 0 150px #30f8b3, 0 0 170px #30f8b3;
			}
		}
	</style>
</head>
<body>
	<div class="container">
		<h1 class="name">CARLO AGBONG</h1>
	</div>
</body>
</html>

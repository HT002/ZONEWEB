# welcome to my website

my website

<html>

	<head>

		<meta charset='UTF-8'>

		

		<title>Simple Loader</title>

		

		<style>

		.content {display:none;}

		.preload { width:100px;

			height: 200px;

			position: fixed;

			top: 30%;

			left: 45%;

		}

		</style>

		<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>

		<script>

		$(function() {

			$(".preload").fadeOut(2000, 

		function() {

			$(".content").fadeIn(1000);

		});

		});

		</script>

		 

	</head>

	<body>

		<div class="preload"><img src="https://user-images.githubusercontent.com/79648523/135586418-f107cacc-0d0c-40a3-a3ca-fc182806f6e1.gif"></div>

		<div class="content">

			HELLO WORLD MY NAME IS BIG 

	</div>

	</body>

</html>

<!-- ref : SmallEnvelop.com -->

<!-- https://smallenvelop.com/display-loading-icon-page-loads-completely/ -->

© 2021 GitHub, Inc.

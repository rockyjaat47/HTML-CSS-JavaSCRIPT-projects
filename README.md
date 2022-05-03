<!DOCTYPE html>
<html>
	
<head>
	<title>
		Create an HTML button that
		acts like a link
	</title>
	
	<!-- Style to create button -->
	<style>
		.GFG {
			background-color: white;
			border: 2px solid black;
			color: green;
			padding: 5px 10px;
			text-align: center;
			display: inline-block;
			font-size: 20px;
			margin: 10px 30px;
			cursor: pointer;
		}
	</style>
</head>

<body>
	<h1>GeeksforGeeks</h1>
	
	<!-- Adding link to the button on the onclick event -->
	<button class="GFG"
	onclick="window.location.href = 'https://ide.geeksforgeeks.org';">
		Click Here
	</button>
</body>

</html>					

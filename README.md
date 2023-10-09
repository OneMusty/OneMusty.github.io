<!DOCTYPE html>
<html>
<head>
	<title>My Website</title>
	<style>
		body {
			background-color: black;
			color: white;
			font-family: Arial, sans-serif;
		}
		
		header {
			background-color: white;
			padding: 20px;
			text-align: center;
			font-size: 30px;
			font-weight: bold;
		}
		
		h1 {
			margin-top: 50px;
			text-align: center;
			font-size: 50px;
			font-weight: bold;
		}
		
		.rectangle {
			border: 2px solid white;
			width: 200px;
			height: 100px;
			margin: auto;
			margin-top: 50px;
			text-align: center;
			line-height: 100px;
			font-size: 30px;
			font-weight: bold;
            cursor: pointer; /* Add this line to make the rectangle clickable */
		}
        
        /* Add this block of code to change the color of the rectangle when it's clicked */
        .rectangle:hover {
            background-color: white;
            color: black;
        }
	</style>
</head>
<body>
	<header>OneMusty.github.io</header>
	
	<h1>My website</h1>
	
    <!-- Add this line to make the rectangle a link -->
    <a href="https://www.example.com"><div class="rectangle">My site</div></a>
	
</body>
</html>

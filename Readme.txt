
Let us add some dynamics to css to interact with...
The ": hover" selector...
Wouldnt it be cool if we could add  changes only when we point the mouse over a tag..
Well with the :hover selector it is possible...

Refer the styles.css file to learn its  syntax

U can open the styles.css file in the css folder and toy with that ;p

replace the entire HTML page as:

<html>
	<head>
		<link href="css/styles.css" rel="stylesheet" />
	</head>
	
	<body>
		<div id="nav-bar">
			<div id="nav-items">
				<div class="nav-item">
					Home
				</div>
				<div class="nav-item">
					Menu 1
				</div>
				<div class="nav-item">
					Menu 2
				</div>
				<div class="nav-item">
					Menu 3
				</div>
				<div class="search-bar">
					<input type="text" placeholder="Search" id="search-box">
					<button type="button" id="search-button">Search</button>
				</div>
			</div>
		</div>
	
	</body>
</html>

Here is an example of linking an external style sheet through the link tag in the head tag...
href="url" - points to the location of your style sheet...

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


my first commit
my second commit
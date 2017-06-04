(Identify group of elements... A new attribute "class")

class is an attribute by which u can identify an element or a group of elements.

Syntax:-
class=<name>

eg:-

<div class="demo"></div>


We can use css selectors. Selectors are like pointers. In the above example we saw a div with class = demo.
We can add a pointer in css with any attribute only defined to that element.

Syntax:-
.<class-name>{
	css properties
}

eg:-

.demo{
	css properties
}


replace the entire HTML page as:

<html>
	<head>
		<style>
			body, html{
				margin: 0;
				width: 100%;
				height: 100%;
			}
			#nav-bar{
				width: 100%;
				height: 50px;
				background: #333;
			}
			#nav-items{
				height: 40px;
			}
			.nav-item{
				width: 100px;
				height: 100%;
				text-align: center;
				display: inline-block;
				border-right: 1px solid #000;
				color: #ccc;
				padding-top: 10px;
			}
			.search-bar{
				display: inline-block;
				width: 300px;
				padding: 0;
			}
			#search-box{
				padding: 10px;
				background: #3f3f3f;
				border-radius: 10px 0px 0px 10px;
				border: 1px solid black;
				width: 150px;
				outline: none;
				color: white;
			}
			#search-button{
				padding: 10px;
				background: #666;
				border-radius: 0px 10px 10px 0px;
				border: 1px solid black;
				width: 60px;
				outline: none;
				color: #ccc;
				margin-left:-5px;
			}
		</style>
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

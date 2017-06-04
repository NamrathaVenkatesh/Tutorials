(How to identify the elements created... A new attribute "id")

id is an attribute by which u can identify an element.

Syntax:-
id=<unique-name>

eg:-

<div id="demo"></div>

Considering the previous code..

There is a new issue... What if I want a div with text color red and another div with text color blue 
and also with some common attributes among them.

We can use css selectors. Selectors are like pointers. In the above example we saw a div with id = demo.
We can add a pointer in css with any attribute only defined to that element.

Syntax:-
#<id-name>{
	css properties
}

eg:-

#demo{
	css properties
}


replace the entire HTML page as:

<html>
	<head>
		<style>
			/* This is a comment */
			/*Common property */
			div{
				background-color: black;
				margin: 10px;
				height: 100px;
			}
			/* Style only for element with id=demo1 */
			#demo1{
				color: red;
			}
			/* Style only for element with id=demo2 */
			#demo2{
				color: blue;
			}
		</style>
	</head>

	<body>
		<div id="demo1">Text is in red color</div>
		<div id="demo2">Text is in blue color</div>
	</body>

</html>


It has the same effect as above but less code...
Here is a link to the table of all css property and preferred values with examples.
https://pageresource.com/css-properties-list/

(Something in the head tag)
Hope u have done enough research on CSS

Consider this example where you have five div with common background-color and text color(to set text color the css property is color: <value>;)
<div style='background-color: red; color: blue;'>One</div>
<div style='background-color: red; color: blue;'>Two</div>
<div style='background-color: red; color: blue;'>Three</div>
<div style='background-color: red; color: blue;'>Four</div>
<div style='background-color: red; color: blue;'>Five</div>

Ok. This seems do-able,but what if you had hunderds of these elements with common property... inline-css won't look tidy.
So we will add the common styles in the head tag and point the element with the common property to the head.

A new element in the head tag <style> .... css properties </style>

replace the entire HTML page as:

<html>
	<head>
		<style>
			div{
				background-color: red;
				color: blue;
			}
		</style>
	</head>

	<body>
		<div>One</div>
		<div>Two</div>
		<div>Three</div>
		<div>Four</div>
		<div>Five</div>
	</body>

</html>


It has the same effect as above but less code...
Here is a link to the table of all css property and preferred values with examples.
https://pageresource.com/css-properties-list/

# Kuoyutzu111.github.io-HW2

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
<style type="text/css">
	body{background-color: lightyellow;}
	h1{color: blacks; }
	label{font-size: 12 ppt}

	.P{background-color: tomato;
		color;white;
		padding:10ppt}

	#label{
		background-color: lightblue;
		color:white;
		padding: 10ppt}

	h1, em {text-decoration: underline}

	span{color:black;
		border:1px solid black;}
	.extra span{
		color:inherit;
	}
</style>

</head>
<div align="lefts">
<strong><h1>New HTML5 Input Types Demo</h1></strong><br>
<body>
	<p>This form demonstrates the new HTML5 input types and the placeholder, required and autofocus attributes.<br><br></p>

	<label>Color:
		<input type="color" autofocus />
		(Hexadecimal code such as #ADD8E6)</label><br><br>


	<form action="/action_page.php">
		<label for ="Date">Date:</label>
		<input type="date" name="Date" >
		(yyyy-mm-dd)<br><br>


	<form>E-mail:
		<input type="email" name="email" placeholder="name@domain.com" required>(name@domain.com)<br><br>

	</form>

	<form action="/action_page.php">Number:
		<label for="quantity"Quantity(between 0 and 7):></label>
		<input type="number" name="quantity"min="0" max:"7" value="4" >
		(Enter a number between 0 and 7)<br><br></form>

	<form action="action_page.php" method="get">
		<label for="range">Range: 0</label>
		<input type="range" name="range" id=range  min="0" max="20"> 20
	</form><br><br>


	<form action="action_page.php">
		<label for="gsearch">Search: </label>
		<input type="text" name="search query" placeholder="search query">
	</form><br><br>

	<form action="/action_page.php">
		<label for="appt">Time: </label>
		<input type="time" name="appt">
		(hh:mm)<br><br>
	</form>

	<form>
		<input type="submit" name="submit">
		<input type="reset" names="clear"></form>
	</form>
	
</div>
</body>
</html>

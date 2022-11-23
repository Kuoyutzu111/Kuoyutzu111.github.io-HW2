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


<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>intro</title>

	<style type="text/css">
		body{color: lightblack;}
		h1, em{text-decoration: underline}

	.p{color: orange}
	#h1{background-color: Red}

	span{
		color:lightblues;
		border:1px solid black;
	}
	.extra span {
		color:inherits ;
	}

	</style>
</head>
<body>
	<div align="Left">
	<h1>My stubedent ID 111306006</h1> 
	<p> <strong>my name is Anita</strong> 
	<p>I don't have any habits</p> <br><code>etc </code></p></div>
	<p> <a href="Http://google.com"> SEARCH  </a> </p>
	<p><img src ="mm.jpg" width ="100" height ="80" alt = "Handsome Guys" /></p>

	<div align ="center">
		<table border="1">
		<tr>
			<th> Idol</th>
			<th> Student ID </th>
			<th> Name </th>
			<th> Habits </th> 
		</tr>

		<tr>
			<td rowspan ="2">
				<img src = "w644.jpg" width ="100" height ="70" alt ="Fault"/> </th>

			<th> <strong><h1><sub>1</sub>1<sup>1</sup>3<sub>0</sub>6<sup>0</sup>0<sub>6</sub></h1></strong> </th>
			<th> <Strong><h1><span>郭于慈</span></h1> </strong></th>
			<th> <strong><h1>Dramas</h1></strong></th>
		</tr>

		<tr>
			<td><i><sub>1</sub>1<sup>1</sup>3<sub>0</sub>6<sup>0</sup>0<sub>6</sub></i></td>
			<td><i>郭于慈</i></td>
			<td><i>Dramas</i></td> 
		</tr>

		<tr>
			 Information About Me <br> Hi nice to meet you ! Have a good day!</td>
		</tr>

	</div>

		

</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Extra</title>
	<style type="text/css">
		.td{color: lightblue}
		#tr{color: black}

		h5.em{text-decoration: underline}

	span {
		color:skyblue;
		border:1Px solid black;
	}
	.extra span{
		color:inherit;
	}
	</style>
</head>
<body>

	<div align="center">
	<table border="1" style="wideth:100%">
		<thead>
			<tr>
				<th colspan="3" ><h5><em>About--111306006</em></h5></th>
			</tr>
		<tbody>
			<tr><td rowspan="3"><img src="myphoto.jpg" width="100" height="100"><br>Personal Photo</td>

				<td colspan="2"><label>Name: 
					<input name="name" type="text" size"25" ></label><br>
					Gender:
					<input name="gender" type="radio" value="Male">Male
					<input name="gender" type="radio" value="Female">Female
					<input name="gender" type="radio" value="Other">Other</td>
			
			</tr>
				
			<td><span>Country:</span><form action="/action_page.php">
				<select name="country">
					<option value="R.O.C">R.O.C</option>
					<option value="China ">China</option>
					<option value="US">US</option>
					<option value="Canada">Canada</option></td>
			<td ><span>Birthday:</spans></style>
				<input type="date" value="birthday" name="birthday"><br>
				</td>
			</tr>

			<td colspan="2"><label>E-mail:
				<input name="email" type="text" value="email"></label></td>
			</tr>	
			

			<tr><td>Hobby	</td>
			<td colspan="2"><form action="/action-page.php" method="get">
				<input type="checkbox" name="Swimming" value="Swimming">Swimming
				<input type="checkbox" name="Volleyball" value="Volleyball">Villeyball
				<input type="checkbox" name="Movie" value="Movie">Movie
				<input type="checkbox" name="Game" value="Game">Game
				<input type="checkbox" name="Sleep" value="Sleep">Sleep</td>


			<tr><td>Skill</td>
			<td colspan="2"><form action="/action_page.php" method="get">
				<input type="checkbox" name="Java" value="Java">Java
				<input type="checkbox" name="HTML" value="HTML">HTML
				<input type="checkbox" name="Python" value="Python">Python
				<input type="checkbox" name="Microsoft" value="Micrtosoft">Microsoft
				<input type="checkbox" name="Premiere" value="Premiere">Premiere</td>
			</tr>	


			<tr><td>Say Something!</td>	
			<td colspan="2"> <input type="text" name="say something here!" value="say something here!" size="100"></td>
		</tr>

		<tr><td colspan="3">
			<input type="submit" name="Submit">
			<input type="reset" name="Reset">
		</td></tr>
			
		
			
		</tbody>
	</div>
</body>
</html>

<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Week10_HW</title>

	<style type="text/css">
		body{font-family: script, cursive;}
		a.nodec{text-decoration: none;}
		a.hover{text-decoration: underline;}
		li {font-weight: bold;}
		li em{text-decoration: line-through;}
		h1{font-family: critter, fantasy;
			text-decoration: underline;}
			em{font-family: script, cursive;
				font-weight: bolder;}
		h2{font-family: courier, monospace;
			text-decoration: line-through;}
		h3{font-family: fixedsys, monospace;
			text-decoration: overline;}
		ul{margin-left: 24px;}
		span{color: indianred;
			border: 1px solid yellow;
			text-decoration: blink;}
		.extra span{color: inherit;}
		</style>
</head>
<body>
	<em>Form</em>
	<p>Please fill out this form about what music you like.</p>

	<form method="post" action="">
		<p>Name:
		<input type="text" name = "name" value = ""></p>
		<p>Email Address:
		<input type="text" name = "name" value = ""></p>
		<h1>Genres you like:</h1>
		<input type="checkbox" name="Genre" value="Rock">Rock
		<input type="checkbox" name="Genre" value="Jazz">Jazz
		<input type="checkbox" name="Genre" value="Metal">Metal
		<input type="checkbox" name="Genre" value="Punk">Punk
		<input type="checkbox" name="Genre" value="Country">Country
		<input type="checkbox" name="Genre" value="Pop">Pop
		<input type="checkbox" name="Genre" value="Hiphop">Hiphop
		<h2>How did you learn about this form?</h2>
		<input type="radio" name="how" value="Facebook">Facebook
		<input type="radio" name="how" value="Instagram">Instagram
		<input type="radio" name="how" value="Line">Line
		<input type="radio" name="how" value="Friends">Friends
		<input type="radio" name="how" value="Other">Other
		<h3>Please rate us!</h3>
		<select name= "Rate">
		<option value="Not Bad">Not Bad</option>
		<option value="Good">Good</option>
		<option value="Couldn't Be Better">Couldn't Be Better</option>
		<option value="Not My Type">Not My Type</option>
		</select>
		<input type="Submit">
	</form>
</body>
</html>

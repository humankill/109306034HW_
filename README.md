<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
<table border="1">
	<thead>
	<tr>
		<th colspan="11">About me -- 109306034</th>
	</tr>
	<tr>
		<td rowspan="5">
			<img src="878685_user_512x512.png" alt="personal photo" width="200" height="200">
			<center><H5>personal photo</H5></center></td>



<tr>
	<td colspan="11"> </br></br>
		<form action="/action_page.php">
		<label for=" name"> Name:</label>
	<input type="text" id="name" name="name" maxlength="10">
	
	<p>Gender: <input type="radio" id="male" name="male" value="male">
	<label for="male" >Male </label>
	<input type="radio" id="female" name="female" value="female">
	<label for="female" >Female </label>
	<input type="radio" id="other" name="other" value="other">
	<label for="other" >Other </label></p></br>
	</td></tr>

<tr>
<td colspan="5"> </br>
 <form action="/action_page.php">
 <label for="county"> County:</label>
 <select name="county" id="county">
 	<option value="taipei">Taipei</option>
 	<option value="newtaipei">New Taipei</option>
 	<option value="keelung">Keelung</option>
 	<option value="kaohsiung">Kaohsiung</option>
 </select></br></br>
</td>
<td colspan="6"></br>
	<form action="/action_page.php">
		<label for="birthday">Birthday: </label>
	<input type="text" id="birthday" name="birthday" maxlength="10"></br></br></td>


<tr>
	<td colspan="11"></br> <form action="/action_page.php">
		<label for="email">E-mail:</label>
	<input type="text" id="email" name="email" maxlength="50"></br></br>
</td></tr>
</thead>

<tbody>
	<tr>
<td>Hobby</td>
	<td colspan="11">
		<form action="/action_page.php">
			<input type="checkbox" id="hobbies1" name="hobbies1" value= "Swimming">
			<label for="hobbies1"> Swimming</label>
			<input type="checkbox" id="hobbies2" name="hobbies2" value= "Volleyball">
			<label for="hobbies2">Volleyball</label>
			<input type="checkbox" id="hobbies3" name="hobbies3" value= "Movies">
			<label for="hobbies3">Movies</label>
			<input type="checkbox" id="hobbies4" name="hobbies4" value= "Games">
			<label for="hobbies4">Games</label>
			<input type="checkbox" id="hobbies5" name="hobbies5" value= "Sleeping">
			<label for="hobbies5"> Sleeping</label></tr>

<tr> 
	<td>Skill</td>
		<td colspan="11">
			<form action="/action_page.php">
			<input type="checkbox" id="skill1" name="skill1" value= "Java">
			<label for="skill1"> Java</label>
			<input type="checkbox" id="skill2" name="skill2" value= "HTML">
			<label for="skill2">HTML</label>
			<input type="checkbox" id="skill3" name="skill3" value= "Phyton">
			<label for="skill3">Phyton</label>
			<input type="checkbox" id="skill4" name="skill4" value= "Microsoft Office">
			<label for="skill4">Microsoft Office</label>
			<input type="checkbox" id="skill5" name="skill5" value= "Adobe Premiere">
			<label for="skill5">Adobe Premiere</label></tr>


<tr>
	<td rowspan="3">Say Something</td>
		<td colspan="11">
			<textarea id="comments" name="comments" rows="4" cols="50">Say something here.
	</textarea></tr>
</tbody>
<tbody>
<tr>
	<th colspan="11">
		<input type="submit" value="Submit">
		<input type="reset" value="重設">
	</th></tr>
</tbody>


</body>
</html>

<html>
<head>
	<title></title>
	<style>
.mydiv{
	border: 5px;
	background-color:#998e90;
	text-align: center;
}
.mydiv1{
	border: 5px;
	background-color: #b8bec2;
	text-align: center;
}
.mydiv2{
	border: 5px;
	background-color: #999999;
	text-align: center;
}
</style>
</head>
<body>
	<p class="para" style="font-size: 50px"><strong>Welcome to National Institute of Technology Patna!</strong></p>
	<h1 align="center">REGISTRATION</h1>
	<div class="mydiv">
	<form>
		<fieldset>
			<legend>Basic details</legend>
			<table>
				<tr><td>Form Number</td><td><input type="text" name="Form Number"></td></tr>
				<tr><td>Name</td><td><input type="text" name="Name"></td></tr>
				<tr><td>Roll Number</td><TD><input type="Number" name="Roll Number"></TD></tr>
				<tr><td>Gender</td><td>male<input type="radio" value="male" name="Gender">female<input type="radio" value="female" name="Gender"></td></tr>
				<tr><td>DOB</td><td><input type="date" name="DOB"></td></tr>
				<tr><td>PWD</td><td>Yes<input type="radio" value="Yes" name="PWD">No<input type="radio" value="No" name="PWD"></td></tr>
				<tr><td>Category</td><td><select value="">
					<option value="GEN">GEN</option>
					<option value="OBC">OBC</option>
					<option value="SC">SC</option>
					<option value="ST">ST</option>
				</select></td></tr></table>
				<table>
				<tr><td>ADDRESS</td></tr>			   
               <tr><td><textarea rows="5" cols="50" maxlength="10"></textarea></td></tr>
                <br>
				<tr><td>PLEASE INPUT CORRECT PINCODE</td></tr>
				<tr><td>PINCODE</td>&nbsp<td><input type="number" name="PIN
				"></td></tr>	
				<tr><td>PHONE NUMBER OF STUDENT</td><td><input type="number"></td></tr>
				<tr><td>PHONE NUMBER OF FATHER/MOTHER/GUARDIAN</td><td><input type="number"></td></tr>
			</table>
		</fieldset>
	</form>
</div>
<div class="mydiv1">
<form>
	<fieldset>
			<legend>ACADEMIC DETAILS</legend>
			<table>
<tr><td>course</td><td><select value="">
	<option value="btech">btech</option>
	<option value="mtech">mtech</option>
	<option value="mtech(dual)">mtech(dual)</option>
	<option value="barch">barch</option>
	<option value="Intmsc">Intmsc</option>
	<option value="phd">phd</option>
</select></td></tr>
<tr><td>Branch</td><td><input type="text" name="Branch"></td></tr>
<tr><td>Semester</td><td><select value="">
	<option value="1st">1st</option>
	<option value="2nd">2nd</option>
	<option value="3rd">3rd</option>
	<option value="4th">4th</option>
</select><small>(for which allotment will be done)</small></td></tr>
<tr><td>All India Rank</td><td><input type="number" name="All India Rank"><small>(2020JEE MAIN RANK/GATE</small></td></tr>
<tr><td>Category Rank</td><td><input type="number" name="Category Rank"><small>(2020JEE MAIN RANK/GATE</small></td></tr>
<tr><td>CGPA</td><td><input type="number" name="CGPA"></td></tr>
<tr><td>Backlog</td><td>Yes<input type="radio" value="Yes" name="Backlog">No<input type="radio" value="No" name="Backlog"></td></tr>
<tr><td>Hostel accomodation</td><td>Yes<input type="radio" value="Yes" name="Hostel accomodation">No<input type="radio" value="No" name="Backlog"><small>(if any)</small></td></tr>
<tr><td>Name of Hostel</td><td><input type="text" name="Name of Hostel"></td></tr>
<tr><td>Room Number</td><td><input type="number" name="Room Number"></td></tr>
	</table></fieldset>
</form>
</div>
<div class="mydiv2">
	<form>
		<fieldset>
			<table>
			<legend>Account details for refunding process</legend>
			<tr><td>Account Holder Name</td><td><input type="text" name="Account Holder Name"><small>(AS PER BANK PASSBOOK)</small></td></tr>
			<tr><td>Account Number</td><td><input type="number" name="Account Number"></td></tr>
			<tr><td>IFSC code</td><td><input type="number" name="IFSC code"></td></tr>
			<tr><td>Bank Name</td><td><input type="text" name="Bank Name"></td></tr>
			<tr><td>Bank Branch</td><td><input type="text" name="Bank Branch"></td></tr>
         </table>
		</fieldset>
	</form>
</div>
 <tr>
      <td><input type="submit" value="Submit and Continue">&nbsp&nbsp<input type="reset" value="Reset"></td>
   </tr>
</body>
</html>

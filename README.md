<html>
<head>
<title>HTML Table</title>
</head>
<body>
<form method=""action="">
<table border="1" align="Center" width="400" bgcolor="#CCCCCC">
<caption>Registration Form</caption>
<tr>
<th>Enter First Name</th>
<td><input type="text" name="fn" id="fn1" maxlength="10" title="Enter Your First Name"
placeholder="Enter Your First Name"required/></td>
</tr>
<tr>
<th>Enter Last Name</th>
<td><input type="text"/></td>
</tr>
<tr>
<th>Enter Password</th>
<td><input type="password"/></td>
</tr>
<tr>
<th>Reenter
Password</th>
<td><input type="password"/></td>
</tr>
<tr>
<th>Enter Email</th>
<td><input type="email"/></td>
</tr>
<tr>
<th>Enter Mobile number</th>
<td><input type="number"/></td>
</tr>
<tr>
<th>Enter Address</th>
<td><textarea rows="8" cols="20"></textarea></td>
</tr>
<tr>
<th>Select Gender</th>
<td>
Male<input type="radio" name="g" value="m"/>
Female<input type="radio" name="g" value="f"/>
</td>
</tr>
<tr>
<th>Select your Hobbies</th>
<td>
Hobby1<input type="checkbox" name="x[]" value="h"/>
Hobby2<input type="checkbox" name="x[]" value="h2"/>
Hobby3<input type="checkbox" name="x[]" value="h3"/>
</td>
</tr>
<tr>
<th>Select Date Of Birth</th>
<td><input type="date"/></td>
</tr>
<tr>
<th>Select Country</th>
<td>
<select name="Country">
<option value="" selected="Selected" disabled="Disabled"> Select your country </option>
<option value="1">India</option>
<option value="2">Sri Lanka</option>
<option value="3">Australia</option>
<option value="4">Italy</option>
<option value="5">Japan</option>
</select>
</td>
</tr>
<tr>
<th>Upload your Image</th>
<td><input type="File"/></td>
</tr>
<tr>
<td colspan="2" align="Center"><input type="Submit" value="Save My Data"/>
<input type="Reset" value="Reset Data"/>
</td>
</tr>
</table>
</form>
<hr>

</body>
</html>

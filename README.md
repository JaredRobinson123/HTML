# HTML
<!DOCTYPE html>
<html>
<head>
<h1 style="text-align:center;">WorkSpace Transfer Form</h1>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<hr>
<p><b>The Following Form is to be submitted only for Workspace Transfers. Please
fill all promots fully.</p>

</style>
a:hover {
    color: red;
    background-color: transparent;
    text-decoration: underline;
}
a:active {
    color: purple;
    background-color: transparent;
    text-decoration: underline;
}
</style>
<p>Please check which box applies to your situation.</p>
<form>
	<input type="radio" name="option1" value="Will">I am willing to Comprmise<br>
	<input type="radio" name="option2" value="Willnot"> I am not willing to Comprmise<br>
<br> 
  Select the day you would like to meet and discuss. Must be 3+ Days in advance
  Day To Discuss:
  <input type="date" name="Meeting">
<p>Below please select the following reason(s) for you coming to this form.</p>
	<input type="checkbox" name="Reasoning" value="Reasoning" checked> Noisy<br>
	<input type="checkbox" name="Reasoning" value="Reasoning">Disruptive<br>
	<input type="checkbox" name="Reasoning" value="Reasoning">Inefficnet<br>	
	<input type="checkbox" name="Reasoning" value="Reasoning">PersonalReasons<br>
	<input type="checkbox" name="Reasoning" value="Reasoning">Other<br>
</form>

<br>

<br>
First name:<br>
<input type="text" name="firstname">
<br>
Last name:<br>
<input type="text" name="lastname">
<br>
Current Workspace:<br>
<input type="text">
<br>
Desired Workspace:<br>
<input type="text">
<br>
Reasoning:<br>
<input type="text" name="Noisy">
<br>
Comments(Define if you selected other):<br>
<input type="text" name="lastname">
<br>
<input type="submit" value= "Submit">
</form>

<form action="/WorkSpaceTransfer" method="post">


<a href="http://jaredrobinson.freeasphost.net/" target="_blank">Restart Transfer Form</a> 

</body>
</html>

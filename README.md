# eircode

-Simple Javascript .length calculator to ensure correct entry of eircode.
- Completed during 2016-2018 in Bsc Information Systems 

=================================================================================================================================================================================


<html>
<head>

<title>String Functions</title>
<script>
//check eircode

var EirCode;
function EnterEirCode()
{
	EirCode = prompt( "Please Enter Your Eir Code", "e.g H87 X4RD");
}
function CheckEirCode(EirCode)
{
	if (EirCode.length >=8)
	return true
	else
	return false
}

</script>
</head>
<body>
<script>
EnterEirCode()
// calculates characters
while (!CheckEirCode(EirCode))
{
	alert("Eir Code Has Too Few Characters.");
	EnterEirCode();
}

alert("Thanks For Entering Your Eir Code.");
document.write("Goodbye");

</script>
</body>
</html>

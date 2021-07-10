# javascript-calculator
JavaScript Addition and Subtraction
<body>
		<p id="demo"></p>
	<script>
		var num1= prompt("Enter the first number :");
		var num2= prompt("Enter the second number:");

		num1= parseInt(num1, 10);
		num2= parseInt(num2, 10);
		var sum, sub;
		   sum= num1+num2;
		document.write("Addition =" +sum );
		sub= num1-num2;
		document.getElementById("demo").innerHTML= ("subtraction :" +sub);

	</script>
	</body>

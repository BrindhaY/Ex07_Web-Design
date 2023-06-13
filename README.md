# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
<script type="text/javascript">
function calc() {
  var a = parseInt(prompt("Enter 1st Value"));
  var b = parseInt(prompt("Enter 2nd Value"));
  var op = parseInt(prompt("Enter Operation to Perform: \n1. Addition \n2. Subtraction \n3. Multiplication \n4. Division"));
  var d;
  
  if (op === 1) {
    d = a + b;
    alert("Result: " + d);
  } else if (op === 2) {
    d = a - b;
    alert("Result: " + d);
  } else if (op === 3) {
    d = a * b;
    alert("Result: " + d);
  } else if (op === 4) {
    d = a / b;
    alert("Result: " + d);
  } else {
    alert("Invalid Operation");
  }
}
</script>
</head>
<body onload="calc()">

<h1>Simple Calculator</h1>
<hr color="red">
<p>Enter option for performing the corresponding operation:</p>
</body>
</html>

## OUTPUT
![Screenshot (43)](https://github.com/BrindhaY/Ex07_Web-Design/assets/127816765/ce1c7941-2755-4dc6-9ae0-5d3e7c5fbb59)
![Screenshot (44)](https://github.com/BrindhaY/Ex07_Web-Design/assets/127816765/7b488a3f-1fe1-4346-aab8-718cf5a700f0)
![Screenshot (45)](https://github.com/BrindhaY/Ex07_Web-Design/assets/127816765/7af7bfc0-9d0f-4608-ada6-ed327578e555)
![Screenshot (46)](https://github.com/BrindhaY/Ex07_Web-Design/assets/127816765/b1c45067-2331-444b-b5d5-31b21d03e283)
![Screenshot (47)](https://github.com/BrindhaY/Ex07_Web-Design/assets/127816765/c5f1eb06-1a6d-4262-87e1-a3da535944b1)

## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.

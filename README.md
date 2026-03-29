# week-3-js
<!DOCTYPE html>
<html>

<head>
    <title>Boolean Assignment</title>
</head>

<body>
    <input type="text" id="input1" placeholder="Input 1">
    <input type="text" id="input2" placeholder="Input 2">
    <br></br>
    <button onclick="checkBooleans()">Booleans values</button>
    <h3 id="result"></h3>

    <script>
        function checkBooleans() {
            var input1 = document.getElementById("input1").value;
            var input2 = document.getElementById("input2").value;
            //compare values
            let result = (input1 === input2);
            document.getElementById("result").innerText = result;
            console.log('input_1=', input1, 'type =', typeof input1);
            console.log('input_2=', input2, 'type =', typeof input2);
            console.log('result=', result, 'type =', typeof result);
        }
    </script>
</body>

</html>

# javascripttt
//first question answer

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var x = parseInt (prompt("enter your age: "))
        if(x<18){
            alert("you are teenage.")

        }
        else if(x>=18 && x<65){
alert("you are adult")
        }
        else if(x>=65){

            alert("senior citizen")
        }

    </script>
    
</body>
</html>


//2. second question answer

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var number1 = 0;
        var number2 = 1;
        var sum = 0;
        
        for(var i=0;i<10;i++){
            console.log(sum);
            number1 = number2;
            number2 = sum;
            sum = number1 + number2;
        }

    </script>
</body>
</html>


//3rd question answer







# homeworkforclass-Iforgot- code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        //question 1
        var ArrayOrNo = function(input) {
          if (toString.call(input) === "[object Array]")
        return true;
        return false;   
        };
        console.log(ArrayOrNo([1,2,3,54]));
        //question 2
        fruits = ["orange", "apple", "grape"];
        console.log(fruits.toString());
        console.log(fruits.join());
        console.log(fruits.join('$'));
        //question 4
        var array = [1,2,3,4,5]

        var sum = 0;
        for(var i=0; i<array.length;i++){
        sum+= array[i]
        }

        console.log(sum); 
        //question 5
        var array = [1,2,3,4,5]
        var sum = 0;
        for(var i=0; i<array.length;i++){
        sum*= array[i]
        }
        console.log(sum); 
        //q6
        var arr = ["peter","james","bob","peter"];
        arr = arr.filter(function(item,index,inputArray) {
        return inputArray.indexOf(item) == index;
        });
        




        
    </script>
      
</body>
</html>

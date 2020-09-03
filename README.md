# Lets-Upgrade-Javascript
DAY 1 ASSIGNMENT
Question 1
Program to search for a particular character in a string
<!DOCTYPE html> 
<html>
  <body>
      <p id="GFG"></p> 
        <script type="text/javascript "> 
            var str = "Welcome to GeeksforGeeks."; 
            var check = str.includes("o", -2); 
            document.getElementById("GFG").innerHTML = check;
       </script> 
    </body> 
</html> 
Question 2
Program to convert minutes to seconds
<html >
<body >
<script type ="text /javascript ">
function secondsToMinutes(time)
{
    return Math.floor(time / 60)+':'+Math.floor(time % 60);
}
</script >
/body >
</html >
Question 3
Program to search for a element in a array of strings
<html>
<body>
<script type="text/javascript">
var strs = ['abc', 'def', 'ghi', 'jkl', 'mno'];
var value = 'abc';
strs.find(
    function(str) 
  {
        return str == value;
    }
);
</script>
</body >
</html>
Question 4
Program to display only elements containing 'a' in them from a array
<html >
<body >
<script type ="text/javascript ">
function contains(arr, element) 
{
    for (var i = 0; i < arr.length; i++) {
        if (arr[i] === element) {
            return true;
        }
    }
    return false;
}
arr = ["b", "c", "a", "k"];
console.log(contains(arr, "a"));
</script >
</body >
</html >
Question 5
Print an array in reverse order
<html>
<body >
<script type ="text /javascript ">
var a=[1,2,3,4,5];
a.reverse();
</script >
</body >
</html >

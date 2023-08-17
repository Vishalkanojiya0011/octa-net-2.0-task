<html>
<body>
<p> To Do list of task</p>
<button onclick="myfunction()">Add Task</button>
<p id="demo"></p>
<script>


function myfunction()
{
var x="";
for(var i=0;i<5;i++)
{
x=x + "Task number is" +i+"<br>";
}
doucument.getElementById("demo").innerHTML=x;
}
</script>
</body>
</html>

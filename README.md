# Project
<!DOCTYPE html>
<html>
<head>
<title>Fibonacci series Demo</title>
<script language="javascript">
var a=0,b=1,c,n,i;
n=parseInt(prompt("Enter limit for fibonacci series:",""));
document.write("<h2> Fibonacci series: </h2><br>");
document.write(a+" "+b+" "); 
for(i=2;i<n;i++)
{
c=a+b;
document.write(c+" ");
a=b;
b=c;
}
</script>
</head>
<body>
</body>
</html> 

 

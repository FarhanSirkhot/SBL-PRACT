Use of Basic Tags:-
a.Design a web page using different text formatting tags 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>different text formatting tags</title> 
</head>
<body>
<hgroup>
<h1>heading1</h1> 
<h2>heading2</h2>
</hgroup>
<p>the gardener poem says,...</p> 
<blockquote>
silly gardener!summer goes<br>
and winter comes with pinching<br> 
when in the garden bare and brown<br> 
you must lay your barrow down<br>
</blockquote><br>
<b><i>hello friends</i></b>
h<sub>2</sub>so<sub>4</sub><br>
(a+b)<sup>2</sup>=a<sup>2</sup>+2ab+b<sup>2</sup><br> 
h<sub>2</sub>o<br>
<kbd>hello</kbd><br>
<code>hello</code><br>
<samp>hello</samp><br><br>
<pre>hello friends           how are you? I  am fine and I hope you will also fine. 
</pre><br><br>
</body> 
</html>

b.Design a web page with links to different pages and allow navigation between web pages.
a.   Create page one.html having a link to two.html, create two.html having a link to 
three.html. Print “Welcome to Hyperlinks” in three.html.
b.   Create an html page and demonstrate “Hyperlinking to anchor” i.e. linking within 
the same page using the concept of bookmarks/anchors.
A:
One.html
<!DOCTYPE html> 
<html>
<haed>
<title>One</title> 
</head>
<body>
<a href="two.html">Go to Two.html</a> 
</body>
</html>Two.html
<!DOCTYPE html> 
<hrtml>
<head>
<title>Two</title> 
</head>
<body>
Welcome to two.html. 
<br>
<a href="three.html">Go to three.html</a> 
</body>
</html>
Three.html
<!DOCTYPE html> 
<hrtml>
<head>
<title>Three</title> 
</head>
<body>
Welcome to Hyperlinks. 
</body>
</html> 
B:
<!DOCTYPE html> 
<html>
<head>
<title>linking within the same file</title> 
</head>
<body>
<a name="top">top region</a> 
<br>
<a href="#bottom">go to bottom</a> 
<!—add large texual content-->
<a name="bottom">bottom region</a> 
<br>
<a href="#top">go to top</a> 
</body>
</html>

c.Design a web page demonstrating all Style sheet types:
Generate a nested list as follows: (Display Fruits and Vegetables in “red” font color using inline 
style, Display Mango, Banana and Apple in font color “Blue” and Tomato, Potato and Carrot in 
font color “Yellow” using internal stylesheet, set background color for Fruits and Vegetables to 
pink using external stylesheet). Hint: use id/class attributes and/or styles for nested tags.
▪         Fruits
I.       Mango
II.       BananaIII.       Apple 
a.   Vegetables
IV.       Tomato
V.       Potato
VI.       Carrot
Main.html:
<!DOCTYPE html>
<html>
<head>
<title>nested lists</title> 
<style type="text/css"> 
.fruits{color:blue}
.vegetables{color:yellow} 
</style>
<link rel="stylesheet" type="text/css" href="one.css"> 
</head>
<body>
<ul style="list-style-type:filled square">
<li class="bg" style="color:red">fruits</li>
<ol style="list-style-type:upper-roman">
<li class="fruits">banana</li>
<li class="fruits">apple</li>
<li class="fruits">mango</li>
</ol>
</ul>
<ol style="list-style-type:lower-alpha">
<li class="bg" style="color:red">vegetables</li>
<ol class="grp1" start="4" style="list-style-type:uppper-roman">
<li class="vegetables">tomato</li>
<li class="vegetables">potato</li>
<li class="vegetables">carrot</li>
</ol>
</ol> 
</body>
</html> 
One.css
.bg{background-color:pink}

2.a.Design a web page with Imagemaps. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>ImageMap</title> 
</head>
Image maps, Tables, Forms and Media<body>
<map name="m1">
<area shape="poly" coords="355,367,390,262,424,367" href="first.html"> 
<area shape="circle" coords="305,216,44" href="one.html">
<area shape="circle" coords="496,213,38" href="two.html">
<area shape="rectangle" coords="278,407,473,443" href="three.html"> 
</map>
<img src="face.png" usemap="#m1">
</body> 
</html>

b.Design a web page demonstrating different semantics:
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Semantic Example</title> 
</head>
<body>
<header>
<img src="garden.jpg" style="float:left; height:80px;width:60"> 
<h1>The Garden Company</h1>
<h5 style="clear:left">Helping your garden grow</h5>
</header>
<nav>
<hr>
<a href="one.html"><img src="home.jpg"></a>
<a href="lists.html"><img src="about.jpg"></a>
<a href="link.html"><img src="contact.jpg"></a>
</hr>
</nav>
<article>Welcome to Home Page<br>
</article>
We are expert in Gardening. 
</article>
<aside>
<b>what does<i>mean?</i></b>
run into an unfamiliar gardening term? 
</aside>
<footer>
<hr style="height:5px"> 
copyright &copy; 2012
</footer> 
</body>
</html>

c.Design a web page with different tables. Design a webpages using table so that the content 
appears well placed.
Code:<!DOCTYPE html> 
<html>
<head>
<title>Layout with table</title> 
</head>
<body>
<a href="http://www.contoso.com" title="Home page"> 
<img src="images/leaf.gif" class="logo"></a>
<h1>The Garden Company</h1>
<h5><i>Helping you help your gardens grow since 1975</i></h5> 
<hr>
<table> 
<tr>
<td style="width: 150px">
<p style="margin:0px">
<a href="index.htm"><img src="images/btn_home.gif" 
style="border:none"></a>
<a href="tips.htm"><img src="images/btn_tips.gif" 
style="border:none"></a>
<a href="contact.htm"><img src="images/btn_contact.gif" 
style="border:none"></a></p>
</td> 
<td>
shipment 
healthy
</tr> 
</table> 
</html>
</td>

d.<p><img src="images/peaches.jpg" style="float: right; padding: 10px"> 
<b>Fruit trees are now in stock! </b>We have just received a large 
of peach, pear, apple, and plum trees with sturdy root systems and 
foliage, with prices as low as $29.99. Visit the <a href="products.htm">
Products</a> page for details.</p>

Design a web page with a form that uses all types of controls 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Password Input Control</title> 
</head>
<body> 
<form >
User ID :  <input type="text" name="user_id" /> 
<br>
Password:  <input type="password" name="password" /> 
<br>Description : <br />
<textarea rows="5" cols="50" name="description"> 
Enter description here...
</textarea>
<br>
<input type="checkbox" name="maths" value="on"> Maths
<input type="checkbox" name="physics" value="on"> Physics
<br>
<input type="radio" name="subject" value="maths"> Maths
<input type="radio" name="subject" value="physics"> Physics
<br>
<select name="dropdown">
<option value="Maths" selected>Maths</option> 
<option value="Physics">Physics</option>
</select> 
<br>
<input type="submit" name="submit" value="Submit" /> 
<input type="reset" name="reset"  value="Reset" /> 
<input type="button" name="ok" value="OK"  />
<input type="image" name="imagebutton" src="/html/images/logo.png" />
</form> 
</body> 
</html>

e.Design a web page embedding with multimedia features. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Multimedia</title> 
</head>
<body>
Video File: <video width="240" height="320" controls>
<source src="myvideo.ogv" type="video/ogg"> 
<source src="myvideo.mp4" type="video/mp4"> 
<source src="myvideo.avi" type="video/avi"> 
<embed src="myvideo.mp4">
</video> 
<br>
Audio File: <audio width="240" height="320" controls>
<source src="myaudio.ogv"> 
<source src="myaudio.mp4"> 
<source src="myaudio.avi"> 
<embed src="myaudio.mp4">
</audio>
</body> 
</html>

3.Java Script
a.Using JavaScript design, a web page that prints factorial/Fibonacci series/any given series. 
Factorial:
<!DOCTYPE html> 
<html>
<head>
<title>Factorial Demo</title> 
<script language="javascript">
var x=parseInt(prompt("Enter a number","")); 
var fact=1,i;
for(i=1;i<=x;i++) 
fact*=i;
document.write("<h1>Factorial of "+x+" is : "+fact+"</h1>"); 
</script>
</head>
<body>
</body>
</html>
Fibonacci:
<!DOCTYPE html> 
<html>
<head>
<title>Fibonacci series Demo</title> 
<script language="javascript">
var a=0,b=1,c,n,i;
n=parseInt(prompt("Enter limit for fibonacci series:","")); 
document.write("<h2> Fibonacci series: </h2><br>"); 
document.write(a+"  "+b+"  ");   
for(i=2;i<n;i++) 
{
c=a+b;
document.write(c+"  "); 
a=b;
b=c; 
}
</script> 
</head>
<body> 
</body> 
</html>

b.Design a form and validate all the controls placed on the form using Java Script. 
<html>
<head>
<title>Form Validation</title> 
<script type="text/javascript">
function validate() 
{if( document.myForm.Name.value == "" ) 
{
alert( "Please provide your name!" ); 
document.myForm.Name.focus(); 
return false;
}
if( document.myForm.EMail.value == "" ) 
{
alert( "Please provide your Email!" ); 
document.myForm.EMail.focus(); 
return false;
}
if( document.myForm.Zip.value == "" ||isNaN( 
document.myForm.Zip.value ) ||
document.myForm.Zip.value.length != 5 )
{
alert( "Please provide a zip in the format #####." ); 
document.myForm.Zip.focus();
return false; 
}
if( document.myForm.Country.value == "-1" ) 
{
alert( "Please provide your country!" ); 
return false;
} 
return(true);
}
</script> 
</head>
<body>
<form name="myForm" onsubmit="return(validate());"> 
<table cellspacing="2" cellpadding="2" border="1"> 
<tr>
<td align="right">Name</td>
<td><input type="text" name="Name" /></td>
</tr> 
<tr>
<td align="right">EMail</td>
<td><input type="text" name="EMail" /></td>
</tr> 
<tr>
<td align="right">Zip Code</td>
<td><input type="text" name="Zip" /></td>
</tr> 
<tr>
<td align="right">Country</td> 
<td><select name="Country">
<option value="-1" selected>[choose yours]</option> 
<option value="1">USA</option>
<option value="2">UK</option> 
<option value="3">INDIA</option>
</select> 
</td>
<td align="right"></td>
<td><input type="submit" value="Submit" /></td>
</tr> 
<tr>
</tr> 
</table>
</form> 
</body> 
</html>

c.Write a JavaScript program to display all the prime numbers between 1 and 100. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>prime number</title> 
<script>
for(var i=1;i<=100;i++) 
{
var flag=0;
for(var j=2;j<=i/2;j++) 
{
if(i%j==0)
{
flag=1; 
break;
} 
}
if(flag==0) 
{
document.write(i+"<br>"); 
}
}
</script> 
</head> 
</html>

d.Write a JavaScript program to accept a number from the user and display the sum of its digits. 
Code:
<!DOCTYPE html> 
<html>
<head><title>sum of digits</title> 
<script>
var n=parseInt(prompt("Enter the number"," ")); 
var p=0,y;
while(n>0) 
{
y=n%10;
n=parseInt(n/10); 
p=p+y;
}
document.write("Sum of digits is: "+p); 
</script>
</head> 
</html>

e.Write a program in JavaScript to accept a sentence from the user and display the number of 
words in it. (Do not use split () function).
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Without using split function</title> 
<script>
var str=prompt("Enter the sentence=",""); 
var count=0;
for(i=0;i<str.length;i++) 
{
if(str.charAt(i,1)==" " && str.charAt(i+1,1)!=" ") 
count++;
}
document.write("Number of words are="+(count+1)); 
</script>
</head> 
<body> 
</body> 
</html>

f.Write a java script program to design simple calculator. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Calculator</title>
<script language="javascript"> 
function calc()
{
var n1,n2,opr,x;
n1=parseInt(f1.s1.value);n2=parseInt(f1.s3.value); 
opr=f1.s2.value;
if(opr=="add") 
x=n1+n2;
else if(opr=="sub") 
x=n1-n2;
else if(opr=="multi") 
x=n1*n2;
else if(opr=="div") 
x=n1/n2;
else
alert("please select operator");
document.getElementById("ans").innerHTML="answer is:"+x; 
}
</script> 
</head>
<body>
<form name="f1"> 
<table width=50%> 
<tr>
<td>Number1<br>
<select name="s1" size=1>
<option>Select</option>
<option value="0">0</option>
<option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
<option value="7">7</option>
<option value="8">8</option>
<option value="9">9</option> 
</select>
</td>
<td>Operator<br>
<select name="s2" size=1>
<option>Select</option>
<option value="add">+</option> 
<option value="sub">-</option> 
<option value="multi">*</option> 
<option value="div">/</option>
</select> 
</td>
<td>Number 2<br>
<select name="s3" size=1>
<option>Select</option>
<option value="0">0</option><option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
<option value="7">7</option>
<option value="8">8</option>
<option value="9">9</option> 
</select>
</td> 
<td>
<input type="button" value="calculate" onclick="calc()"> 
</td>
</tr> 
</table> 
</form>
<p id="ans"> </p> 
</body>
</html>


4.a.Control and looping statements and Java Script references
Design a web page demonstrating different conditional statements. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Conditional Statements</title> 
<script language="javascript">
var age = 20; 
if( age > 18 )
{
}
</script> 
</head>
<body> 
</body> 
</html>

b.document.write("<b>Qualifies for driving</b>");
Design a web page demonstrating different looping statements. 
Code:
<!DOCTYPE html> 
<html>
<head>
<title>Looping Statements</title>
<script language="javascript">
document.write("For Loop demo:<br>");for (i = 0; i < 5; i++) 
{
text1 += "The number is " + i + "<br>"; 
document.write(text1+" ");
}
document.write("<br>While Loop demo:<br>"); 
while (i < 10) 
{
text2 += "The number is " + i; 
document.write(text2+" "); 
i++;
}
document.write("<br>Do-While Loop demo:<br>"); 
do 
{
text3 += "The number is " + i; 
document.write(text3+" "); 
i++;
}while (i < 10); 
</script>
</head> 
<body> 
</body> 
</html>

c.Design a web page demonstrating different Core JavaScript references (Array, Boolean, Date, 
Function, Math, Number, Object, String, regExp).
Array object code: 
<!DOCTYPE html> 
<html>
<head>
<title>Array object Demo</title>
<script language="javascript">
var cars=["Saab","Volvo","BMW"];
document.write("Array length is: "+cars.length+"<br>"); 
document.write(cars.join["*"]);
cars.push("Opel");
document.write("After insert: "+cars.toString()); 
cars.pop();
document.write("After delete: "+cars.toString()); 
cars.sort();
document.write("After sort: "+cars.toString()); 
cars.reverse();
document.write("After reverse: "+cars.toString()); 
</script>
</head> 
<body></body>
</html>
Boolean object code: 
<!DOCTYPE html> 
<html>
<head>
<title>Boolean object demo</title> 
<script language="javascript"> 
function myFunction() 
{
document.getElementById("demo").innerHTML = Boolean(10 > 9); 
}
</script>
</head> 
<body>
<p>Display the value of Boolean(10 > 9):</p> 
<button onclick="myFunction()">Try it</button> 
<p id="demo"></p>
</body>
</html>
Date object code: 
<!DOCTYPE html> 
<html>
<head>
<title> Date object demo </title> 
<script language="javascript">
var currentDate =new Date(); 
document.write("Date is:");
document.write(currentDate.getMonth()+"/"+currentDate.getDate()+"/"+currentDate.g 
etFullYear
()+"<br>");
document.write("Time is:");
document.write(currentDate.getHours()+":"+currentDate.getMinutes
()+":"+currentDate.getSeconds()); 
</script>
<head>
<body>
</body>
</html>
Function object code: 
<!DOCTYPE html> 
<html><head>
<title> function object demo</title>
<script language="javascript">
addBraces=new Function("s","return'['+s+']'");
document.write(addBraces("this"));
document.write(addBraces("is"));
document.write(addBraces("a"));
document.write(addBraces("test")); 
</script>
</head>
<body>
</body>
</html>
Math object code: 
<!DOCTYPE html> 
<html>
<head>
<title>math object</title> 
<script language="javascript">
document.write("Random number: " +Math.random(3)+"<br>");
document.write("Minimum number: "+Math.min(150,0,-29,60)+"<br>");
document.write("Maximum number: "+Math.max(600,120,129,89)+"<br>");
document.write("Round(47.6): "+Math.round(47.6)+"<br>");
document.write("Ceil(4.4): "+Math.ceil(4.4)+"<br>");
document.write("Floor(4.7): "+Math.floor(4.7)+"<br>");
document.write("Square root of 2: "+Math.SQRT2+"<br>");
document.write("Square root of 1/2: "+Math.SQRT1_2+"<br>");
document.write("2 raise to 3: "+Math.pow(2,3)+"<br>"); 
</script>
</head>
<body>
</body>
</html>
Number object demo: 
<!DOCTYPE html> 
<html>
<head>
<title>Number object Demo</title> 
<script language="javascript">
document.write("Maximum value: "+Number.MAX_VALUE;); 
document.write("Minimum value: "+Number.MIN_VALUE;); 
var num1 = 5.56789;
document.write(num1.toFixed(2)); 
var num2 = 13.3714;
document.write(num2.toPrecision(2)); 
document.write(num1.toString());</script> 
</head>
<body>
</body>
</html>
Object object code: 
<!DOCTYPE html> 
<html>
<head>
<title> object demo </title>
<script language="javascript"> 
myobj1=new Object(123);
document.write(myobj1.toString()+"<br>"); 
myobj2=new Object("hello world"); 
document.write(myobj2.valueOf());
</script> 
</head>
<body> 
</body> 
</html>
String object demo: 
<!DOCTYPE html> 
<html>
<head>
<title>String object Demo</title> 
<script language="javascript">
var txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"; 
document.write(txt.length);
var x = 'It\'s alright';
var y = "We are the so-called \"Vikings\" from the north."; 
document.write(x + "<br>" + y);
var str = "Please locate where 'locate' occurs!"; 
var pos = str.indexOf("locate");
document.write(pos);
var str = "Please locate where 'locate' occurs!"; 
var pos = str.lastIndexOf("locate"); 
document.write(pos);
var str = "Please locate where 'locate' occurs!"; 
var pos = str.search("locate"); 
document.write(pos);
var str = "Apple, Banana, Kiwi"; 
var res = str.slice(7, 13); 
document.write(res);
var str = "Apple, Banana, Kiwi"; 
var res = str.substring(7, 13); 
document.write(res);var str = "Apple, Banana, Kiwi"; 
var res = str.substr(7, 6); 
document.write(res);
var str = "Please visit Microsoft!";
var n = str.replace("Microsoft", "W3Schools"); 
document.write(n);
var text1 = "Hello World!";       
var text2 = text1.toUpperCase(); 
document.write(text2);
var text1 = "Hello World!";       
var text2 = text1.toLowerCase(); 
document.write(text2);
var text1 = "Hello"; 
var text2 = "World";
text3 = text1.concat(" ", text2); 
document.write(text3);
var str = "HELLO WORLD"; 
documet.write(str.charAt(0));  
var str = "HELLO WORLD"; 
documet.write(str.charCodeAt(0));  
var txt = "a,b,c,d,e";         
var arr=txt.split(" ");  
document.write(arr[0]+" "+arr[2]);
</script> 
</head>
<body> 
</body> 
</html>
RegEx object demo: 
<!DOCTYPE html> 
<html>
<head>
<title>RegExp object Demo</title>
<script language="javascript">
var str = "Visit W3Schools!"; 
var n = str.search(/w3Schools/i); 
document.write(n);
var str = "Visit Microsoft!";
var res = str.replace(/microsoft/i, "W3Schools"); 
document.write(res);
text = "The best things in life are free!"; 
document.write(/e/.test(text));
text = "The best things in life are free!"; 
document.write(/e/.exec(text));
</script> 
</head>
<body></body> 
</html>

5.Basic PHP I
a.Write a PHP Program to accept a number from the user and print it factorial. 
Input.html
<html> 
<head>
<title>Factorial of a number</title> 
</head>
<body>
<form method="post" action=”Fact.php">
Enter a number: <input type="text" name="n1"><br> 
<input type="submit" value="Factorial">
</form> 
</body> 
</html>
Fact.php 
<?php
$n1=(int)$_POST['n1']; 
$fact=1;
for($i=1;$i<=$n1;$i++) 
{
$fact=$fact*$i; 
}
echo "Factorial of ".$n1." is: ".$fact; 
?>

b.Write a PHP program to accept a number from the user and print whether it is prime or not. 
Input.html
<html> 
<head>
<title>Prime Number</title> 
</head>
<body>
<form method="post" action="checkPrime.php">
Enter a number: <input type="text" name="n1"><br> 
<input type="submit" value="CheckPrime">
</form> 
</body> 
</html>
checkPrime.php 
<?php
$n1=(int)$_POST['n1']; 
$flag=0;
for($i=2;$i<=$n1/2;$i++){
if($n1%$i==0) 
{
$flag=1; 
break;
} 
}
if($flag==0)
else
?>
echo "Number is prime"; 
echo "Number is not prime";


6.a.Basic PHP II
Write a PHP code to find the greater of 2 numbers. Accept the no. from the user. 
Input.html
<html> 
<head>
<title>Greater of two no.s</title> 
</head>
<body>
<form method="post" action="check.php">
1st Number: <input type="text" name="n1"><br> 
2nd Number: <input type="text" name="n2"><br> 
<input type="submit" value="Check">
</form> 
</body> 
</html>
check.php 
<?php
$n1=(int)$_POST['n1']; 
$n2=(int)$_POST['n2']; 
if($n1>$n2)
echo $n1." is greater than ".$n2; 
else if($n2>$n1)
echo $n2." is greater than ".$n1; 
else
echo "Both the no.s are equal";
?>

b.Write a PHP program to display the following Binary Pyramid:
1
01
101
0101 
Code:
<?php
for($i=0;$i<4;$i++){
for($j=0;$j<=$i;$j++) 
{
if(($i+$j)%2==0) 
echo "1 ";
else
echo "0 ";
}
echo "<br>";
}
?>


7.a.String Functions and arrays
Write a PHP program to demonstrate different string functions. 
Code:
<?php
echo strlen("Hello");
echo strchr("Hello world!","world");
echo str_replace("world","Peter","Hello world!");
echo str_word_count("Hello world!");
echo strpos("I love php, I love php too!","php");
echo substr_count("Hello world. The world is nice","world");
echo substr("Hello world",6);
echo strtolower("Hello WORLD.");
echo strtoupper("Hello WORLD.");
echo strcmp("Hello world!","Hello world!");
echo strcasecmp("Hello world!","Hello world!"); 
?>

b.Write a PHP program to create one dimensional array. 
Code:
<?php
$cars = array("Volvo", "BMW", "Toyota");
echo "I like " . $cars[0] . ", " . $cars[1] . " and " . $cars[2] . "."; 
echo count($cars);
$arrlength = count($cars);
for($x = 0; $x < $arrlength; $x++) 
{
echo $cars[$x]; 
echo "<br>";
}
//Associative arrays
$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43"); 
echo "Peter is " . $age['Peter'] . " years old.";
?>

8.PHP and Database
a.Write a PHP code to create: 
•         Create a database College
•         Create a table Department (Dname, Dno, Number_Of_faculty) 
Code:
<?php
$con=mysql_connect("localhost","root",""); 
if(!$con)
die('could not connect:'.mysql_error());
if(mysql_query("create database College",$con)) 
echo"Database Created successfully";
else
echo "Error creating database:".mysql_error(); 
mysql_select_db("College",$con);
$query="create table department(dname varchar(50),dno smallint,no_of_faculty 
smallint)";
if(mysql_query($query,$con))
echo"Table Created successfully"; 
else
echo "Error creating table:".mysql_error(); 
mysql_close($con);
?>

b.Write a PHP program to create a database named “College”. Create a table named “Student” 
with following fields (sno, sname, percentage). Insert 3 records of your choice. Display the 
names of the students whose percentage is between 35 to 75 in a tabular format.
Code: 
<html> 
<head>
<title>Database insert and select</title> 
</head>
<body> 
<?php
$con=mysql_connect("localhost","root",""); 
if(!$con)
die('could not connect:'.mysql_error());
if(mysql_query("create database College",$con)) 
echo"Database Created successfully";
else
echo "Error creating database:".mysql_error(); 
mysql_select_db("College",$con);
$query="create table student(sno smallint,sname varchar(50),percentage 
decimal(7,2))";
if(mysql_query($query,$con))
echo"Table Created successfully"; 
else
echo "Error creating table:".mysql_error();
$query1="insert into student values(101,'Allen',78)";if(mysql_query($query1,$con))
echo"Record 1 inserted successfully"; 
else
echo "Error inserting record 1:".mysql_error(); 
$query2="insert into student values(102,'Smith',45)"; 
if(mysql_query($query2,$con))
echo"Record 2 inserted successfully"; 
else
echo "Error inserting record 2:".mysql_error(); 
$query3="insert into student values(103,'Scott',63.2)"; 
if(mysql_query($query3,$con))
echo"Record 3 inserted successfully"; 
else
echo "Error inserting record 3:".mysql_error();
$sql="select * from student where percentage>=35 and percentage<=75"; 
$result=mysql_query($sql,$con);
if(mysql_num_rows($result)>0) 
{
echo "<table 
border='1'><tr><th>Sno</th><th>Sname</th><th>Percentage</th></tr>";
while($row=mysql_fetch_assoc($result)) 
{
echo "<tr>";
echo "<td>".$row['sno']."</td>";
echo "<td>".$row['sname']."</td>";
echo "<td>".$row['percentage']."</td>";
echo "</tr>"; 
}
echo "</table>"; 
}
else 
{
echo "Table is empty"; 
}
mysql_close($con); 
?>
</body> 
</html>

c.Design a PHP page for authenticating a user. 
Input.html
<html> 
<head>
<title>User authentication</title> 
</head>
<body>
<form method="post" action="validate.php"> 
Username: <input type="text" name="t1"><br>Password: <input type="password" name="p1"><br> 
<input type="submit" value="Submit">&nbsp;
<input type="reset" value="Clear"> 
</form>
</body> 
</html>
validate.php: 
<?php
$user=$_POST['t1']; 
$pass=$_POST['p1'];
if($user=="abc" && $pass=="1234") 
echo "Welcome ".$user;
else
echo "Invalid username and password";
?>

Email
9.
a.
10
.
Write a program to send email with attachment.   
Code:
<?php
$to="someone@example.com"; 
$subject="test mail";
$message="Hello! This is simple email"; 
$from="someoneElse@example.com" 
$header="From:$from";
mail($to,$subject,$message,$header); 
echo "Email sent";
?>

a.Sessions and Cookies
Write a program to demonstrate use of sessions and cookies. 
Session code:
<?php
session_start();
if(isset($_SESSION['views'] ) ) 
$_SESSION[' views '] += 1;
else
$_SESSION[' views '] = 1;
$msg = "You have visited this page ".  $_SESSION[' views ']; 
$msg .= "in this session";
?>
Cookie code (Setting and Retrieving): 
<?php
$cookie_name = "user";$cookie_value = "John Doe";
setcookie($cookie_name, $cookie_value, time() + (86400 * 30), "/"); // 86400 = 1 day
?>
<html> 
<body> 
<?php
if(!isset($_COOKIE[$cookie_name])) 
{
echo "Cookie named '" . $cookie_name . "' is not set!"; 
}
else 
{
echo "Cookie '" . $cookie_name . "' is set!<br>"; 
echo "Value is: " . $_COOKIE[$cookie_name];
}
?> 
</body> 
</html>

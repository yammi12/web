1. Write a HTML code to demonstrate 
   a. Various formatting tags,
   b. Ordered and unordered list, 
   c. And table using frames suitably.

   
        a)    
Various formatting tags
<html>
<head>
<title>formatting tags</title>
</head>
<body>
<b>This text is bold</b><br>
<strong>This text is important!</strong><br>
<i>This text is italic</i><br>
<em>This text is emphasized</em><br>
<small>This is some smaller text.</small><br>
<p>Do not forget to buy <mark>milk</mark> today.</p>
<p>My favorite color is <del>blue</del> red.</p>
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
<p>This is <sub>subscripted</sub> text.</p>
<p>This is <sup>superscripted</sup> text.</p>
</body>
</html>


         b)
Ordered List
<html>
<body>
<h4>Numbered list:</h4>
<ol>
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ol>  
<h4>Letters list:</h4>
<ol type="A">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ol>  
<h4>Lowercase letters list:</h4>
<ol type="a">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ol>  
<h4>Roman numbers list:</h4>
<ol type="I">
 <li>Apples</li>
 <li>Bananas</li><li>Lemons</li>
 <li>Oranges</li>
</ol>  
</body>
</html>
Unordered list
<html>
<body>
<h4>Disc bullets list:</h4>
<ul type="disc">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
<h4>Circle bullets list:</h4>
<ul type="circle">
 <li>Apples</li>
li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
<h4>Square bullets list:</h4>
<ul type="square">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
</body>
</html>Unordered list
<html>
<body>
<h4>Disc bullets list:</h4>
<ul type="disc">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
<h4>Circle bullets list:</h4>
<ul type="circle">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
<h4>Square bullets list:</h4>
<ul type="square">
 <li>Apples</li>
 <li>Bananas</li>
 <li>Lemons</li>
 <li>Oranges</li>
</ul>  
</body>
</html>


2. Develop and demonstrate a XHTML document that illustrates the use external style  sheet, ordered list, table, borders, padding, color, and the <span> tag.
 
 <?xml version = "1.0" encoding = "utf-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
"http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns = "http://www.w3.org/1999/xhtml">
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css" />
<title> Lab program1 </title>
</head>
<body bgcolor="pink">
<h2> <center> CURRICULUM VITAE </center> </h2><hr>
<img src="stone_bird.jpg" align="right" width="100" height="50" border="3" />
<h3> Qualification details: </h3>
<table border="3" > <!-- table with some information -->
<tr>
<th>Qualification </th>
<th>Board</th>
<th>Pass out</th>
<th>Percentage</th>
<th>Class</th>
</tr>
<tr>
<td >B.E</td>
<td>VTU</td>
<td>2008</td>
<td>65 %</td>
<td>FC</td>
</tr>
<tr>
<td >P.U.C</td>
<td>K.S.E.B</td>
<td>2004</td>
<td>60 %</td>
<td>FC</td>
</tr>
<tr>
<td >S.S.L.C</td>
<td>K.S.E.B</td>
<td>2000</td>
<td>65 %</td>
<td>FC</td>
</tr>
</table>
<hr> <!-- horizontal line -->
<h3>Personel Information:</h3>
<h3>
<ol> <!-- ordered list -->
<li>Name :Viyay</li>
<li>DOB :20-03-1985</li>
<li>Nationality :Indian</li>
<li>Religion :Hindu</li>
</ol>
</h3>
<hr />
<p><span>This is WP lab</span> Welcome to web programming lab <span>This is WP 
lab</span></p>
</body>
</html>
// mystyle.css
p,table,li {
font-family: "lucida calligraphy"; margin-left: 10pt;
}
p {
word-spacing: 5px;
}
body {
background-color:rgb(100,255,205); } p,li,td  {
font-size: 75%;
}
td  
{
}
th  
{
}
padding: 0.5cm;
text-align:center; font-size: 85%;
h1, h2, h3, hr {
color:#483d8b;
}
table {


border-style: solid; background-color: rgb(200,100,105);
}
li
{
}
list-style-type: upper-alpha;
span { color:blue;
background-color:pink; font-size: 15pt;
font-style: italic; font-weight: bold;
}


3. Develop and demonstrate a XHTML file that includes JavaScript script for the  following problems:
Input : A number n obtained using prompt
Output: The first n Fibonacci numbers

<?xml version = "1.0" encoding = "utf-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" 
"http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<!-- lab2a.html -->
<html xmlns = "http://www.w3.org/1999/xhtml">
<head>
<title>Program 2a</title>
<script type="text/javascript"> var fib=0,fib1=0,fib2=1;
var num = prompt("Enter a number ", " "); if(num!=null && num>0)
{
document.write("<h1>" + num + " Fibonacci are <br/>"+"</h1>"); if(num==1)
document.write("<h1> "+ fib1 + "</h1>"); else
document.write("<h1>" + fib1 + "<br />"+ fib2 + "</h1>"); for(i=3;i<=num; i++)
{
fib = fib1 + fib2;
document.write("<h1> " + fib + "</h1>"); fib1=fib2;
fib2=fib;
}
}
else
alert("No Proper Input");
</script>
</head>
<body bgcolor="maroon" text="white" >
</body>
</html>


4. Design an XML document to store information about a student in an engineering  college affiliated to VTU. The information must include USN, Name, Name of the College, Brach, Year of Joining, and e- mail id. Make up sample data for 3 students. 
Create a CSS style sheet and use it to display the document.

3a.xml
<?xml version = "1.0"?>
<?xml-stylesheet type = "text/css" href = "6a.css" ?>
<students>
<VTU>
<USN> 1HK07CS001 </USN>
<name> Chulbul Panday</name>
<college> HKBKCE </college>
<branch> CSE</branch>
<YOJ> 2007 </YOJ>
<email> chulbul_pandey@gmail.com </email>
</VTU>
<VTU>
<USN> 1HK07CS002</USN>
<name> Makhi Pandey</name>
<college> HKBKCE </college>
<branch> CSE </branch>
<YOJ> 2007 </YOJ>
<email> makhi_pandey@gmail.com </email>
</VTU>
<VTU>
<USN> 1HK07CS003</USN>
<name> Ched Singh</name>
<college> HKBKCE </college>
<branch> CSE </branch>
<YOJ> 2007</YOJ>
<email> ched_singh@yahoo.com </email>
</VTU>
</students>
3a.css
Students { background-color: #ffffff; width: 100%; }
VTU { display: block; margin-bottom: 30pt; margin-left: 0; }
USN { color: #FF0000; font-size: 20pt;  }
name { color: #0000FF; font-size: 20pt;  }
college, branch, YOJ { display: block; color: #000000; margin-left: 20pt; }
email { background-color: #ffff22; margin-left: 40pt; color: #336633; }


5. Write a JavaScript code to compute the sum of n natural numbers

 <html>
<head>
<script type = "text/javascript">
    var num = window.prompt("Enter the number:","");
    var n = parseInt(num);
    result = sumnaturalno(n);
    window.alert("The sum of " + n + "natural number is" + result);
    function sumnaturalno(n)
    {
        var i;
        var sum = 0;
        for(i = 1;i <= n; i++){
            sum = sum + i;}
        return (sum);
    }
</script>
</head>
</html>

         PROGRAM 6 EXTERNAL JAVA FILE
         
message.js
function msg(){  
 alert("Hello Javatpoint");  
}  

<html>  
<head>  
<script type="text/javascript" src="message.js"></script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
/body>  
</html>  

              PROGRAM 7   FORM VALIDATION
<html>
<body>
<script>  
function validateform(){  
var name=document.myform.name.value;  
var password=document.myform.password.value;  
  
if (name==null || name==""){  
  alert("Name can't be blank");  
  return false;  
}else if(password.length<6){  
  alert("Password must be at least 6 characters long.");  
  return false;  
  }  
}  
</script>  
<body>  
<form name="myform" method="post" action="http://www.javatpoint.com/javascriptpages/valid.jsp" onsubmit="return validateform()" >  
Name: <input type="text" name="name"><br/>  
Password: <input type="password" name="password"><br/>  
<input type="submit" value="register">  
</form>  
</body>
</html>


            PROGRAM 8 EVENTS
<html>
<head> Javascript Events </head>
<body>
<script language="Javascript" type="text/Javascript">
	<!--
	function clickevent()
	{
		document.write("This is JavaTpoint");
	}
	//-->
</script>
<form>
<input type="button" onclick="clickevent()" value="Who's this?"/>
</form>
</body>
</html>











# WebTechnology

1. IMPLEMENTING BACKGROUND DESIGN, 
COLOR & TEXT TAGS. 
 
 
<Doctype html> 
    <html> 
        <head> 
            <title> WEB TECHNOLOGY </title> 
        </head> 
        <body> 
            <p> HTML STYLES </p> 
            <body style="background-color:yellow;"> 
                <h1 style="color:red;">WEB TECHNOLOGY</h1> 
                <p style="color:blue">I am implementing Background 
design,color,and Text tags in HTML</p> 
            </body> 
    </html>

    2. IMPLEMENTING IMAGE TAGS. 
 
<Doctype html> 
    <html> 
        <head> 
            <title> WEB TECHNOLOGY </title> 
        </head> 
        <body> 
            <p> HTML STYLES </p> 
                <img src="butterfly.jpg" 
                width="300px"height="200px"> 
                 </body> 
    </html>

    3. TO DISPLAY LIST OF ITEMS IN DIFFERENT 
STYLES. 
<html> 
    <head> 
        <title>list items</title> 
    </head> 
    <body> 
        <ul style="list-style-type: disc;"> 
             <h3>ul disc</h3> 
             <li>item1</li> 
             <li>item2</li> </ul> 
        <ul style="list-style-type: circle;"> 
             <h3>ul square</h3> 
             <li>item1</li> 
             <li>item2</li> </ul> 
        <ul style="list-style-type: square;"> 
             <h3>ul circle</h3> 
             <li>item1</li> 
             <li>item2</li></ul> 
        <ol type="1"> 
            <h3>ol type number</h3> 
            <li>item1</li> 
            <li>item2</li></ol> 
        <ol type="A"> 
            <h3>ol type upper character</h3> 
            <li>item1</li> 
            <li>item2</li> </ol> 
        <ol type="a"> 
            <h3>ol type lower character</h3> 
            <li>item1</li> 
            <li>item2</li> </ol> 
        <ol type="I"> 
            <h3>ol type upper roman</h3> 
            <li>item1</li> 
            <li>item2</li> </ol> 
        <ol type="i"> 
            <h3>ol type lower roman</h3> 
            <li>item1</li> 
          <li>item2</li></ol> 
          <dl> 
          <dt>DESCRIPTION LIST</dt>
          <dd>list1</dd> 
<dd>list2</dd> 
</dl> 
</body> 
</html>

4.IMPLEMENTING TABLE TAGS. 
 
<html> 
    <head><title>table tags</title></head> 
    <body> 
        <table border="1"> 
        <thead> 
            <tr> 
                <th>NAME</th> 
                <th>PAPER</th> 
                <th>MARK</th></tr> 
        </thead> 
        <tbody> 
            <tr> 
                <td rowspan="2">Harry</td> 
                <td>core</td> 
                <td>80</td></tr> 
            <tr> 
                <td>allide</td> 
                <td>90</td></tr> 
        </tbody> 
        <tfoot> 
            <tr> 
                <td rowspan="2">Mark</td> 
                <td>core</td> 
                <td>80</td></tr> 
            <tr> 
                <td>allide</td> 
                <td>75</td> 
            </tr> 
        </tfoot> 
        </table> 
    </body> 
</html> 
 
5.DEMONSTRATE THE USAGE OF INLINE, 
INTERNAL & EXTERNAL STYLE SHEET USING CSS. 
Inline Styles: 
<Doctype html> 
<html> 
<head> 
<title> WEB TECHNOLOGY </title> 
</head> 
<p> CASCADING STYLE SHEETS </p> 
<p style="color: red; font-size: 16px;">I am using inline styles in css </p> 
</body> 
</html>

:-Internal  Styles. 
<html> 
<head><title> WEB TECHNOLOGY </title> 
<style> 
p { color: blue; 
font-size: 18px;} 
</style></head> 
<body> 
<p> CASCADING STYLE SHEETS </p> 
<p>I am using internal styles in CSS.</p> 
</body> 
</html> 

:-External Styles: 
/* CSS rules in a separate file with a `.css` extension ,ex: styles.css */ 
p { 
color: green; 
font-size: 20px; 
} 
/* `<head>` section of  HTML document, add a `<link>` tag to link to the 
external CSS file.*/ 
<!DOCTYPE html> 
<html> 
<head> 
<link rel="stylesheet" type="text/css" href="styles.css"> 
</head> 
<body> 
<p>I am using External Style Sheets in CSS.</p> 
</body> 
</html>

6. IMPLEMENTING JAVA SCRIPT IN HTML 
<html> 
<head> 
<title>Java Script in HTML</title> 
<script> 
function speak() 
{ 
alert("this is my first javascript program") 
} 
</script> 
</head> 
<body> 
<button onclick="speak()">click me</button> 
</body> 
</html>

7.  HOT TEXT USING HYPERLINK TAGS. 
<html> 
<head> 
<title> Hot Text Example</title> 
</head> 
<body>  
<p>click on the college name to find it's website</p> 
<p> 
<a href="https:www.psgrkcw.ac.in">PSGR KRISHNAMMAL COLLEGE FOR 
WOMEN</a> 
</p> 
</body> 
</html>

8. IMPLEMENTING FRAMES AND FRAME SETS.  
<html> 
<head> 
<title>Frames Example</title> 
</head> 
<frameset cols="25%,75%"> 
<frame src="frame1.html"></frame> 
<frame src="frame2.html"></frame> 
</frameset> 
</html> 
frame1.html 
<html> 
<head><title>left frame</title></head> 
<body> 
<h2>This is left frame</h2> 
<p>the left frame content will be displayed here.</p> 
</body> 
</html>
frame2.html 
<html> 
<head><title>left frame</title></head> 
<body> 
<h2>This is right frame</h2> 
<p>the right frame content will be displayed here.</p> 
</body> 
</html>

9. CREATE A FORM WITH VARIOUS FIELDS AND   
APPROPRIATE FONT AND VALIDATIONS USING 
ANY ONE OF THE SCRIPTING LANGUAGES. 
<html> 
<head> 
<title>Form Validations</title> 
<style> 
body { 
font-family: 'Arial', sans-serif; 
background-color: #f4f4f4; 
margin: 0; 
padding: 0; 
} 
form { 
width: 50%; 
margin: 50px auto; 
padding: 17px; 
background-color: #fff; 
border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); 
        } 
 
        label { 
            display: block; 
            margin-bottom: 8px; 
            font-weight: bold; 
        } 
 
        input, 
        select, 
        textarea { 
            width: 100%; 
            padding: 8px; 
            margin-bottom: 15px; 
            border: 1px solid #ccc; 
            border-radius: 4px; 
            box-sizing: border-box; 
        } 
 
      
   input[type="button"] { 
            background-color: #4559a0; 
            color: #fff; 
            cursor: pointer; 
        } 
 
        input[type="button"]:hover { 
            background-color:  #4caf50; 
        } 
    </style> 
</head> 
 
<body> 
 
<h4><b><center>FORM VALIDATION</center></b></h4> 
    <form> 
        <label for="name">Name:</label> 
        <input type="text" id="name" name="name" required> 
 <label for="email">Email:</label> 
        <input type="email" id="email" name="email" required pattern="[a-zA-Z0
9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$"> 
 
        <label for="age">Age:</label> 
        <input type="number" id="age" name="age" required> 
 
        <label for="gender">Gender:</label> 
        <select id="gender" name="gender" required> 
            <option value="">Select</option> 
            <option value="male">Male</option> 
            <option value="female">Female</option> 
            <option value="other">Other</option> 
        </select> 
 
        <label for="message">Message:</label> 
        <textarea id="message" name="message" rows="4" required></textarea> 
 
        <input type="button" value="Submit" onclick="validateForm()"> 
    </form> 
 
    <script> 
        function validateForm() { 
            var name = document.getElementById("name").value; 
            var email = document.getElementById("email").value; 
            var age = document.getElementById("age").value; 
            var gender = document.getElementById("gender").value; 
            var message = document.getElementById("message").value; 
 
            if (name === "" || email === "" || age === "" || gender === "" || message 
=== "") { 
                alert("All fields must be filled out"); 
                return false; 
            } 
 
            // Age validation (assuming age should be between 18 and 100) 
            if (isNaN(age) || age < 18 || age > 100) { 
                alert("Please enter a valid age between 18 and 100"); 
return false; 
} 
return true; 
} 
</script> 
</body> 
</html>


10.DEMONSTRATE JAVA SCRIPT WITH POP
UP BOXES. 
 
 
<html> 
<head> 
<title>pop-up boxes in javascript</title> 
</head> 
    <body> 
        <center> 
            <h3>ALERT BOX</h3> 
            <button onclick="alertbox()"> 
                click here for alert box 
            </button> 
 
            <h3>PROMPT BOX</h3> 
            <button onclick="promptbox()"> 
                click here for prompt box 
            </button> 
 
            <h3>CONFIRM BOX</h3> 
            <button onclick="confirmbox()"> 
                click here for confirm box 
            </button> 
 
            <script> 
                function alertbox(){ 
                    alert("This is a alert box") 
                } 
 
                function promptbox(){ 
                    prompt("Enter your name") 
                } 
 
                function confirmbox(){ 
                    var result = confirm("do you want to procees?") 
                    if (result) { 
                        alert("you clicked ok")
                        } else { 
alert("you clicked cancel") 
} 
} 
</script> 
</center> 
</body> 
</html>

11.CREATE A WEB PAGE USING XML. 
<?xml version="1.0" encoding="UTF-8"?> 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" 
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"> 
<html xmlns="http://www.w3.org/1999/xhtml"> 
<head> 
<title>Simple Web Page with XML Data</title> 
</head> 
<body> 
<h1>Welcome to My Simple Web Page</h1> 
<p>This is a basic web page that includes XML data:</p> 
<xml> 
<person> 
<name>John Doe</name> 
<age>25</age> 
<city>New York</city> 
</person> 
</xml> 
</body> 
</html>

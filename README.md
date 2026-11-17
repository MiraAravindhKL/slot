# Ex04 Time Table
## Date:17.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
    <title>Slot Time Table</title>
</head>

<body bgcolor="honeydew" text="#FFFFFF">

    <center>
        <img src="logo.png" alt="College Logo" width="400" height="100">

        <h1 style="color:black">SAVEETHA ENGINEERING COLLEGE</h1>
        <h2 style="color: black;">SLOT TIME TABLE</h2>
    </center>

    <table border="1" align="center" cellpadding="15" cellspacing="0"
           bgcolor="purple">

        <tr bgcolor="magneta">
            <th>TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>

        <tr>
            <th bgcolor="purple">8:00 AM - 9:29 AM</th>
            <td>CDS</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>S&NM</td>
            <td>PS</td>
        </tr>

        <tr>
            <th bgcolor="purple">9:45 AM - 11:15 AM</th>
            <td>FWAD</td>
            <td>PP</td>
            <td>FREE SLOT</td>
            <td>PP</td>
            <td>PP</td>
            <td>S&NM</td>
        </tr>

        <tr>
            <th bgcolor="purple">11:30 AM - 12:15 PM</th>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
            <td>SCOFT-MM</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="purple">12:15 PM - 12:59 PM</th>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
            <td>SCOFT-MM</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
        </tr>

        <tr>
            <th bgcolor="purple">1:15 PM - 2:45 PM</th>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>PS</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="purple">3:00 PM - 4:30 PM</th>
            <td>DE</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>BEEEME</td>
            <td>DE</td>
            <td>FREE SLOT</td>
        </tr>

    </table>

    <br>

    <center>
        <h2 style="color:black">SUBJECT DETAILS</h2>
    </center>

    <table border="1" align="center" cellpadding="10" cellspacing="0"
           bgcolor="purple">

        <tr bgcolor="magneta">
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>

        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
        </tr>

        <tr>
            <td>2</td>
            <td>19EE405</td>
            <td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING (BEEME)</td>
        </tr>

        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING (PP)</td>
        </tr>

        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>DIGITAL ELECTRONICS (DE)</td>
        </tr>

        <tr>
            <td>5</td>
            <td>19MA211</td>
            <td>STATISTICS AND NUMERICAL METHODS (S&NM)</td>
        </tr>

        <tr>
            <td>6</td>
            <td>19EN105</td>
            <td>PUBLIC SPEAKING (PS)</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS (CDS)</td>

        </tr>

    </table>

</body>
</html>
```
## OUTPUT
![alt text](<aravindhslot/Screenshot (11).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

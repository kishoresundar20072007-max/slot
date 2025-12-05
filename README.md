# Ex03 Time Table
## Date: 05.12.2025
# Ref no: 25012046

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table  align="center" width="540" cellspacing="2" cellpadding="4" border="3">
        <caption><b>SLOT TIME TABLE - SUNDAR K (25012046)</b></caption>
        <tr align="center">
        <th bgcolor="lightgray">Day/Time</th>
        <th bgcolor="lightgray">Monday</th>
        <th bgcolor="lightgray">Tuesday</th>
        <th bgcolor="lightgray">Wednesday</th>
        <th bgcolor="lightgray">Thursday</th>
        <th bgcolor="lightgray">Friday</th>
        <th bgcolor="lightgray">Saturday</th>
        </tr>
        <tr align="center">
        <th bgcolor="lightgray">8-10</th>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        </tr>
        <tr align="center">
        <th bgcolor="lightgray">10-12</th>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
        <th bgcolor="lightgray">12-1</th>
        <td colspan="6" align="center">L U N C H</td>
        </tr>
        <tr align="center">
        <th bgcolor="lightgray">1-3</th>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>MENTOR MEET</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr align="center">
        <th bgcolor="lightgray">3-5</th>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FUNDAMENTALS OF WEB APPILICATION</td>
        <td>FREE SLOT</td>
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
        <th bgcolor="lightgray">S. No.</th>
        <th bgcolor="lightgray">Subject Code</th>
        <th bgcolor="lightgray">Subject Name</th>
        </tr>
        <tr>
        <td align="center" bgcolor="lightgray">1.</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
        <td align="center" bgcolor="lightgray">2.</td>
        <td align="center">19AI304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
        </tr>

        <tr>
        <td align="center" bgcolor="lightgray">4.</td>
        <td align="center">SH1101</td>
        <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr>
    </body>        
</html>
~~~


## OUTPUT

![timetable](https://github.com/user-attachments/assets/05eb949a-37f6-45d6-8ff5-d02e3ae30bed)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

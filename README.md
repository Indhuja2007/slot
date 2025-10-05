# Ex03 Time Table
## Date:05/10/2025

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
```
<html>
    <head>
        <title>SLOT-TIMETABLE</title>
    </head>
    <body>
        <center>
          <img src="/static/logo.png" height="200" width="600">
        </center>
        <center><h2>SLOT-TIMETABLE - INDHUJA.K(25018219)</h2></center>
        <table border="5" align="center" cellspacing="5" cellpadding="5" bgcolor="yellow">"
            <tr bgcolor="green">
                <th>Day\Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="green">08-10</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>C.E</td>
                <td>C PROGRAM</td>
                <td>FWAD</td>
                <td>FREE</td>
            </tr>
            <tr>
                <th bgcolor="green">10-12</th>
                <td>FREE</td>
                <td>C.E</td>
                <td>C.E</td>
                <td>FREE</td>
                <td>C.E</td>
                <td>C.E</td>
            </tr>
            <tr>
                <th bgcolor="green">12-01</th>
                <td align="center" colspan="6">LUNCH</td>
            </tr>
            <tr>
                <th bgcolor="green">01-03</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MENTOR MEET</td>
                <td>C PROGRAM</td>
                <td>C.E</td>
                <td>FREE</td>
            </tr>
            <tr>
                <th bgcolor="green">03-04</th>
                <td>C PROGRAM</td>
                <td>C PROGRAM</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>C PROGRAM</td>
                <td>FREE</td>
            </tr>
        </table>



        <h1>      </h1>
        <table border="5" class="SUBJECT TABLE" align="center" cellpadding="5" cellspacing="5">
            <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>FUNDAMENTAL OF C PROGRAMMING(C PROGRAM)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH(C.E)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (35).png>)    


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

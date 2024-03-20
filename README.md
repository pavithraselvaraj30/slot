# Ex03 Time Table
## Date:17-03-2024

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
        <title>SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
        <img src="logo.png" width="550" height="50">
        </center>
        <br>
        <table align="center" border="2" cellspacing="5" cellpadding="5" width="40" height="50" bgcolor="lightblue">
        <caption> <b> SLOT TIME TABLE-PAVITHRA (212223230147) </b></caption>
        <tr>
            <th bgcolor="grey">DAY/TIME</th>
            <th bgcolor="grey">8-10</th>
            <th bgcolor="grey">10-12</th>
            <th bgcolor="grey">12-1</th>
            <th bgcolor="grey">1-3</th>
            <th bgcolor="grey">3-5</th>
        </tr>
        <tr>
            <td bgcolor="grey">Monday</td>
            <td>Free slot</td>
            <td>Free slot</td>
            <td>Lunch</td>
            <td>BEEE</td>
            <td> C programming</td>
        </tr>
        <tr>
            <td bgcolor="grey">Tuesday</td>
            <td>Free slot</td>
            <td>Python and linear algebra</td>
            <td>Lunch</td>
            <td>Fundamentals of web application</td>
            <td>Free slot</td>
         </tr>
         <tr>
            <td bgcolor="grey">Wednesday</td>
            <td>Chemistry</td>
            <td>BEEE</td>
            <td>Lunch</td>
            <td>English</td>
            <td>Python and linear algebra</td>
        </tr>
        <tr>
            <td bgcolor="grey">Thursday</td>
            <td>Free slot</td>
            <td>Free slot</td>
            <td>Lunch</td>
            <td>Fundamentals of web application</td>
            <td>Free slot</td>
        </tr>
        <tr>
            <td bgcolor="grey">Friday</td>
            <td>Fundamentals of web application</td>
            <td> C programming</td>
            <td>Lunch</td>
            <td>Python and linear algebra</td>
            <td>English</td>
        </tr>
        <tr>
            <td bgcolor="grey">Saturday</td>
            <td>Python and linear algebra</td>
            <td>Chemistry</td>
            <td>Lunch</td>
            <td>Free slot</td>
            <td>Free slot</td>
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2" bgcolor="grey">
            <tr align="center">
            <th bgcolor="lightblue">S. No.</th>
            <th bgcolor="lightblue">Subject Code</th>
            <th bgcolor="lightblue">Subject Name</th>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">1.</td>
            <td align="center" bgcolor="grey">19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">2.</td>
            <td align="center" bgcolor="grey">19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">3.</td>
            <td align="center" bgcolor="grey">19Ai301C</td>
            <td>Python and linear algebra</td>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">4.</td>
            <td align="center" bgcolor="grey">19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">5.</td>
            <td align="center" bgcolor="grey">19EN101</td>
            <td> English </td>
            </tr>
            <tr>
            <td align="center" bgcolor="lightblue">6.</td>
            <td align="center" bgcolor="grey">19EE305</td>
            <td>BEEE</td>
            </tr>
        </table>
       </body>
    </html>

    
```


## OUTPUT
![Screenshot (1)](https://github.com/pavithraselvaraj30/slot/assets/149366880/51cd44a2-21e9-4fa6-921d-f03798394378)
![Screenshot (2)](https://github.com/pavithraselvaraj30/slot/assets/149366880/7cec3d3e-9175-4b9e-8e8a-bf9080c5c125)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

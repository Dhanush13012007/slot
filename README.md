# Ex02 Time Table
## Date:25.11.2025

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
        <title>SLOT TIMINGS</title>
    </head>
    <body>       
        <img src="logo.png" width ="110" height="15"> 
        
        
        <table border="3" cellpadding="10" bgcolor="grey">
            <caption><b>Table:-Slot Timings &nbsp &nbsp STUDENT NAME:M DHANUSH &nbsp &nbsp REF.NO:25009955</b></caption>
            <tr>
                <th>Day/Time</th>
                <th>mon</th>
                <th>tue</th>
                <th>wed</th>
                <th>thurs</th>
                <th>fri</th>
                <th>sat</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td bgcolor="brown">freeslot</td>
                <td bgcolor="red">FOCP</td>
                <td bgcolor="blue">ML</td>
                <td bgcolor="blue">ML</td>
                <td bgcolor="green">FWAD</td>
                <td bgcolor="red">FOCP</td>

            </tr>
            <tr>
                 <td>10-12</td>
                 <td bgcolor="brown">freeslot</td>
                 <td bgcolor="blue">ML</td>
                 <td bgcolor="blue">ML</td>
                 <td bgcolor="red">FOCP</td>
                 <td bgcolor="green">FWAD</td>
                 <td bgcolor="green">FWAD</td>
            </tr>
            <tr>
                <td>12-1</td>
                <td colspan="6" bgcolor="purple">LUNCH</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td bgcolor="green">FWAD</td>
                <td bgcolor="green">FWAD</td>
                <td bgcolor="yellow">MENTOR MEET</td>
                <td bgcolor="brown">free slot</td>
                <td bgcolor="blue">ML</td>
                <td bgcolor="red">FOCP</td>
            </tr>
            <tr>
                <td>3-5</td>
                <td colspan="4" bgcolor="brown">free slot</td>
                <td bgcolor="red">FOCP</td>
                <td bgcolor="brown">free slot</td>

            </tr>
        </table>
        <table border="3" cellpadding="10" bgcolor="grey">
            <tr>
                <th>S.NO</th>
                <th>Subject code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>fundamendals of web application(FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI410</td>
                <td>introduction to machine leaarning(ML)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>fundamentals of c programming(FOCP)</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

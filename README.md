# Ex02 Time Table
## Date:25/11/2025

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
        <title>Timetable</title>
    </head>
    <body>
        <img src="logo.png" width="550" height="150" alt="Timetable Image" title="sec header">
        
        <table border="5" cellspacing="3" cellpadding="5">
            <br>
            <br>
            <caption> <b>TIMETABLE:SAHITHYA(25004681) </b> </caption>
            <tr>
                <th bgcolor="pink">Day/time</th>
                <th bgcolor="pink">MON</th>
                <th bgcolor="pink">TUES</th>
                <th bgcolor="pink">WED</th>
                <th bgcolor="pink">THURS</th>
                <th bgcolor="pink">FRI</th>
                <th bgcolor="pink">SAT</th>
            </tr>
            <tr>
                <td bgcolor="pink">8-10</td>
                <td colspan="2" align="center">Eng</td>
                <td>FWAD</td>
                <td>Python</td>
                <td>Free Hour</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <td bgcolor="pink">10-12</td>
                <td colspan="3" align="center">FWAD</td>
                <td colspan="2" align="center">Free Hour</td>
                <td>Eng</td>
            </tr>
            <tr>
                <td bgcolor="pink">12-1</td>
                <td colspan="6" align="center">Lunch</td>
            </tr>
            <tr>
                <td bgcolor="pink">1-3</td>
                <td>Python</td>
                <td>Free Hour</td>
                <td>Mentor meet</td>
                <td>Eng</td>
                <td>Free Hour</td>
                <td>Python</td>
            </tr>
            <tr>
                <td bgcolor="pink">3-5</td>
                <td>Python</td>
                <td colspan="3" align="center">Free Hour</td>
                <td>Python</td>
                <td>Free Hour</td>
            </tr>           
        </table>
        <br>
        <br>
        <table border="5" cellspacing="3" cellpadding="5">
            <tr>
            <th>S.NO</th>
            <th>Subject Code</th>
            <th align="center">Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Applicatio(FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EN101</td>
                <td>Communicative English(Eng)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI301</td>
                <td>Python Programming(Python)</td>
            </tr>

        </table>

    </body>
</html>
```

## OUTPUT
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a9478637-e9d7-4d7d-bfa2-c829ba266032" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

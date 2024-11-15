# Ex03 Time Table
## Date: 11-11-2024


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
    <body>
        <img src="logo.png" width="700" height="200">
        <table border="5" cellspacing="20" cellpadding="3">
            <caption>SLOT TIME TABLE-DHARSHANA A S (24009985)</caption>
            <tr bgcolor="Teal">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>Free Slot</td>
                <td>CDS</td>
                <td>Calculus and Matrix Algebra</td>
                <td>Communicative English</td>
                <td>Web Application</td>
                <td>Free Slot</td>
            </tr>
            <TR>
                <td>10-12</td>
                <td>Communicative English</td>
                <td>EDM</td>
                <td>C Programming</td>
                <td>Calculus and Matrix Algebra</td>
                <td>C Programming</td>
                <td>Free Slot</td>
            </TR>
            <TR>
                <td>12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </TR>
            <TR>
                <td>1-3</td>
                <td>Web Application</td>
                <td>Wed Application</td>
                <td>Mentor Meet</td>
                <td>Free Slot</td>
                <td>EDM</td>
                <td>Free Slot</td>
            </TR>
            
                <td>3-5</td>
                <td>Free slot</td>
                <td>Free Slot</td>
                <td>Chemistry</td>
                <td>Chemistry</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
            </TR>
        </table>
    </body>
</html>
<br>
<html>
    <body>
        <table border="2" cellspacing="15" cellpadding="2">
            <caption>COURSE</caption>
            <tr bgcolor="Slate gray">
                <th>S.No</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI302 </td>
                <td>Engineering Design and Modelling</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of Web Application Development</td>
            </TR>
            <TR>
                <td>3</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering</td>
            </TR>
            <TR>
                <td>4</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </TR>
            <TR>
                <td>5</td>
                <td>19MA201 </td>
                <td>Calculus and Matrix Algebra</td>
            </TR>
            
            <TR>
                <td>7</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </TR>

            <TR>
                <td>6</td>
                <td>19EY708</td>
                <td>CDS</td>
            </TR>
        </table>
    </body>
</html>
<style>
    body{
    font-family: 'poppine';
    }
</style>
```


## OUTPUT
![alt text](<Screenshot 2024-11-16 000939.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

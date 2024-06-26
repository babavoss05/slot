# Ex03 Time Table
## Date:24/03/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:
### html:
```html
<html>
    <head>
        <title>
             TIME TABLE
        </title>
        <link rel="stylesheet" href="exp3.css">
    </head>
    <body class="bg">
        <center>
            <img src="logo.png" with="100px", height="100px"><br><br><br>
            <h2 class="name">TIME TABLE Gokul S (212221220013)</h2>
            <table border="6" class="table1">
                <tr class="dt">
                    <th>Day/Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thuresday</th>
                    <th>Friday</th>
                    <th>Saturday</th>
                </tr>
                <tr>
                    <td class="dt">8-10</td>
                    <td>WEB APP</td>
                    <td class="fs">FREE SLOT</td>
                    <td>CSS</td>
                    <td>MPMC</td>
                    <td class="fs">FREE SLOT</td>
                    <td> DATA MINING</td>
                </tr>
                <tr>
                    <td class="dt">10-12</td>
                    <td >Robotics</td>
                    <td>PYTHON</td>
                    <td>PYTHON</td>
                    <td>DATA MINING</td>
                    <td class="fs">FREE SLOT</td>
                    <td>MPMC</td>
                </tr>
                <tr>
                    <td class="dt">12-01</td>
                    <td colspan="6" style="text-align: center; color: rgb(12, 131, 12)">LUNCH BREAK</td>
                </tr>
                <tr>
                    <td class="dt">01-03</td>
                    <td>MPMC</td>
                    <td class="fs">FREE SLOT</td>
                    <td >MAD</td>
                    <td>WEB APP</td>
                    <td class="fs">FREE SLOT</td>
                    <td>MAD</td>
                </tr>
                <tr>
                    <td class="dt">03-05</td>
                    <td class="fs">FREE SLOT</td>
                    <td class="fs">FREE SLOT</td>
                    <td>ADC</td>
                    <td class="fs">FREE SLOT</td>
                    <td >Robotics</td>
                    <td>ADC</td>
                </tr>
            </table>
            <br> <br> 
            <table border="6" class="table2">
                <tr>
                    <th>S. No.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI414</td>
                    <td><b>Fundamental of Web Application Development [FUN WEB]</b></td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19EC303</td>
                    <td><b>MPMC</b></td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19AI412</td>
                    <td><b>Data Mining</b></td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19EY706</td>
                    <td><b>Company Specific Skills</b></td>
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19EC306</td>
                    <td><b>ADC</b></td>
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19AI533</td>
                    <td><b>Robotics</b></td>
                </tr>
                <tr>
                    <td>7.</td>
                    <td>19CS301</td>
                    <td><b>PYTHON</b></td>
                </tr>
            </table>
        </center>
    </body>
</html>
```
### CSS:
```css
.name{
    font-family: 'Pricedown', Times, serif;
}
.bg{
    background-color: rgb(67, 162, 163);
}
.table1{
    background-color: rgb(157, 126, 203);
}
.table2{
    background-color: rgb(241, 238, 244);
}    
.dt{
    background-color: rgb(166, 224, 232);
}
.fs{
    color: rgb(193, 82, 42);
}
b{ 
    color:rgb(36, 99, 105); 
}
```


## OUTPUT:
![alt text](image.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

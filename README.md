# Ex03 Time Table
## Date:19/9/2025

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

<!DOCTYPE html>
<html>
  <head>
    <title>Saveetha Engineering College Timetable</title>
    <style>
      table {
        width: 80%;
        border-collapse: collapse;
        margin: 30px auto;
        font-family: Arial, sans-serif;
      }
      th, td {
        border: 1px solid #444;
        padding: 10px;
        text-align: center;
      }
      th {
        /* No background color */
      }
      .day {
        /* No background color */
      }
    </style>
  </head>
  <body>
    <img src="/static/logo.png" height="100px" width="100%">
    <center>
      <h2>Saveetha Engineering College</h2>
      <h3>My Timetable</h3>
    </center>
    <table>
      <tr>
        <th>Day</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>1-3</th>
        <th>3-5</th>
      </tr>
      <tr>
        <td class="day">Monday</td>
        <td>ENGLISH</td>
        <td></td>
        <td>WEB APPLICATION</td>
        <td>PYTHON PROGRAMMING</td>
      </tr>
      <tr>
        <td class="day">Tuesday</td>
        <td></td>
        <td>PYTHON PROGRAMMING</td>
        <td>ENGLISH</td>
        <td></td>
      </tr>
      <tr>
        <td class="day">Wednesday</td>
        <td>ENGLISH</td>
        <td>WEB APPLICATION</td>
        <td>MENTOR MEET</td>
        <td>WEB APPLICATION</td>
      </tr>
      <tr>
        <td class="day">Thursday</td>
        <td></td>
        <td></td>
        <td>ENGLISH</td>
        <td>WEB APPLICATION</td>
      </tr>
      <tr>
        <td class="day">Friday</td>
        <td>ENGLISH</td>
        <td>PYTHON PROGRAMMING</td>
        <td></td>
        <td>ENGLISH</td>
      </tr>
      <tr>
        <td class="day">Saturday</td>
        <td>PYTHON PROGRAMMING</td>
        <td></td>
        <td>WEB APPLICATION</td>
        <td>PYTHON PROGRAMMING</td>
      </tr>
    </table>
  </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-09-22 131101.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex03 Time Table

## Date:07.12.2025

## AIM

To write a html webpage page to display your slot timetable.

## ALGORITHM

### STEP 1

Create a Django-admin Interface.

### STEP 2

Create a static folder and inert HTML code.

### STEP 3

Create a simple table using `<table>` tag in html.

### STEP 4

Add header row using `<th>` tag.

### STEP 5

Add your timetable using `<td>` tag.

### STEP 6

Execute the program using runserver command.

## PROGRAM

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Slot Timetable</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: lavender;
        text-align: center;
      }
      .header {
        background: pink;
        color: rgb(203, 60, 203);
        padding: 15px;
      }
      .header h2 {
        margin: 5px 0;
      }
      table {
        border-collapse: collapse;
        width: 90%;
        margin: 20px auto;
      }
      th,
      td {
        border: 1px solid rgb(40, 7, 7);
        padding: 10px;
        text-align: center;
      }
      th {
        background-color: rgb(111, 39, 180);
      }
      td {
        background-color: rgb(215, 144, 201);
      }
      .sub-table th {
        background-color: rgb(11, 60, 166);
      }
      td {
        background-color: rgb(20, 200, 240);
      }
    </style>
  </head>
  <body>
    <center>
      <img src="/static/logo.png" height="100px" width="540" />
    </center>
    <h3>SLOT TIME TABLE-SAADHANA A (25018432)</h3>

    <table>
      <tr>
        <th>Day/Time</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>12-1</th>
        <th>1-3</th>
        <th>3-5</th>
      </tr>
      <tr>
        <td>MONDAY</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
        <td rowspan="6" class="vertical text">LUNCH</td>
        <td>FOCP</td>
        <td>FREE SLOT</td>
      </tr>
      <tr>
        <td>TUESDAY</td>
        <td>ENG</td>
        <td>ENG</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
      </tr>
      <tr>
        <td>WEDNESDAY</td>
        <td>FWAD</td>
        <td>FWAD</td>
        <td>MM</td>
        <td>FOC</td>
      </tr>
      <tr>
        <td>THURSDAY</td>
        <td>ENG</td>
        <td>FOC</td>
        <td>ENG</td>
        <td>FOC</td>
      </tr>
      <tr>
        <td>FRIDAY</td>
        <td>FOC</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
      </tr>
      <tr>
        <td>SATURDAY</td>
        <td>ENG</td>
        <td>FWAD</td>
        <td>ENG</td>
        <td>FREE SLOT</td>
      </tr>
    </table>
    <h3>Subjects</h3>
    <table class="sub-table">
      <tr>
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
      </tr>
      <tr>
        <td>2</td>
        <td>19EN101</td>
        <td>Communicative English (ENG)</td>
      </tr>
      <tr>
        <td>3</td>
        <td>19AI304</td>
        <td>Fundamentals Of C Programming (FOC)</td>
      </tr>
      <tr></tr>
    </table>

  </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-12-07 at 11.01.50 AM.png>)

## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.

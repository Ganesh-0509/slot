# Ex03 Time Table
## Date:

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Time Table - Saveetha Engineering College</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
  body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    background: linear-gradient(135deg, #ffe0e0, #ffc2d1);
    padding: 0;
    color: #2e2e2e;
  }

  .navbar {
    background-color: #6a1b9a;
    padding: 15px 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: white;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }

  .navbar img {
    height: 50px;
    margin-right: 15px;
  }

  .navbar .title {
    font-size: 22px;
    font-weight: 600;
    display: flex;
    align-items: center;
  }

  .navbar .code {
    font-size: 18px;
    background: #ab47bc;
    padding: 5px 12px;
    border-radius: 8px;
    font-weight: 500;
  }

  .container {
    padding: 30px;
  }

  .table-container, .subject-container {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    margin-bottom: 30px;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }

  th, td {
    padding: 12px;
    text-align: center;
    border-bottom: 1px solid #ddd;
  }

  th {
    background: #f06292;
    color: white;
  }

  tr:nth-child(even) {
    background: #fce4ec;
  }

  h2 {
    color: #4a148c;
  }

  .footer {
    text-align: center;
    margin: 40px 0 20px;
    font-size: 14px;
    color: #555;
  }
</style>

</head>
<body>
  <div class="navbar">
    <div class="title">
      <img src="/static/logo.png" alt="College Logo">
      SAVEETHA ENGINEERING COLLEGE
    </div>
    <div class="code">TNEA CODE: 1216</div>
  </div>

  <div class="container">
    <div class="table-container">
      <h2>Weekly Time Table - GANESH KUMAR T (212224240043)</h2>
      <table>
        <tr>
          <th>Day/Time</th><th>8-10</th><th>10-12</th><th>12-1</th><th>1-3</th><th>3-5</th>
        </tr>
        <tr><td>Monday</td><td>INTRO TO ML</td><td>FREE SLOT</td><td>LUNCH</td><td>CHE</td><td>FUND OF C</td></tr>
        <tr><td>Tuesday</td><td>ENG</td><td>FWAD</td><td>LUNCH</td><td>PRG MICR</td><td>FUND OF AI</td></tr>
        <tr><td>Wednesday</td><td>FREE SLOT</td><td>FUND OF AI</td><td>LUNCH</td><td>HVE</td><td>PRG MICR</td></tr>
        <tr><td>Thursday</td><td>FUND OF WEB</td><td>INTRO TO DS</td><td>LUNCH</td><td>INTRO TO ML</td><td>FREE SLOT</td></tr>
        <tr><td>Friday</td><td>FUND OF WEB</td><td>FUND OF C</td><td>LUNCH</td><td>CHE</td><td>FREE SLOT</td></tr>
        <tr><td>Saturday</td><td>INTRO TO DS</td><td>ENG</td><td>LUNCH</td><td>FREE SLOT</td><td>FREE SLOT</td></tr>
      </table>
    </div>

    <div class="subject-container">
      <h2>Subject Details</h2>
      <table>
        <tr><th>S.No</th><th>Subject Code</th><th>Subject Name</th></tr>
        <tr><td>1</td><td>19AI410</td><td>Introduction to Machine Learning</td></tr>
        <tr><td>2</td><td>19AI414</td><td>Fundamentals of Web Application Development</td></tr>
        <tr><td>3</td><td>19HS801</td><td>Human Values and Professional Ethics</td></tr>
        <tr><td>4</td><td>19AI405</td><td>Fundamentals of Artificial Intelligence</td></tr>
        <tr><td>5</td><td>19AI304</td><td>Fundamentals of C Programming (FUND OF C)</td></tr>
        <tr><td>6</td><td>19EN101</td><td>English (ENG)</td></tr>
        <tr><td>7</td><td>19CY205</td><td>Principles of Chemistry</td></tr>
        <tr><td>8</td><td>19AI403</td><td>Introduction to Data Science</td></tr>
      </table>
    </div>

    <div class="footer">
      Designed with Passion by Ganesh Kumar T | Saveetha Engineering College
    </div>
  </div>
</body>
</html>
```

## OUTPUT
![Output](ganesh/slotapp/static/image.png)
![Output](<ganesh/slotapp/static/image copy.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

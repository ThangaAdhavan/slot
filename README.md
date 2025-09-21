# Ex03 Time Table
## Date:21.09.2025

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

```<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - THANGAADHAVAN</title>
</head>
<body>
    <IMG src="/static/logo.png" HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - THANGAADHAVAN</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="GREEN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>FREE SLOT</td>
            <td>PUBLIC SPEAKING</td>
            <td>FREE SLOT</td>
            <td>PUBLIC SPEAKING</td>
            <td>PUBIC SPEAKING</td>
        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>PYTHON</td>
            <td>WEB APPLICATION</td>
            <td>FREE SLOT</td>
            <td>PYTHON</td>
            <td>PUBLIC SPEAKING</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="GREEN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>WEB APPLICATION</td>
            <td>PUBLIC SPEAKING</td>
            <td>MENTOR MEETING</td>
            <td>FREE SLOT</td>
            <td>WEB APPLICATION</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>WEB APPLICATION</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN105</td>
            <td>PUBLIC SPEAKING(PS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMING</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![alt text](timetable/timetableapp/static/logo.png)
![alt text](<timetable/timetableapp/static/Screenshot 2025-09-20 220857.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

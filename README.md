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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - Kesav K M</title>
</head>
<body>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - Kesav K M (212224110031)</h3>

    <table border="1">
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>Python and Linear Algebra</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>FWAD</td>
            <td>Python</td>
            <td>FWAD</td>
            <td>EDM</td>
            <td>Data Science</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>EDM</td>
            <td>DS</td>
            <td>MENTOR MEET</td>
            <td>PROB</td>
            <td>EMPD</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FREE SLOT</td>
            <td>EMPD</td>
            <td>FREE SOLT</td>
            <td>RA</td>
            <td>FREE SOLT</td>
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
            <td>19AI403</td>
            <td>Introduction to Data Science(DS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI301C</td>
            <td>Phython and Linear Algebra(PLA)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI302</td>
            <td>Engineering Design and Modelling(EDM)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI303</td>
            <td>Engineering Mechanics and Product Development(EMPD)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19MA222</td>
            <td>Probability and Queueing Models(PQM)</td>
        </tr>
    </table>
</body>
</html>


## OUTPUT
![Screenshot 2025-04-16 113845](https://github.com/user-attachments/assets/520f5f45-7918-49ab-9c4f-49e9ffeb88a1)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex03 Time Table
## Date  :10/9/2024
## NAME  :V RAKSHA DHARANIKA 
## REF NO:212223230167

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
</head>
<body bgcolor= "#0f0616" style="color: white;">
    <center>
        <img src="C:\Users\A.sathish\Downloads\clglogo.png" alt="College Logo" style="width: 580; margin-top: 20px;" />
    </center>

    <br>
    <table align="center" width="80%" cellspacing="0" cellpadding="8" border="1" style="border-collapse: collapse;">
        <caption style="font-size: 0.90; color: white;">SLOT TIMETABLE - V RAKSHA DHARANIKA (212223230167)</caption>
        <tr bgcolor="black" style="color:white;">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr bgcolor="gray">
            <th bgcolor="black" style="color: white;">8-10</th>
            <td style="color: black;">Free</td>
<td style="color: black;">Computer Network</td>
<td style="color: black;">Programming in C</td>
<td style="color: black;">Free</td>
<td style="color: black;">Programming in C</td>
<td style="color: black;">Fundamentals of Web</td>
        </tr>
        <tr bgcolor="darkgray">
            <th bgcolor="black" style="color: white;">10-12</th>
            <td style="color: black;">Quantitative Ability</td>
            <td style="color: black;">Free</td>
            <td style="color: black;">Introduction to IoT</td>
            <td style="color: black;">Fundamentals of Web</td>
            <td style="color: black;">Operating System</td>
            <td style="color: black;">Introduction to IoT</td>
        </tr>
        <tr bgcolor="gray">
            <th bgcolor="black" style="color: white;">12-1</th>
            <td colspan="6" align="center">LUNCH BREAK</td>
        </tr>
        <tr bgcolor="darkgray">
            <th bgcolor="black" style="color: white;">1-3</th>
            <td style="color: black;">Free</td>
            <td style="color: black;">Free</td>
            <td style="color: black;">Mentor Meet</td>
            <td style="color: black;">Introduction to Machine Learning</td>
            <td style="color: black;">Free</td>
            <td style="color: black;">Introduction to Data Science</td>
        </tr>
        <tr bgcolor="gray">
            <th bgcolor="black" style="color: white;">3-5</th>
            <td style="color: black;">Fundamentals of Web</td>
            <td style="color: black;">Introduction to Data Science</td>
            <td style="color: black;">Computer Networks</td>
            <td style="color: black;">Operating System</td>
            <td style="color: black;">Free</td>
            <td style="color: black;">Introduction to Machine Learning</td>
        </tr>
    </table>

    <br>

    <table align="center" width="60%" cellspacing="0" cellpadding="5" border="1" style="border-collapse: collapse;">
        <tr bgcolor="black" style="color: white;">
            <th> S.No.</th>
            <th style="color: white;">Subject Code</th>
            <th style="color: white;">Subject Name</th>
        </tr>
        <tr bgcolor="gray">
            <td style="color: black;" align="center">1.</td>
            <td style="color: black;" align="center">19AI414</td>
            <td style="color: black;" >Fundamentals of Web Development</td>
        </tr>
        <tr bgcolor="darkgray">
            <td style="color: black;" align="center">2.</td>
            <td style="color: black;" align="center">19AI410</td>
            <td style="color: black;">Introduction to Machine Learning</td>
        </tr>
        <tr bgcolor="gray">
            <td  style="color: black;"align="center">3.</td>
            <td  style="color: black;"align="center">19CS406</td>
            <td style="color: black;">Computer Networks</td>
        </tr>
        <tr bgcolor="darkgray">
            <td style="color: black;" align="center">4.</td>
            <td  style="color: black;"align="center">19AM508</td>
            <td style="color: black;">Introduction to IoT</td>
        </tr>
        <tr bgcolor="gray">
            <td style="color: black;" align="center">5.</td>
            <td  style="color: black;"align="center">19EY710</td>
            <td style="color: black;">Quantitative Ability I</td>
        </tr>
        <tr bgcolor="darkgray">
            <td style="color: black;" align="center">6.</td>
            <td style="color: black;" align="center">19CS405</td>
            <td style="color: black;">Operating System</td>
        </tr>
        <tr bgcolor="gray">
            <td style="color: black;" align="center">7.</td>
            <td style="color: black;" align="center">19CS302</td>
            <td style="color: black;">Programming in C</td>
        </tr>
        <tr bgcolor="darkgray">
            <td style="color: black;" align="center">8.</td>
            <td style="color: black;" align="center">19AI410</td>
            <td style="color: black;">Introduction to Data Science</td>
        </tr>
        <tr bgcolor="gray">
            <td style="color: black;" align="center">9.</td>
            <td style="color: black;" align="center">ECA-M</td>
            <td style="color: black;">Mentor Meet</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT

![image](https://github.com/user-attachments/assets/3e2d9fcf-f236-47cb-add2-399905be1eba)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

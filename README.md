# Ex03 Slot Time Table
## Date:08/10/2024
## Name:Ramkumar S
## Reg.No:212223220085

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
### STEP 1:
Create a Django-admin Interface.

### STEP 2:
Create a static folder and inert HTML code.

### STEP 3:
Create a simple table using ```<table>``` tag in html.

### STEP 4:
Add header row using ```<th>``` tag.

### STEP 5:
Add your timetable using ```<td>``` tag.

### STEP 6:
Execute the program using runserver command.

## PROGRAM:
```
<html></html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.jpg" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lavender">
<caption><b>SLOT TIME TABLE - Ramkumar s (212223220085)</b></caption>
<tr align="center">
<th bgcolor="skyblue">Day/Time</th>
<th bgcolor="skyblue">Monday
<th bgcolor="skyblue">Tuesday
<th bgcolor="skyblue">Wednesday
<th bgcolor="skyblue">Thursday
<th bgcolor="skyblue">Friday
<th bgcolor="skyblue">Saturday
</tr>
<tr align="center">
<th bgcolor="skyblue">8am-10am</th>
<td >Free Slot</td>
<td >Operating System</td>
<td >Fundamentals of C Programming</td>
<td >Operating System</td>
<td >Fundamentals of Web Application Development</td>
<td >Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">10am-12pm</th>
<td >Fundamentals of C Programming</td>
<td >Principles of Chemistry in Engineering</td>
<td >Fundamentals of Web Application Development</td>
<td >Statistics and Numerical Methods</td>
<td >Principles of Chemistry in Engineering</td>
<td >Statistics and Numerical Methods</td>
</tr>
<tr>
<th bgcolor="skyblue">12pm-01pm</th>
<td colspan="6" align="center"> L U N C H - B R E A K</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="skyblue">01pm-03pm</th>
<td >Computer Networks</td>
<td >Free Slot</td>
<td >Mentor Meeting</td>
<td >Free Slot</td>
<td >Free Slot</td>
<td >Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">03pm-05pm</th>
<td >Introduction to Data Science</td>
<td >Fundamentals of Web Application Development</td>
<td >Computer Networks</td>
<td >Introduction to Data Science</td>
<td >Free Slot</td>
<td >Free Slot</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject Code:</th>
<th>Subject Name:</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI403</td>
<td>Introduction to Data Science</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS405</td>
<td>Operating System</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS406</td>
<td>Computer Networks</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT:
![Screenshot 2024-10-08 213143](https://github.com/user-attachments/assets/84706bef-cdaf-46b8-a92c-b3b742a9c0c2)


## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.

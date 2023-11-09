# Ex03 Time Table
## Date:31.10.2023

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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - HAREESH R(23013706)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>EINGINEERING DESIGN AND MODELLING</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FREE SLOT</td>
<td>EINGINEERING DESIGN AND MODELLING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>DIGITAL ELECTRONICS</td>
<td>SOFT SKILLS</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>DIGITAL ELECTRONICS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
```


## output
![Alt text](<Screenshot (8).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

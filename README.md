# Ex03 Time Table
## Date:21.03.2024

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
<head>
<title> TIME TABLE </title>   
</head>
<body>

<center>
<img src="/static/logo.png"height="100"width="540">
</center>

<br>

<center>
<table align="centre" border="6" bgcolor="pink" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE - M.Hashwatha (212223240051) </caption>

<tr bgcolor="grey">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>

<tr align="center">
   <th bgcolor="grey"> 8-10 </th>
   <td> Digital Electronics</td>
   <td> Statistics </td>
   <td>  Free Slot </td>
   <td>  Free Slot </td>
   <td> Web Applicaton </td>
   <td> Probability </td>
</tr>

<tr align="center">
    <th bgcolor="grey"> 10-12 </th>
    <td> Free Slot</td>
    <td> Web Applicaton </td>
    <td> Free Slot</td>
    <td> Probability </td>
    <td> C programming </td>
    <td> Statistics </td>
</tr>

<tr align ="center">
    <th bgcolor="grey"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>

<tr align ="center">
    <th bgcolor="grey"> 1-3 </th>
    <td > Free SLOT </td>
    <td> Physics </td>
    <td> Physics </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>

<tr align ="center">
    <th bgcolor="grey"> 3-5 </th>
    
    <td>  C Programming </td>
    <td> Free Slot </td>
    <td> Web Applicaton </td>
    <td> Digital Electronics </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>

</tr>

</table>

</center>
<br>
<center>

<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>

<tr align="center">
<td> 1. </td>
<td> 19AI414 </td>
<td> Fundamental of Web Applicaton </td>
</tr>

<tr align="center">
<td> 2. </td>
<td> 19EE404 </td>
<td> Digital Electronics </td>
</tr>

<tr align="center">
<td> 3. </td>
<td> 19MA211 </td>
<td> Statistics </td>
</tr>

<tr align="center">
<td> 4. </td>
<td> 19MA222 </td>
<td> Probability </td>
</tr>

<tr align="center">
<td> 5. </td>
<td> 19PH214 </td>
<td> Physics </td>
</tr>

<tr align="center">
<td> 6. </td>
<td> 19AI304 </td>
<td> C Programming </td>
</tr>

</center>

</html>

```
## OUTPUT

![alt text](<Screenshot 2024-03-22 091954.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

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
<html>
<title>title</title>
<body>
    <h3>name:Gajalakshmi</h3>
    <h3>ref.num: 23011881</h3>
    <img src ="/static/logo.png" height="100" width="540">
<table border="6"cellspacing="4"cellpadding="4">
<caption>my time table</caption>

<tr>
<th bgcolor="sky blue"align="center">day/time</th>
<th bgcolor="sky blue"align="center">8:9 am</th>
<th bgcolor="sky blue"align="center">9:10 am</th>
<th bgcolor="sky blue"align="center">10:11 am</th>
<th bgcolor="sky blue"align="center">11:12 am</th>
<th bgcolor="sky blue"align="center">12:1 pm</th>
<th bgcolor="sky blue"align="center">1:2 pm</th>
<th bgcolor="sky blue"align="center">2:3 pm</th>
<th bgcolor="sky blue"align="center">3:4 pm</th>
<th bgcolor="sky blue"align="center">4:5 pm</th>
</tr>

<tr>
<th bgcolor="sky blue"align="center">monday</th>
<td colspan="2"align="center"bgcolor="orange">free</th>
<td colspan="2"align="center"bgcolor="orange">c programming</th>
<td align="center"bgcolor="orange">lunch</td>
<td colspan="2"align="center"bgcolor="orange">maths</th>
<td colspan="2"align="center"bgcolor="orange">physics</th>
</tr>

<tr>
<th bgcolor="sky blue"align="center">tuesday</th>
<td colspan="2"align="center"bgcolor="orange">english</th>
<td colspan="2"align="center"bgcolor="orange">maths</th>
<td align="center"bgcolor="orange">lunch</td>
<td colspan="2"align="center"bgcolor="orange">free</th>
<td colspan="2"align="center"bgcolor="orange">free</th>
</tr>

<tr>
<th bgcolor="sky blue"align="center">wednesday</th>
<td colspan="2"align="center"bgcolor="orange">web development</th>
<td colspan="2"align="center"bgcolor="orange">computer architecture</th>
<td align="center"bgcolor="orange">lunch</td>
<td colspan="2"align="center"bgcolor="orange">free</th>
<td colspan="2"align="center"bgcolor="orange">c programming</th>
</tr>

<tr>
<th bgcolor="sky blue"align="center">thursday</th>
<td colspan="2"align="center"bgcolor="orange">free</th>
<td colspan="2"align="center"bgcolor="orange">web development</th>
<td align="center"bgcolor="orange">lunch</td>
<td colspan="2"align="center"bgcolor="orange">english</th>
<td colspan="2"align="center"bgcolor="orange">free</th>
</tr>

<tr>
<th bgcolor="sky blue"align="center">friday</th>
<td colspan="2"align="center"bgcolor="orange">free</th>
<td align="center"bgcolor="orange">computer architecture</th>
<td align="center"bgcolor="orange">physics</th>
<td align="center"bgcolor="orange">lunch</td>
<td colspan="2"align="center"bgcolor="orange">web development</th>
<td colspan="2"align="center"bgcolor="orange">soft skills</th>
</tr>

</table>
<table border="4"cellpadding="4">

<caption>subject and their respective subject codes</caption>
<tr>
<th align="center"bgcolor="blue">s.no</th>
<th align="center"bgcolor="blue">subject code</th>
<th align="center"bgcolor="blue">subject name</th>
</tr>

<tr>
<th align="center"bgcolor="blue">1.</th>
<th align="center"bgcolor="yellow">19AI414</th>
<th align="center"bgcolor="gold">fundamentals of web application</th>
</tr>

<tr>
<th align="center"bgcolor="blue">2.</th>
<th align="center"bgcolor="yellow">19CS305</th>
<th align="center"bgcolor="gold">computer architecture</th>
</tr>

<tr>
<th align="center"bgcolor="blue">3.</th>
<th align="center"bgcolor="yellow">fundamentals of c programming</th>
<th align="center"bgcolor="gold">19AI414</th>
</tr>

<tr>
<th align="center"bgcolor="blue">3.</th>
<th align="center"bgcolor="yellow">english</th>
<th align="center"bgcolor="gold">19EN101</th>
</tr>

<tr>
<th align="center"bgcolor="blue">4.</th>
<th align="center"bgcolor="yellow">soft skills</th>
<th align="center"bgcolor="gold">19EY701</th>
</tr>

<tr>
<th align="center"bgcolor="blue">5.</th>
<th align="center"bgcolor="yellow">calculus and matrix algebra</th>
<th align="center"bgcolor="gold">19MA201</th>
</tr>

<tr>
<th align="center"bgcolor="blue">6.</th>
<th align="center"bgcolor="yellow">physics for quantum computing</th>
<th align="center"bgcolor="gold">19CS305</th>
</tr>

</table>
</body>
</html>
```


## OUTPUT
![Screenshot 2023-11-17 140827](https://github.com/Gajalakshmivelmurugan/slot/assets/144871940/370656c6-7af9-41d7-b7cc-7b486dd1ed32)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

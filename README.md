# Ex03 Time Table
## Date:18-03-2024

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

## PROGRAM:

'''
<html>
	<head>
		<title>
			Time Table
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="red">
			<caption>SLOT TIME TABLE- Sri Harish B (212223220110) </caption>
            <br>
			<tr>
				<th bgcolor="lightgray"> Day/Time </th>
				<th bgcolor="lightgray"> Monday </th>
				<th bgcolor="lightgray"> Tuesday </th>
                <th bgcolor="lightgray"> Wednesday </th>
                <th bgcolor="lightgray"> Thursday </th>
                <th bgcolor="lightgray"> Friday </th>
                <th bgcolor="lightgray"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free SLOT </td>
                <td> Free SLOT </td>
                <td> Free SLOT </td>
                <td> CALC </td>
                <td> FWAB </td>
                <td> CREATIVE </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> Free SLOT </td>
                <td> OS </td>
                <td> PROB </td>
                <td> OS </td>
                <td> PYTHON </td>
                <td> Free SLOT </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> CALC </td>
                <td> FWAD </td>
                <td> Free SLOT </td>
                <td> FWAD </td>
                <td> CN </td>
                <td> PROB </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> Free SLOT </td>
                <td> Free SLOT </td>
                <td> CN </td>
                <td> PYTHON </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="orange">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19AI301 </td>
                    <td align="center"> Python Programming (PYTHON) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (FWAD) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19CS405 </td>
                    <td align="center"> Operating System (OS) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19CS406 </td>
                    <td align="center"> Computer Networks(CN) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19MA201 </td>
                    <td align="center"> Calculus And Matrix Algebra(CALC) </td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19MA222 </td>
                    <td align="center"> Probability and Queueing Models(PROB) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19EY702 </td>
                    <td align="center"> Creative skills for communication (CRT SKILLS) </td>
                </tr>
                
                </table>
	</body>

</html>
'''

## OUTPUT:

![alt text](<Screenshot 2024-03-18 210353.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

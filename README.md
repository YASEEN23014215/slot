# Ex03 Time Table
## Date:7.10.2024

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
		<title>
			Software Companies
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="yellow">
			<caption>SLOT TIME TABLE- YASEEN (212223220126) </caption>
            <br>
			<tr>
				<th bgcolor="lightgray"> Day/Time </th>
				<th bgcolor="lightgray"> Monday </th>
				<th bgcolor="lightgray"> Tuesday </th>
                <th bgcolor="lightgray"> Wednesday </th>
                <th bgcolor="lightgray"> Thursday </th>
                <th bgcolor="lightgray"> Friday </th>
                
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> FWAD </td>
                <td> Free Slot </td>
                <td> SNM </td>
                
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> Free slot </td>
                <td> Intro to Ds </td>
                <td> SNM </td>
                <td> Intro to Ds </td>
                <td> Transforms </td>
                
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> CN </td>
                <td> Free slot </td>
                <td> ECM </td>
                <td> Free slot </td>
                <td> RA </td>
                
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> Transforms </td>
                <td> Free slot </td>
                <td> CN </td>
                <td> DS </td>
                <td> DS </td>
                
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19CS406 </td>
                    <td align="center">COMPUTER NETWORKS(CN)  </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (FWAD) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI408 </td>
                    <td align="center"> DATA STRUCTURES(DS) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19MA211 </td>
                    <td align="center"> STATISTICS AND NUMERICAL METHOD(SNM) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19EY709 </td>
                    <td align="center"> REASONING ABILITY(RA) </td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19AI403 </td>
                    <td align="center"> INTRODUCTION TO DATA SCIENCE (Intro to DS)) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19MA219 </td>
                    <td align="center"> TRANSFORMS AND ITS APPLICATIONS(Transforms) </td>
                </tr>
            
                
                </table>
	</body>

</html>

```

## OUTPUT
![image](https://github.com/user-attachments/assets/751a10d8-7cbe-4958-813f-8fdf821b05e5)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

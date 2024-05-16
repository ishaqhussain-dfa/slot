# Ex03 Time Table
## Date:
04/04/2024

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
# SLOT TIME TABLE
```

<html>
     <head>
              <title> SLOT TIME TABLE </title>
     </head>
     <body bgcolor="black" TEXT="white">
<center>
     <img src="logo.jpg"  height="100" width="500" align="center" /></center>
          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor="skyblue" align="center" >
          <CAPTION align=“top”> TIME TABLE </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="gray">   DAY/TIME </th>
               <th bgcolor="red">   MONDAY </th>
               <th bgcolor="red">   TUESDAY </th>
               <th bgcolor="red">   WEDNESDAY </th>
               <th bgcolor="red">   THURSDAY </th>
               <th bgcolor="red">   FRIDAY </th>
               <th bgcolor="red"> SATURDAY</th>
               </tr>
               <tr>
                <th bgcolor="purple"> 8-10 </th>
                <td> FWAD </td>
                <td> -- </td>
                  <td> RES </td>
                <td> -- </td>
                <td> ADC </td>
                <td> --</td>
               </tr>
               <tr>
                <th bgcolor="purple"> 10-12 </th>
                <td> 19EY706 </td>
                <td> SPM </td>
                <td> ADC </td>
                <td> SPM </td>
                <td> -- </td>
                <td> --</td>
               </tr>
               <tr>
                <th bgcolor="purple"> 12-1 </th>
                 <td colspan="6" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="purple"> 1-3 </th>
                <td> DS </td>
                <td> OS </td>
                <td> DS </td>
                <td> OS </td>
                <td> ADC </td>
                <td> --</td>
               </tr>
               
              
              <tr>
               <th bgcolor="purple"> 3-5 </th>
               <td> -- </td>
               <td> RES </td>
               <td> -- </td> 
               <td> FWAD </td> 
               <td> -- </td>
               <td> FWAD</td>
              </tr>
           </table>
            <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
           <tr>
           <th> S.No </th>
             <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           <th>FACULTY</th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> Fundamental of web application and development </td>
           <td>SaravanaKumar J</td>
           </tr>
           <tr>
           <td> 2. </td>
           <td> 19EY706 </td>
           <td> Company Specific Assessments for Employability </td>
           <td>ManojKumar S</td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19IT405</td> 
           <td> Data Structures using Python</td>
           <td>Maha Lakshmi</td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> 19CS504 </td>
           <td> Software Project Management </td>
           <td>VelMurugan N</td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19CS545 </td>
           <td> Open Source Operating System </td>
           <td>Advantage Pro Faculty</td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19EE603 </td>
           <td> Renewable Energy Source </td>
           <td>Rajalingam S</td>
           </tr>
           <tr>
            <td> 7. </td>
            <td> 19EC306 </td>
            <td> Analog and Digital Communication </td>
            <td>Hema Malini A</td>
            </tr>
           </table>
              
        </body>
</html>

```

## OUTPUT
![output](https://github.com/KGSatheeshKumar/slot/assets/128453421/86e5b0d7-15ed-4251-b6fb-1edb6e90616f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

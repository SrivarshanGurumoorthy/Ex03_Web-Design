# Ex.03 Slot Time Table
## AIM
  To create slot time table.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the college logo using ```<img>``` tag.

### STEP-3
  Use the ```<table>``` tag with proper cell spacing and cell padding.  

### STEP-4
  Give your name and register number as table title using ```<caption>``` tag.

### STEP-5
  Enter the slot times and days as table header using ```<th>``` tag.
  
### STEP-6
  Type the subjects in the respective slots using ```<tr>``` and ```<td>``` tags.
 
### STEP-7
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
  <h1 align = "center"> SLOT TIMETABLE SRIVARSHAN(212222250027)</h1>
  </head>
  <body>

    <img src="deeps.png"  align = "center" >
<table>
 
  <table border="5" cells spacing="15">
  <tr>
    <th>DAY/TIME</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
      </colgroup>
    </tr>
  <tr style="background-color:cyan">
    <td  style="background-color:yellow"> 8-10</td>
    <td>FUNDAMENTALS OF PROGRAMMING</td>
    <td> COMMUNACATIVE ENGLISH</td>
    <td>PHYSICS FOR QUANTUM COMPUTING</td>
    <td>STATISTICS AND NUMERICAL METHODS</td>
    <td>FUNDAMENTALS OF C PROGRAMMING </td>
  </tr>
  <tr style="background-color:cyan">
    <td style="background-color:yellow">10-12</td>
    <td>FREE SLOT</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING </td>
    <td>FREE SLOT </td>
    <td>STATISTICS AND NUMERICAL METHODS</td>
  </tr>
  <tr style="background-color:cyan">
    <td style="background-color:yellow">12-1</td>
   <td colspan="5" align="center">LUNCH</td>
    </tr>
  
  <tr style="background-color:cyan">
    <td style="background-color:yellow">1-3</td>
    <td>FREE SLOT</td>
    <td>FREE SLOT</td>
    <td>COMMUNICATIVE ENGLISH</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENTS</td>
    <td>SOFT SKILLS</td>
    </tr>
  <tr style="background-color:cyan">
    <td style="background-color:yellow">3-5</td>
    <td>STASTISTICS AND NUMERICAL METHODS</td>
    <td>FREE SLOT</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENTS</td>
    <td>PHYSICS FOR QUANTUM COMPUTING</td>
    <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </TR>
</table> 
  </body>
</html>
```

## OUTPUT
![Screenshot (47)](https://user-images.githubusercontent.com/127816583/233350562-b293aee8-5807-4d27-8265-989f173730ef.png)


## RESULT
 Slot time table is created successfully.

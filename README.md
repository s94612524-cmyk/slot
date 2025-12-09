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
html>



<head>
    <title>Newpage</title>
    
</head>


<body>

  <img src= "LOGO.jpg" width="200">  


    <img src="sanjay333.jpg"  height="200px" width="1000px">

        <h1 style="text-align:center;" >TIME TABLE SANJAY.S 25017513</h1>

    <table class="table1">
        <style>
    .table1 {
      width: 70%;
      margin: 10%;
      border-collapse: collapse; 
      background-color:rgb(255, 255, 255); 
    }

    .table1
    th{
        border: 2px solid rgb(0, 0, 0);
        padding: 50px solid rgb(255, 255, 255);
        background-color: rgb(255, 255, 255);
        text align: center;
    
    }

    .table1
    td{border: 1px solid rgb(0, 0, 0);
       padding: 30px solid rgb(255, 255, 255);
       background-color: rgb(9, 210, 255);
       text align: center; 
    
    }
    </style>


        <h1>
            <tr>
            <th>TIME/DAY</th>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THUR</th>
            <th>FRI</th>
            <th>SAT</th>
            </tr>

            <tr>
                <th>8-10 AM</th>
                <td>Python</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>NO SCHEDULE</td>
                <td>NO SCHEDULE</td>
                <td>NO SCHEDULE</td>
        
            </tr>

            <tr>
                <th>10-12 AM</th>
                <td>python</td>
                <td>NO SCHEDULE</td>
                <td>NO SCHEDULE</td>
                <td>ENG</td>
                <td>PYTHON</td>
                <td>NO SCHEDULE</td>
            </tr>

            <tr>
                <th>1-3 PM</th>
                <td>WEB</td>
                <td>PYTHON</td>
                <td>MENTOR MEET</td>
                <td>WEB</td>
                <td>PYTHON</td>
                <td>NO SCHEDULE</td>
            </tr>

            <tr>
                <th>3-5 PM</th>
                <td>ENG</td>
                <td>WEB</td>
                <td>ENG</td>
                <td>NO SCHEDULE</td>
                <td>NO SCHEDULE</td>
                <td>ENG</td>
            </tr>

        

        </h1>

    </table>

    <table class="table2">
         

        <h1>
            <style>
    .table2 {
      width: 70%;
      margin: 10%;
      border-collapse: collapse; 
      background-color:white; 
    }

    .table2
    th{
        border: 1px solid rgb(0, 0, 0);
        padding: 40px solid rgb(255, 255, 255);
        background-color: antiquewhite;
        text-align: center;
    
    }

    .table2
    td{border: 1px solid rgb(0, 0, 0);
       padding: 30px solid rgb(255, 255, 255);
       background-color: rgb(231, 195, 65);
       text-align: center; 
    
    }
    </style>
            <tr>
            <th>S.no</th>
            <th>subject code</th>
            <th>subject name</th>
            </tr>

            <tr>
                <th>1</th>
                <td>19AI301</td>
                <td>Python programming</td>
            </tr>

            <tr>
                <th>2</th>
                <td>19AI414</td>
                <td>Fundementals of web application development</td>
            </tr>

            <tr>
                <th>3</th>
                <td>19EN101</td>
                <td>Communicative english</td>
            </tr>

        </h1>

    </table>


</body>

</html>
```

## OUTPUT

<img width="1595" height="904" alt="Screenshot 2025-12-09 153401" src="https://github.com/user-attachments/assets/539b1c61-5f76-4080-b2e5-c0c709ced4f1" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

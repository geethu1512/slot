# Ex03 Time Table
## Name : Geethu R
## Register No.: 212224040089
## Date: 19-04-2025

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
~~~
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - GEETHU, 212224040089</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid black;
            text-align: center;
            padding: 8px;
        }

        img {
            display: block;
            margin: 0 auto;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>

    <!-- New logo line as requested -->
    <img src="/static/logo.png" height="100" width="540" alt="Logo">

    <!-- Optional: you can keep this old logo or remove it -->
    <!-- <img src="logo.png"> -->

    <div class="center-text">
        <p><strong>SLOT TIME TABLE - GEETHU (212224040089)</strong></p>
    </div>

    <table>
        <tr>
            <th bgcolor="Yellow">Day/Time</th>
            <th bgcolor="Yellow">Monday</th>
            <th bgcolor="Yellow">Tuesday</th>
            <th bgcolor="Yellow">Wednesday</th>
            <th bgcolor="Yellow">Thursday</th>
            <th bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th bgcolor="Yellow">8-10</th>
            <td colspan="3" bgcolor="Cyan">FREE SLOT</td>
            <td bgcolor="Cyan">PHY</td>
            <td bgcolor="Cyan">CHE</td>
        </tr>
        <tr>
            <th bgcolor="Yellow">10-12</th>
            <td bgcolor="Cyan">GER</td>
            <td bgcolor="Cyan">FREE SLOT</td>
            <td bgcolor="Cyan">FWAD</td>
            <td bgcolor="Cyan">FWAD</td>
            <td bgcolor="Cyan">PHY</td>
        </tr>
        <tr>
            <th bgcolor="Yellow">12-1</th>
            <td colspan="5" bgcolor="Cyan">LUNCH</td>
        </tr>
        <tr>
            <th bgcolor="Yellow">1-3</th>
            <td colspan="2" bgcolor="Cyan">FREE SLOT</td>
            <td bgcolor="Cyan">MAT</td>
            <td bgcolor="Cyan">MAT</td>
            <td bgcolor="Cyan">SS</td>
        </tr>
        <tr>
            <th bgcolor="Yellow">3-5</th>
            <td colspan="2" bgcolor="Cyan">FREE SLOT</td>
            <td bgcolor="Cyan">GER</td>
            <td bgcolor="Cyan">CHE</td>
            <td bgcolor="Cyan">FWAD</td>
        </tr>
    </table>

    <table>
        <tr>
            <th bgcolor="White">S. No.</th>
            <th bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <td bgcolor="White">1.</td>
            <td bgcolor="White">19AI41</td>
            <td colspan="2" bgcolor="White">Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td bgcolor="White">2.</td>
            <td bgcolor="White">19EN612</td>
            <td colspan="2" bgcolor="White">German Basic (GER)</td>
        </tr>
        <tr>
            <td bgcolor="White">3.</td>
            <td bgcolor="White">19PH206</td>
            <td colspan="2" bgcolor="White">Physics for Information Technology (PHY)</td>
        </tr>
        <tr>
            <td bgcolor="White">4.</td>
            <td bgcolor="White">19CY205</td>
            <td colspan="2" bgcolor="White">Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td bgcolor="White">5.</td>
            <td bgcolor="White">19MA201</td>
            <td colspan="2" bgcolor="White">Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td bgcolor="White">6.</td>
            <td bgcolor="White">19EY701</td>
            <td colspan="2" bgcolor="White">Soft Skills (SS)</td>
        </tr>
    </table>

</body>
</html>
~~~


## OUTPUT
![output](https://github.com/user-attachments/assets/1c17d8aa-a437-48da-9146-cc46dd20b29f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

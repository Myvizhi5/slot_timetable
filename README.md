# Ex03 Time Table
## Date:29-09-25

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
from http.server import HTTPServer, BaseHTTPRequestHandler

content = '''
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="cyan">
    <table border="1" align="center" bgcolor="pink" cellpadding="10"
    <caption><h1 align="center">List of protocol</h1></caption>
    <tr>
        <th>S.NO</th>
        <th>Name of Layers</th>
        <th>Name of protocols</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Application Layer</td>
        <td>HTTP,FTP</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Transport Layer</td>
        <td>TCP & UDP</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Internet Layer</td>
        <td>ICMP & ARP</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Network Access Layer</td>
        <td>Ethernet & Frame Relay</td>
    </tr>
    </table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-27 101424-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

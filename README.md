# EX01 Developing a Simple Webserver
## Date:15.10.2026
## Reg No:26017981

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Network Protocols and Abbreviations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f9f9f9;
        }
        table {
            width: 100%;
            max-width: 800px;
            border-collapse: collapse;
            margin: 20px auto;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #007BFF;
            color: white;
            text-transform: uppercase;
            font-size: 14px;
            letter-spacing: 0.5px;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        abbr {
            font-weight: bold;
            color: #333;
            text-decoration: none;
            border-bottom: 1px dotted #666;
            cursor: help;
        }
    </style>
</head>
<body>

    <h2 style="text-align: center; color: #333;">Common Network Protocols</h2>

    <table>
        <thead>
            <tr>
                <th>Abbreviation</th>
                <th>Protocol Name</th>
                <th>Standard Port</th>
                <th>Primary Function</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><abbr title="HyperText Transfer Protocol">HTTP</abbr></td>
                <td>HyperText Transfer Protocol</td>
                <td>80</td>
                <td>Transmitting web pages across the internet.</td>
            </tr>
            <tr>
                <td><abbr title="HyperText Transfer Protocol Secure">HTTPS</abbr></td>
                <td>HyperText Transfer Protocol Secure</td>
                <td>443</td>
                <td>Securely transmitting encrypted web pages.</td>
            </tr>
            <tr>
                <td><abbr title="Transmission Control Protocol">TCP</abbr></td>
                <td>Transmission Control Protocol</td>
                <td>N/A</td>
                <td>Reliable, connection-oriented data delivery.</td>
            </tr>
            <tr>
                <td><abbr title="User Datagram Protocol">UDP</abbr></td>
                <td>User Datagram Protocol</td>
                <td>N/A</td>
                <td>Fast, connectionless data transmission.</td>
            </tr>
            <tr>
                <td><abbr title="File Transfer Protocol">FTP</abbr></td>
                <td>File Transfer Protocol</td>
                <td>20, 21</td>
                <td>Transferring files between a client and a server.</td>
            </tr>
            <tr>
                <td><abbr title="Domain Name System">DNS</abbr></td>
                <td>Domain Name System</td>
                <td>53</td>
                <td>Translating human-readable domain names to IP addresses.</td>
            </tr>
            <tr>
                <td><abbr title="Simple Mail Transfer Protocol">SMTP</abbr></td>
                <td>Simple Mail Transfer Protocol</td>
                <td>25</td>
                <td>Sending emails across networks.</td>
            </tr>
            <tr>
                <td><abbr title="Secure Shell">SSH</abbr></td>
                <td>Secure Shell</td>
                <td>22</td>
                <td>Securely logging into remote systems and servers.</td>
            </tr>
            <tr>
                <td><abbr title="Dynamic Host Configuration Protocol">DHCP</abbr></td>
                <td>Dynamic Host Configuration Protocol</td>
                <td>67, 68</td>
                <td>Automatically assigning IP addresses to network devices.</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
~~~

## OUTPUT:

![alt text](<Screenshot 2026-10-15 142556.png>)
## RESULT:
The program for implementing simple webserver is executed successfully. add-A


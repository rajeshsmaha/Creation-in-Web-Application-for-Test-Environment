# CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
## AIM
To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Explain about the Experiment.
## ALGORITHM
# Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
# Step 2:
Connect to the instance using SSH and install a web server like Apache
# Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.
# Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
# webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```
## OUTPUT
### REG NUMBER:212223040165
### NAME:RAJESHWARAN D


# TERMINAL
![image](https://github.com/user-attachments/assets/90b732c2-d9c2-48b8-8633-69e5313414e6)
![image](https://github.com/user-attachments/assets/2007c9cf-d98d-4226-9d4d-e8cfabace9eb)
![image](https://github.com/user-attachments/assets/3504238b-88e1-419d-8165-38444cc6688a)
# WEBPAGE
![image](https://github.com/user-attachments/assets/4c829de3-3f04-45a3-9116-ee018ebb0a47)
## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  





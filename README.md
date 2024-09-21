# Computer Science II
## Lab 5.0 - MySQL

Install the MySQL software and test your MySQL username and password.

This is a lab used in Computer Science II (CSCE 156) for Fall 2024 
in the [School of Computing](https://computing.unl.edu) 
at the [University of Nebraska-Lincoln](https://www.unl.edu).

## Overview

   
### Lab Objectives & Topics

Following the lab, you should be able to:

-   install the MySQL software
  
-   connect to a MySQL server using your MySQL username and password

### Peer Programming Pair-Up

At the start of each lab, you may find a team member by yourself or may be randomly paired up with another student by
a lab instructor.  One of you will be designated the *driver* and the other the *navigator*. Each week you should try to alternate: if you were a driver last week, be a navigator next, etc. If you prefer to work on this lab by yourself, that is fine too. 


## 1. Install MySQL Workbench

MySQL Workbench is a free Integrated Development Environment (IDE) for MySQL.  You can download and install
MySQL Workbench at the following URL.

https://www.mysql.com/products/workbench/
    

## 2. Connect to a MySQL server on a Linux server

We connect to the MySQL server running on a Linux server of the School of Computing.

1. Find the email about your MySQL username and password, which was sent to you several weeks ago.

2. Run the MySQL Workbench that you just installed

3. Create a new MySQL connection by clicking the plus sign 
<p align="center">
<img src="images/Workbench-1.png" alt="create a new connection" width="70%"/>
</p>  

4. Type the hostname ***`nuros.unl.edu`***, your MySQL username (for example, my MySQL username is lxu3), and a connection name (for example, SOC). We use the default port number 3306. Then click the "OK" button.
<p align="center">
<img src="images/Workbench-2.png" alt="hostname" width="70%"/>
</p>  

5. Click to open the MySQL connection that we just created 
<p align="center">
<img src="images/Workbench-3.png" alt="open a new connection" width="70%"/>
</p>  

6. Type your MySQL password 
<p align="center">
<img src="images/Workbench-4.png" alt="password" width="70%"/>
</p>  


7. If you see a "Connection Warning" window, just click the "Continue Anyway" button  
<p align="center">
<img src="images/Workbench-5.png" alt="warning" width="70%"/>
</p>  

  But if you see a "Cannot Connect to Database Server" window, then one of the following information is wrong
* hostname must be `nuros.unl.edu`
* username must be the username in the email sent to you
* password must be the password in the email sent to you
<p align="center">
<img src="images/Workbench-5error.png" alt="error" width="70%"/>
</p>  

8. Then you are successfully connected to the MySQL server. 
<p align="center">
<img src="images/Workbench-6.png" alt="connect" width="70%"/>
</p>  




## 3. Activities 

Type and execute the following MySQL statements.

Note that after typing each statement, please click the icon highlighted in the red box to execute the statement. Also note that if MySQL Workbench does not find any error in a statement, there is a blue dot before the statement.
<p align="center">
<img src="images/Workbench-5.png" alt="execute" width="50%"/>
</p>  

If MySQL Workbench finds an error in a statement, there is a red x before the statement. For example, line 3 in the following screenshot has a typo `iff`.
<p align="center">
<img src="images/Workbench-6.png" alt="invalid" width="50%"/>
</p>  

Replace `lxu3` in the following statement with your MySQL username. 

```sql
use lxu3;
```

## 4. Answer the lab questions on Canvas

* You do not need to submit any code for this lab. Instead please answer the lab questions on Canvas. 

# EMS_Project
Employee Management System with the help of  GUI (Python) and MySQL database.

### First download and install MySQL database and then make one database.

## `Connect with database.`
`Step :- 1`
#### pip install mysql-connector-python


`Step :- 2`
#### import mysql.connector
#### conn = mysql.connector.connect(host='localhost',username='root',password ='R@thod03',database = 'my_project')
#### my_cursor = conn.cursor()

#### conn.commit()
#### conn.close()

#### print("Connection Done!")


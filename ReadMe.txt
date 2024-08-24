How To Access The Folder:
Right click on TimeTableManagementWebApplication folder and select the option extract all.

How To Run or Use The Project:

1.The user shall be able to login using a username and password.
2.If the user does an account they can register by clicking the link on the login page.
(if you find it hard to do so you can use the information on text file 'Tables,txt')
3.The software shall store only the hash of the password in the database.
4.The user shall be able to log into the software with their username and password.
5.The user shall only be able to see their own data and never that of other users.

After successfully logging in the user shall be able to:

1. The user must be able to add multiple modules for the semester. The following data must
be stored for each module:
a. Code, for example, PROG6212
b. Name, for example, Programming 2B
c. Number of credits, for example, 15
d. Class hours per week, for example, 5
2. The user must be able to enter the number of weeks in the semester.
3. The user must be able to enter a start date for the first week of the semester.

When you click the save button, you should be able to view the data by clciking the button 'view data'
which will show the information above with the self stydt calculation time below.

4. The software shall display a list of the modules with the number of hours of self‐study that
is required for each module per week. The number shall be calculated as follows:
self-study hours per week = number of credits x 10 / number of weeks - class hours per week
5. The user must be able to record the number of hours they spend working on a specific
module on a certain date.
6. The software shall display how many hours of self‐study remain for each module for the
current week. This should be calculated based on the number of hours already recorded on
days during the current week.
7. The software shall not persist the user data between runs. The data shall only be stored in
memory while the software is running
First import the tbl_user to mysql to do that,
go to localhost/phpmyadmin/
create database name it as "users"
then click import then select the tbl_user file

copy the myexam folder into your htdocs folder.

then in postman click import then drag MyExam.postman_collection file

to create a user open CreateUser then click body then select x-www-form-urlencoded and add key as follows
firstname,lastname,number,email
NOTE: all fields are required. firstname and lastname only accepts alpha characters while number only accepts number
and has a minimum and maximum number of 11 characters and email only accepts valid email.

to view all user open ViewAll simply hit send button

to view user open ViewUserPerId by ID input ID number in the link then send the request

to delete a user also put the ID in the link then send the request

to update the user data open UpdateUser then put the ID in the link and add the same key in the create user then add
your desire value and hit send button
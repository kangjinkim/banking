# Banking Record System C++ Project #

This banking record system project in C++ is a simple console application 
developed without the use of graphics component. It is more of a database 
project in C++, and is built using the language’s file handling mechanism.
 It is suitable for beginners who want to learn how to add, edit, search, 
 delete or modify records in a file, and how to use file as database overall.

The source code for this project is short – just over 150 lines. The coding has 
been presented in a very understandable manner. The source code needs to be 
compiled in Code::Blocks IDE using GCC compiler. You can download the source 
code plus the executable file for banking record system project in C++ from the 
link below.

This project is originally from 
https://www.codewithc.com/banking-record-system-project-c/ . 
Thank you, Code With C!

## Banking Record System Project Abstract ##

File handling has been effectively used for each feature of this project. 
Here, I am going to describe these features in brief.

 * Add Record:
    For this feature void read_data() function has been used to add banking 
    record into the file. It asks for information such as account number, 
    first name, last name and balance to be entered.

 * Show/List Data:
    With the information provided in add record, the void show_data() function 
    in this banking record system project in C++ show the record corresponding 
    to a particular account number, first name and last name. Current balance 
    of the account holder is displayed.

 * Search Record:
    When the function for this feature is first executed, it shows the total 
    records in the file, and the user can then search by record number. 
    If the record searched for is not found, the banking record system project 
    in C++ displays the message – “Error in opening! File Not Found!!”

 * Edit Record:
    This works in similar manner to the Search feature. When the function for 
    Edit Record is first executed, it shows the total records in the file, and 
    the user can edit the information by providing record number. Then, the C++ 
    project shows all the data in that record, and the user can enter any data 
    to modify. If the record to be edited for is not found, it displays 
    the message – “Error in opening! File Not Found!!”

 * Delete Record:
    First of all, when the function of this feature is executed, it shows all 
    the records in the file, and the user can enter the record number to delete. 
    If the record was not found, this banking record system project in C++ 
    displays the message – “Error in opening! File Not Found!!”

## How to install: ##

```
$ mkdir build
$ cd build
$ cmake ..
$ make
```

## How to execute: ##

```
$ cd build
$ ./banking

***Acount Information System***
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 1

Enter Account Number: 1
Enter First Name: Kangjin
Enter Last Name: Kim
Enter Balance: 100

Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 1

Enter Account Number: 2
Enter First Name: Kangjin
Enter Last Name: Kim
Enter Balance: 200

Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 2

****Data from file****
Account Number: 1
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  100
-------------------------------
Account Number: 2
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  200
-------------------------------
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 3

 There are 2 record in the file
 Enter Record Number to Search: 1
Account Number: 1
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  100
-------------------------------
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 4

 There are 2 record in the file
 Enter Record Number to edit: 1
Record 1 has following data
Account Number: 1
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  100
-------------------------------

Enter data to Modify 

Enter Account Number: 1
Enter First Name: Kangjin
Enter Last Name: Kim
Enter Balance: 110

Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 2

****Data from file****
Account Number: 1
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  110
-------------------------------
Account Number: 2
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  200
-------------------------------
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 5

 There are 2 record in the file
 Enter Record Number to Delete: 2
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 2

****Data from file****
Account Number: 1
First Name: Kangjin
Last Name: Kim
Current Balance: Rs.  110
-------------------------------
Select one option below 
	1-->Add record to file
	2-->Show record from file
	3-->Search Record from file
	4-->Update Record
	5-->Delete Record
	6-->Quit
Enter your choice: 6

$
```

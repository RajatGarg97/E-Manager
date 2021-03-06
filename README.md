# Project-E-Manager

## About

- This project aims to create a command line program for pocket money for students to spend in a particular month. The idea is to manage your expenses on a weekly basis instead of spending heavily in the first half and then living like a pauper in the second.

## Installation
- Fork this project to your GitHub account.
- After forking, enter the following commands in your terminal.
```
$ git clone  https://github.com/user_name/E-Manager
$ cd E-Manager/src
$ g++ main.cpp
$ ./a.out
```
Next should be fairly simple to follow.

## Usage
This is primarily built to use for day-to-day usage in student life. It is very helpful at a later stage of life as well though.

## Contributing
It's great if you want to contribute to this repository. If you are not sure where to start, click [here](https://github.com/salman-bhai/E-Manager/blob/master/CONTRIBUTING.md)

## License
- The software is registered under the [MIT License](https://github.com/salman-bhai/E-Manager/blob/master/LICENSE)


## Versions Of the Application

**v1.0** 
- The program will have a memory life of only one month following which it will have to be reset by the user again. 
- Accounts can be added for a validity of a month and then at the end of the month the account will display the amount of money in the savings account of the applicant.
- This is a basic version of the application with limited memory and primitive input using file memory!
- Allows the user to input a certain amount of money at the beginning of the month and then spend it according to a classification of three types of weeks (given by high-spending week, moderate-spending week and low-spending week) and spend the money without exceeding the limit as decided on each week.

**v2.0**
- Money managing tool which will allows users to show their spending habits and based on the spending habits of users the algorithm will predict the maximum possible way to save money.
- Week classification will be done according to previous spending in that particular month. 
- Use of a MySQL Database allows to store records of a person's expense in a database rather than in a file!
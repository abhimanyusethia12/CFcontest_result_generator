# CFcontest_result_generator
Made to automate IITK PClub's Sport Programmer of the Month Contest.

It takes a csv file as input with roll numbers and code forces handles of students in the following format
>roll number 1 | handle 1

>roll number 2 | handle 2

and takes the contest id as an input

The program gives as an output a csv file with relative ranks of the students in the input csv file who attempted the contest, aling with their roll numbers in the following format
>relative rank | roll number

Students whose names are in the input csv file but did not attempt the contest would be given a rank of 10000
## How to run the programme?

Enter the following in the terminal 

`python CFcontest_result_calculator.py <input file name> <contest id>`

An example input file is present in the repo (input.csv)

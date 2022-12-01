
# Objects and Classes

With solving this problems, I practice working with Classes.

## Problem: Average Grades
Define a class Student, which holds the following information about students: name, list of grades and average grade (calculated property, read-only).
A single grade will be in range [2…6], e.g. 3.25 or 5.50.
Read a list of students and print the students that have average grade ≥ 5.00 ordered by name (ascending), then by average grade (descending). Print the student name and the calculated average grade.

### Example:
#### input: 
6

Petar 3 5 4 3 2 5 6 2 6

Mitko 6 6 5 6 5 6

Gosho 6 6 6 6 6 6

Ani 6 5 6 5 6 5 6 5

Iva 4 5 4 3 4 5 2 2 4

Ani 5,50 5,25 6,00

#### output:
Ani -> 5.58

Ani -> 5.50

Gosho -> 6.00

Mitko -> 5.67

## Problem: Book Library

To model a book library, define classes to hold a book and a library. 
The library must have a name and a list of books. The books must contain the title, author, publisher, release date (in dd.MM.yyyy format), ISBN-number and price.

Read a list of books, add them to the library and print the total sum of prices by author, ordered descending by price and then by author’s name lexicographically.

Books in the input will be in format {title} {author} {publisher} {release date} {ISBN} {price}.
The total prices must be printed formatted to the second decimal place.

### Example:
#### input:
5

LOTR Tolkien GeorgeAllen 29.07.1954 0395082999 30,00

Hobbit Tolkien GeorgeAll 21.09.1937 0395082888 10,25

HP1 JKRowling Bloomsbury 26.06.1997 0395082777 15,50

HP7 JKRowling Bloomsbury 21.07.2007 0395082666 20,00

AC OBowden PenguinBooks 20.11.2009 0395082555 14,00

#### output:

Tolkien -> 40.25

JKRowling -> 35.50

OBowden -> 14.00

## Problem: Count Working Days
Write a program that reads two dates in format dd-MM-yyyy and prints the number of working days between these two dates inclusive. Non-working days are:

•	All days that are Saturday or Sunday.

•	All days that are official holidays in Bulgaria:

o	New Year Eve (1 Jan)

o	Liberation Day (3 March)

o	Worker’s day (1 May)

o	Saint George’s Day (6 May)

o	Saints Cyril and Methodius Day (24 May)

o	Unification Day (6 Sept)

o	Independence Day (22 Sept)

o	National Awakening Day (1 Nov)

o	Christmas (24, 25 and 26 Dec)

All days not mentioned above are working and should count.

### Example:
#### input:
20-12-2015

31-12-2015
#### output:
7








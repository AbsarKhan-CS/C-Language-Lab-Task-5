# C-Language-Lab-Task-5
PF Lab Task 5
FOR LOOP
Task # 01:
A cinema sells tickets for shows 1 through 10 in a day, and the price rises by Rs. 50 for each later show
(show 1 = Rs. 500). Print a schedule showing the show number and its ticket price.

TASK 2:
A teacher has n students in a class. Take n from the user, then take each student's test score (out of 100).
Print the class's total score and average score.

TASK 3:
A person deposits money and it grows using compound interest. Given the number of years, calculate how
much a sum of money grows if it's multiplied by a fixed growth factor each year (this is essentially a
factorial-style repeated multiplication).
WHILE LOOP

TASK 4:
A bank's system needs to verify a 4-to-6 digit PIN entered by a customer. Take the PIN as an integer and,
digit by digit, find the sum of its digits and print the PIN reversed (used as a basic checksum/verification
step).

TASK 5:
A water tank starts at a given level. Every hour, if the tank has an even number of liters, half the water
drains out; if it has an odd number, the tank operator adds 3x + 1 liters as an emergency refill rule (a
Collatz-style simulation). Simulate until the tank reaches exactly 1 liter, printing the level each hour and
the total number of hours taken.
DO WHILE LOOP

TASK 6:
A university's result-entry portal must ensure a data-entry clerk cannot submit a mark outside the 0–100
range. Keep asking the clerk to re-enter the mark until it is valid, then declare the student Pass (≥50) or
fail.

TASK 7:
A self-service kiosk shows a menu: 1) Add Item, 2) Remove Item, 3) View Total, 4) Checkout. The kiosk
should keep showing this menu and processing the customer's choice repeatedly until they select
Checkout, since the menu must appear at least once even for a walk-up customer.


1D ARRAYS
TASK 8:
A weather station records the temperature (°C) every hour for 8 hours in a day. Store the readings in an
array and report the hottest temperature, the coldest temperature, and the second-hottest temperature of
the day.

TASK 9:
A warehouse stores the stock count of 10 different product shelves in an array. Print the shelf stock levels
in reverse order (as if scanning from the back of the warehouse to the front), then let a staff member
search for a specific stock count and report which shelf (index) holds it, or that it doesn't exist.

TASK 10:
A signup form takes a username (up to 20 characters) as input. Count how many vowels and consonants
it contains (a basic strength heuristic), then convert the username to all uppercase to store it in the system's
case-insensitive username database.

TASK 11:
A city traffic department is developing a simple priority system for 5 emergency vehicles. Each
vehicle is assigned a 4-bit priority code, represented by an integer from 0 to 15, and its current
speed is also recorded. Write a C program that stores the priority codes and speeds of all 5 vehicles
in arrays. For each vehicle, perform a left shift by 2 bits and a right shift by 1 bit on its priority
code. Display the original priority code, left-shifted value, right-shifted value, and speed for each
vehicle. Assign the vehicle a priority level according to these rules: High Priority if the left-shifted

TASK 12:
A security company is developing an access control system for a commercial building. The system
assigns 10 employees an integer access code between 1 and 255. Write a C program that stores the
10 access codes in an array and takes all codes as input. For every access code, perform a left shift
by 2 bits and a right shift by 1 bit. Display the original code, left-shifted value, and right-shifted
value for every employee. An access code is classified as Accepted when its left-shifted value is
greater than 100 and its right-shifted value is an even number. Otherwise, classify it as Flagged.
At the end, display the total number of Accepted and Flagged codes, the highest original access
code, and all original access codes whose right-shifted value is greater than 20.
value is greater than 20 and the speed is at least 80 km/h; Medium Priority if the left-shifted value
is greater than 10 and the speed is at least 60 km/h; otherwise, assign Normal Priority. At the end,
display the total number of vehicles in each priority category.

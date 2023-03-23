# handout-6-1

Write a program to do the following:
a.	Generate 10 random numbers between 10 and 40 and store them in linked list pointed by ALL. 
b.	Create an algorithm for making changes to the list ALL such that all even numbers appear at the beginning of the list. Use one of the following hints to  write your program

HINT 1. While traversing ALL, collect even numbers in list EVEN and odd numbers in list ODD. Now to get the final list, simply append the two lists EVEN and ODD
HINT 2. While traversing ALL, create a NEW list by inserting even numbers in front and odd numbers at the rear of the list 

Sample run:
  Original list ALL: 20->37->19->33->24->38->11->13->19->24->NULL
  New list ALL     : 24->38->24->20->37->19->33->11->13->19->NULL

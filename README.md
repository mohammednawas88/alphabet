# ArrayList of Linkedlist problem

Write a java program that repeatedly prompts the user to input a string starting with letters from the English alphabet. The program must stop getting input when the user inputs the string “STOP” Consider The word STOP as case insensitive (i.e. STOP = stop = Stop = Stop ….) . Then the program must display the words starting with each letter (Case-Sensitive) from the alphabet in a separate line (e.g. you need to make a new line after all words starting with a specific letter are finished. 

Your program must be written according to the following rules:
Create an array list of 52 linked lists. 
Each linked list will have the strings starting with a specific letter each in a separate node.  For example element 0 in the array list will have a linked list of the strings starting with a and element 1 in the array list will have a linked list of the Strings starting with  A, element 2 in the array list will have a linked list of the strings starting with b element 3 in the array list will have a linked list of the strings starting with B,……, element 50 in the array list will have a linked list of the strings starting with z element 51 in the array list will have a linked list of the strings starting with Z
Use the classes MyArrayList and MylinkedList. (No Need to re-implement them). 
Strings NOT starting with a letter from the English alphabet must be ignored.

Consider the case when the user input the following strings consequently:
Ali Ahmad Abed Basel basel Ayshe ayshe 123 Anas Baba betul Zaki Ziko zakiyya stop

The output will be:
ayshe
Ali Ahmad Abed Ayshe Anas
basel betul
Basel Baba
zakiyya
Zaki Ziko 

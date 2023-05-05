Download Link: https://assignmentchef.com/product/solved-cse102-assignment-9
<br>
<span class="kksr-muted">Rate this product</span>

Description: In this homework, you will implement a sequence model for banking system. This homework will be implemented by using Structs in C.

The bank has five type of customer, which are labelled as 0, 1, 2, 3, 4. These labels showed us customer’s job. 0 is employee, 1 is retired, 2 is student, 3 is unemployed and 4 is other.

Each customer’s construct must include Name, Age and Label. These are will be get from user input with using command line. Name, age and label must be keep in struct.

Banking system keeps maximum 50 customer in same time.Label 0 has the highest priority, then 1, 2, 3, 4 have the lower priorities respectively.

Example : sequence contains 0-0-0-1-2-2-3-4-4-5 and new customer want to join with label 1. Sequence will be updated like this : 0-0-0-1-1-2-2-3-4-4-5

To prevent starvation when occur 0 labelled customers comes continuously, each type of customer has limitations like this: 0 label customer can join 5 times in a row, 1 label customer can join 3 times in row, 2 label customer can join 3 times in a row, 3 label customer can join 2 times in a row, 4 label customer can join 2 times in a row.

Example : sequence contains 0-0-0-0-1-1-2-3-3-4 , if two customers want to join sequence label 1, the new sequence will be like this: 0-0-0-0-1-1-1-2-3-3-4-1,

sequence contains 0-0-0-0-1-1-2-3-3-4 , if one customers want to join sequence label 0, the new sequence will be like this: 0-0-0-0-0-1-1-2-3-3-4,

sequence contains 0-0-0-0-1-1-2-3-3-4 , if one customers want to join sequence label 3, the new sequence will be like this: 0-0-0-0-1-1-2-3-3-4-3

Program should appear as follows:

***********Banking System*********** Current Sequence:1-Add customer2-Process customer

2

There is not any customer in bank system sequence. Current Sequence:1-Add customer2-Process customer
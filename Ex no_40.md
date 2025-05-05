## Given an array of strings sorted in lexicographical order, print all of its permutations in strict lexicographical order. If two permutations look the same, only print one of them. See the 'note' below for an example.

Complete the function next_permutation which generates the permutations in the described order.

## For example, s=[ab,bc,cd]. The six permutations in correct order are:

ab bc cd
ab cd bc
bc ab cd
bc cd ab
cd ab bc
cd bc ab
Note: There may be two or more of the same string as elements of .
## For example, s=[ab,bc,cd]. Only one instance of a permutation where all elements match should be printed. In other words, if s[0]==s[1], then print either s[0]  or s[1] but not both.

A three element array having three distinct elements has six permutations as shown above. In this case, there are three matching pairs of permutations where ab and ba are switched. We only print the three visibly unique permutations:

ab ab bc
ab bc ab
bc ab ab
## Input Format

The first line of each test file contains a single integer , the length of the string array .

Each of the next  lines contains a string .

Constraints

 contains only lowercase English letters.
Output Format

Print each permutation as a list of space-separated strings on a single line.

## Sample Input 0

2
ab
cd
## Sample Output 0

ab cd
cd ab
## Sample Input 1

3
a
bc
bc
## Sample Output 1

a bc bc
bc a bc
bc bc a



AIM: 
To write a program to print the sum and difference of the given two integers . 
 
# ALGORITHM: 
1. Start. 
2. Define a variables. 
3. Write a program to print the sum and difference of the integers.. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End. 
 
# PROGRAM: 
```
#include <stdio.h> 
 
int main() { 
    int a, b; 
    int sum, difference; 
 
    // Input two numbers 
    printf("Enter two 
integers: "); 
    scanf("%d %d", &a, 
&b); 
 
    // Calculate sum and 
difference 
    sum = a + b; 
    difference = a - b; 
 
    // Print the results 
    printf("Sum = 
%d\n", sum); 
    printf("Difference = 
%d\n", difference); 
 
    return 0; 
} 
```
# OUTPUT: 
![image](https://github.com/user-attachments/assets/4511855a-3ad1-4b4f-9a92-b30e9f041206)

# RESULT: 
Thus, the program is executed and verified successfully.

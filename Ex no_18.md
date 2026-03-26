# EX 18 C program to find frequency of a character in the given input.

## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
Start. Define the required variable. Write program to find frequency of a character. Read the value using scanf. Ask the user to make an input. Print out the answer. End

## Program:
```
/*
C program to find frequency of a character in the given input.
#include<stdio.h> 
#include<string.h> 
int main()
{
int i,count=0,len;
char str[100],val[100]; 
scanf("%s %s",str,val); 
len=strlen(str); 
for(i=0;i<len;i++){
if(str[i]==val[0]) 
count++;
}printf("%d",count);}
Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004 
*/
```

## Output:

<img width="278" height="296" alt="image" src="https://github.com/user-attachments/assets/17a9a59a-8fb7-4c2d-9982-5d44ad3d2a88" />


## Result:
Thus the program was executed and the output was verified successfully.

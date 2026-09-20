# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start.

2.Define the required variable.

3.Write program to find frequency of a character.

4.Read the value using scanf.

5.Ask the user to make an input.

6.Print out the answer.

7.End  

## Program:
```
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
```

## Output:
<img width="278" height="296" alt="image" src="https://github.com/user-attachments/assets/7211cb57-c673-456d-b642-57b9fe525aae" />

## Result:
Thus the program was executed and the output was verified successfully.

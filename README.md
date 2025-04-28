# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
~~~
#include <stdio.h>

int main() {
    int num = 44;
    int shift = 3;
    int result;

    result = num << shift;

    printf("Left shift of %d by %d positions is: %d\n", num, shift, result);

    return 0;
}
~~~

## OUTPUT

![image](https://github.com/user-attachments/assets/4a34f073-ec31-4928-bf40-5dfd11877638)

## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
~~~
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if(a==b)
    {
        printf("X is equal to Y");
    }
    else
    {
        printf("X is NOT equal to Y");
    }
    return 0;
}
~~~
## OUTPUT

![437893460-91b7b5ea-5d03-4245-a2a5-870fce2b4c52](https://github.com/user-attachments/assets/9f19b03a-5396-4e95-97f0-1f81ee1e631d)

           
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
~~~
#include<stdio.h>
#include<ctype.h>
int main()
{
    char str[100];
    scanf("%s",str);
    for(int i=0;str[i] != '\0';i++)
    {
        str[i] = tolower(str[i]);
    }
    printf("Lower case String is:%s",str);
    return 0;
}
~~~
## OUTPUT

![437893761-52a2eb2f-e4bf-465a-8b2c-67e070c52229](https://github.com/user-attachments/assets/6981834a-576d-4b4c-b6c3-6107d68fec3c)


## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
~~~
#include<stdio.h>
int main()
{
    char a[100];
    int l=0;
    fgets(a,sizeof(a),stdin);
    while(a[l]!='\0')
    {
        l++;
    }
    printf("%d",l-1);
    return 0;
}
~~~
## OUTPUT

![437894238-84b3385e-83a0-447e-a822-1139f2a28ae2](https://github.com/user-attachments/assets/1dd5621c-8bca-4aa9-ac8d-aef1fa480378)

## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
~~~
#include<stdio.h>
#include<string.h>
int main()
{
    char str[10];
    char srt[10];
    scanf("%s",str);
    scanf("%s",srt);
    int s = strcmp(str,srt);
    if(s==0)
    {
        printf("strings are same");
    }
    else
    {
        printf("strings are not same");
    }
    return 0;
}
~~~
## OUTPUT
 
![437896644-7f0c8569-9cd9-444e-a087-bbab127da8bc](https://github.com/user-attachments/assets/21d38762-0090-4525-be5f-a3b15f9b0f85)


## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.


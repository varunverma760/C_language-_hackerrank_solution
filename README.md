# C_language-_hackerrank_solution
c program hackerrank solution
     
     
     
   ***PLAYING WITH CHARACTERS**
     
  
  
  
  OBJECTIVE
  
 
 This challenge will help you to learn how to take a character, a string and a sentence as input in C.


To take a single character ch as input, you can use scanf("%c", &ch ); and printf("%c", ch) writes a character specified by the argument char to stdout.

  
  
  char ch;
  scanf("%c",&ch);
  printf("%c",ch);

 
 
 
 Input
 
 
 
 You have to print the character , ch, in the first line  . Then print  in next line. In the last line print the sentence,sen .




Input format




First, take a character, ch as input.
Then take the string, s as input.
Lastly, take the sentence sen as input.




Output

Print three lines of output. The first line prints the character,ch .
The second line prints the string,s .
The third line prints the sentence,sen .









***FUNCTIONS IN C**





  
OBJECTIVE





In this challenge, you will learn simple usage of functions in C. Functions are a bunch of statements glued together. A function is provided with zero or more arguments, and it executes the statements on it. Based on the return type, it either returns nothing (void) or something.

A sample syntax -




return_type function_name(arg1,arg2,arg3,....)
{



......



....



....


[if return_type is non-void]
           
           
           return something of type " return_type";
         
}


for example, a function to read four variables and return the sum of them can be written as 


int sum_of_four(int a, intb,int c,int d)
{


int sum =0;

sum+= a;

sum+= b;

sum+= c;

sum+= d;

return 0;



}




TASK



You have to write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.



INPUT FORMAT


Input contain four integer -a,b,c,d one in each line 


OUTPUT FORMAT

Print the greatest of the four integer


Note:- I/O will be automatically handled

Sample Input 0

3
4
5
6

Sample Output
6



***POINTERS IN C**


OBJECTIVE


In this challenge, you will learn to implement the basic functionalities of pointers in C. A pointer in C is a way to share a memory address among different contexts (primarily functions). They are primarily used whenever a function needs to modify the content of a variable, of which it doesn't have ownership.



void increment(int *v) {
        (*v)++; 
    }
      	int main() {
        int a;
        scanf("%d", &a);
        increment(&a);
        printf("%d", a);
    	return 0;      
    }     





***TASK**



You have to complete the function void update(int *a,int *b), which reads two integers as argument, and sets a with the sum of them b, and  with the absolute difference of them.



***Input format**

The input will contain two integers,a  and b, separated by a newline.


***Output format**

You have to print the updated value of  a and b , on two different lines.

Note: Input/ouput will be automatically handled. You only have to complete the function described in the 'task' section.


***Sample Input**

4




5



***Sample Output**

9 

1






**Sum and Difference of two number**




OBJECTIVE




The fundamental data types in c are int, float and char. Today, we're discussing int and float data types.

The printf() function prints the given statement to the console. The syntax is printf("format string",argument_list);. In the function, if we are using an integer, character, string or float as argument, then in the format string we have to write %d (integer), %c (character), %s (string), %f (float) respectively.

The scanf() function reads the input data from the console. The syntax is scanf("format string",argument_list);. For ex: The scanf("%d",&number) statement reads integer number from the console and stores the given value in variable number .

To input two integers separated by a space on a single line, the command is scanf("%d %d", &n, &m), where  n and m are the two integers.


**Task**



Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:

1 . Declare 4 variables: two of type int and two of type float.

2. Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your  variables.

3. Use the + and - operator to perform the following operations:
Print the sum and difference of two int variable on a new line.
Print the sum and difference of two float variable rounded to one decimal place on a new line.

Input Format


The first line contains two integers.



The second line contains two floating point numbers.



Output Format



Print the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float



Sample Input


10.     4


4.0.    2.0




Sample Output



14.     6 



6.0     2.0


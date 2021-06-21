# hello-world
A simple calculator

#include <cs50.h>

#include <stdio.h>

int main(void)
{
    
//Asks the question forever
while(true){

float x=get_float("Gimme a number ");

char op = get_char("/ or x or + or -  ");

float y=get_float("Gimme another number ");

//Multiplies the 2 numbers
if(op=='*'){
  
    printf("%f\n",x*y);}

else if(op=='/'){

    printf("%f\n",x/y);}

else if(op=='+'){

    printf("%f\n",x+y);}

else if(op=='-'){
    
    printf("%f\n",x+y);}

}

}

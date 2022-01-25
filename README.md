#include <stdio.h>
int main()
{
    int age=0;
    printf("Enter Your age= ");
    scanf("%d",&age);
    
if(age<18)
{
    printf("You can't Vote:(\n");
    
    //nested conditions
    if(age==17)  
    {
        printf("Try next Year to vote!!");
    }
    else
    {
        printf("You have Several Years to Vote!!");
    }   
}
   
else if(age>=18 && age<25) 
    {
        printf("You are a minor Voter.. You can VOTE!!!");
    }
    
    
else
    {
       printf("You Can VOTE!!"); 
    }
    return 0;
}

# Ds17207970199157498490915991953691

#include<studio.h>
#include<process.h>
#define stack_size 5
int s[5],top=-1,item;
void push()
{
if(top == stack_size-1)
{
printf("stack Overflow\n");
return;
}
top=top+1;
s[top]=item;
}
void pop()
{
int item_deleted;
if(top==-1)
{
printf("Stack Underflow\n");
return;
}
void display()
{
int i;
if(top==-1)
{
printf("stack is empty \n");
return;
}
printf("CONTENTS OF THE STACK IS\n");
for(i=top;i>=0;i--)
print("%d\n",s[i]);
}
int main()
{
int ch;
for(;;)
{
printf("1.PUSH 2.POP 3.DISPLAY 4.EXIT\n");
print(" Enter CHOICE\n");
scanf("%d",&ch);
switch(ch)
{
case 1:printf("Enter the element to be pushed \n");
scanf("%d",&item);
push():
break;
case 2:pop();
       break;
case 3:display();
       break;
default: exit(0);
}
}
}

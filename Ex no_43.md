# EX 43 WRITE A FUNCTION TO DISPLAY QUEUE ELEMENTS USING ARRAY
## AIM:
To Write a function to display queue elements using array.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a function to display queue elements using array.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End.

## Program:
```
float queue[50];
int rear=-1,front=-1,i;
void display()
{
if(front==-1||front>rear)
printf("No elements to display\n");
else
{
for(i=front;i<=rear;i++)
printf("%.1f\n",queue[i]);
}
}
void display()
{
if(front==-1||front>rear)
{
printf("No elements to display\n");
else
{
for(i=front;i<=rear;i++)
```

## Output:

![image](https://github.com/user-attachments/assets/71cb92bb-6f93-4504-acd0-908f429965e1)


## Result:
Thus the program was executed and the output was verified successfully.

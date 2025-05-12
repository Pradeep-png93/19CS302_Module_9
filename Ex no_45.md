# EX 45 WRITE A FUNCTIONS TO PERFORM ENQUEUE AND DISPLAY ELEMENTS IN QUEUE USING ARRAY
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a functions to traverse the linked list and display it in the following format.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End

## Program:
```
char queue[50];
int size=10,front,rear,i;
void enqueue(char data)
{
if(rear<size)
{
if(front==-1)
{
front=0;
}
rear=rear+1;
queue[rear]=data;
}
{
printf("%c\n",queue[i]);
}
}
void dequeue()
{
if(front==-1||front>rear)
{
printf("Queue Underflow\n");
}
else
{
front=front+1;
}
}
void display()
{
for(i=front;i<=rear;i++)
printf(“%c “,queue[i]);
}

```

## Output:

![image](https://github.com/user-attachments/assets/2b441216-370f-440e-97b4-1652ae1922be)


## Result:
Thus the program was executed and the output was verified successfully.

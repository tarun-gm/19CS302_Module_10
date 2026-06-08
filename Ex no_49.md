
# EX 49 C function to search an element in the double linked list.
## DATE: 
## AIM:
To write a C function to search an element in the double linked list.

## Algorithm:
1. Start. 
2. Define a variables. 
3. Write a function to search an element in the double linked list.. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End   

## Program:
```c program
struct Node 
{ 
struct Node *prev; 
struct Node *next; 
int data; 
}*head; 
 
void search(int data) 
{ 
struct Node *temp; 
int item=data,i=0,flag; 
temp=head; 
if(temp==NULL) 
{ 
printf("Empty list\n"); 
} 
else{ 
while(temp!=NULL) 
{ 
if(temp->data == item) 
{ 
 
 SAVEETHA ENGINEERING COLLEGE  
printf("item %d found at location %d",item,i+1); 
flag=0; 
} 
i++; 
temp=temp->next; 
} 
if(flag!=0) 
{ 
printf("Item not found\n"); 
} 
}
```

## Output:

![Screenshot 2025-05-07 224921](https://github.com/user-attachments/assets/45caff34-3faa-42bf-a98a-295918b4e877)


## Result:
Thus the program was executed and the output was verified successfully.

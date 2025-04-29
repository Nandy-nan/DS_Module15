# Ex14 Heap Tree
## DATE:
## AIM:
To write a C function to delete an element in a Heap Tree.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to delete an element in a Heap Tree
Developed by: nandhana r
RegisterNumber:  212223040124
*/

void deleteRoot(int array[], int num) 
{ 
int i; 
for(i=0;i<size;i++) 
{ 
if(num==array[i]) 
{ 
break; 
} 
} 
swap(&array[i],&array[size-1]); 
size-=1; 
for(i=size/2-1;i>=0;i--) 
{ 
heapify(array,size,i); 
} 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/5cb3b03e-3d76-467b-a7cb-e798854f8929)




## Result:
Thus, the function to delete an element in a Heap Tree is implemented successfully.

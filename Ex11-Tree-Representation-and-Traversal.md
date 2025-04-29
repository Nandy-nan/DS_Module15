# Ex11 Tree Representation and Traversal
## DATE:
## AIM:
To write a C function to perform post order traversal of a binary tree.

## Algorithm

1 Start the program.
2 Include required libraries.
3 Create a structure for storing the nodes.
4 Define a function for post order traversal of a binary tree.
5 End the program.

## Program:
```
/*
Program to perform post order traversal of a binary tree.
Developed by: Nandhana R
RegisterNumber: 212223040124 
*/

#include <stdio.h>
#include <stdlib.h>
struct node {
    
    int data;
    struct node *left;
    struct node *right;
  
};
void postOrder( struct node *root) {
    if(root==NULL)
    return;
    else
    {
        postOrder(root->left);
        postOrder(root->right);
        printf("%d ",root->data);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/26f4347d-d80a-49f9-aeb8-1f311533c8a5)




## Result:
Thus, the function to perform post order traversal of a binary tree is implemented successfully

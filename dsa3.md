# Binary Tree 
- Full vs complete vs perfect binary trees










## Practicals 
- implementation - node with value and two pointers left and right , binary tree with root pointer 
- insert a node 
    - create a node with the given value 
    - check root exists if not set the new node as the root 
    - create another function to recursively search and insert the node 
    - in the new function check the value is less or greater than the node value 
    - in each condition if the right or left node is empty insert the new node therr 
    - else recursively call the second function passing left or right node as an argument
- delete a node 
    - create a function with node as an parameter 
    - if the node doesnt exits return null 
    - if the node exists check the value of the node is equals to the searched value if true return the node itsels 
    - check if the searched value is less than the given node or greater thatn the node and recursively call the newely created search function on the left or right pointer accordingly 

- InOrder Traversal
    - create traversal function with parameters node with root as default value and a result with default value  as an array 
    - check if the node exists and when it exists recursively call the function again with left as an argument then push the root value to the result and the n recall the function with right as an argumenent 
- PreOrder Traversal
    - create traversal function with parameters node with root as default value and a result with default value  as an array 
    - check if the node exists and when it exists push the root value to the resul then trecursively call the function again with left as an argument then recall the function with right as an argumenent 
- PostOrder Traversal
    - create traversal function with parameters node with root as default value and a result with default value  as an array 
    - check if the node exists and when it exists trecursively call the function again with left as an argument then recall the function with right as an argumenent then  push the root value to the resul   
    
- levelOrder Traversal 
    - create an array for result and queu with only value as the root of the tree 
    - loop until the queue is empty and inside the loop 
        - set levelsize as the current queue length and also initailise an empty array to hold the levelNodes 
        - loop through from 0 to the levelsize 
            - unshift from the queue and push the unshifted value to the levelnodes 
            - push the left and right nodes to the queue 
        - push the levelnodes to the result

- Get minimum depth 
    - if there is no root return 0 
    - if there is no left then 1+ minimum depth of the right node and if there is no right then 1+ minimum depth of the left node 
    - else minimum of minimum depth of left node and right node 
- Get Maximum Depth 
    - if there is no node return 0 
    - return 1+ maximum of depth of left and right childs



# Graph 

## Graph using adjacency list 
- implementation - adjancncy list which is an object 
- add a new node - chek if the node is in adjancency list else add it  to the list with value as an empty set 
- add edge given two nodes  
    - check if the two nodes existing else add the node to the adjacency list 
    - add the second node to first nodes sets and add the first node to second node's set
- check if there is an edge between two nodes 
    - check the adjacency set of first node contains second and adjacency set of second node contains the first 
- remove edge between two nodes 
    - delete the first node from adjacency set of first node and viseversa 
- remove node from the graph 
    - check if the node is already exists 
    - loop through the adjacency list and remove all the edges connected to the node 
    - remove the node from the adjacency list 

- Breadth first search 
    - function with argument start 
    - check if the start is in the adjacency list else terminate 
    - create an queue with start in it and a visited set 
    - run a loop until the queue is non empty 
        - dequeu the element from the queue 
        - check the element is in visited else log and add it to the visited sset
            - loop through the dequeued nodes adjacency set if the element is not in the visited set add it to the queue

- Depth first search 
    - function with argument start 
    - check if the start is in the adjacency list else terminate 
    - create an stack with start in it and a visited set 
    - run a loop until the queue is non empty 
        - pop the element from the queue 
        - check the element is in visited else log and add it to the visited sset
            - loop through the pop nodes adjacency set if the element is not in the visited set add it to the queue

- display the graph 
    - loop through the adjacency list and print all the node and its adjacency 




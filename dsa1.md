

# Data Structure 
## Linear vs Non Linear Data Structures
linear - elemenets are arranged sequentially for easier traversal 
## Static vs Dynamic Data Structures 

static - fixed size and memory allocation at compile time 
## Abstract Data Types 
only provides the interface to which a DS must adhere to 

# Memory Management 
## Bit vs Byte 
## Stack and Heap Memory 
## Dynamic vs Static Memory Allocation
static means allocation during compile time ,dynamic occurs at runtime 
## Virtual Memory 
## Memory leak and Heap Overflow 
memory leaks occurrrs when apps retain referece to objects that are no longer needed 
### How to prevent Memory leak 
remove event listeners properly , clear larges state objects when scope ends , monitor memory ussage , 
## Garbage Collection 


# Analysis of Algorithms 
## Order Of Growth 
## Asymptotic Analysis 
### Time and Space Complexities 
### Worst , best and average class analysis 
## Asymptotic Notations 
### Big O vs Omega vs Theta notattions 
#### Properties of Big O 
### Time vs space complexity 
## Inplace algorithms 
operates on input data without requiring additional memory space 

# Recursion 
technique to solve big problems by breaking into smaller and similar problems , call itself directly or indirectly in itself 
## Disadvantages
more space requirement , difficult to understand and debug 
## Advantages 
clean and simpler code , efficient for non liner ds operations 
## tail recursion 
recursive call  is the last operation in the function 

# Arrays
DS where elements are allocated in contiguos memory 
## Static vs Dynamic Arrays 
## Multidimensional vs Jagged Array 
## Homogenous vs Heterogenous Arrays 
## Array Vs List 
## Complexities 
traversal n , access 1 , search n , remove/insert end 1 , remove/insert start n

# String 
## Mutable vs Immutable Strings 
## UTF-8 , ASCII vs unicode 

# Linked List 
## Singly vs doubly vs circular linked lists 
### Applications of ll  
applications - , implement other ds , dynamic memory allocation in os , memory management , process scheduling , list of songs in music player , image viewer , implementation of queu 
### advantages of ll 
efficient insertion and deletion 
### disadvantages of ll 
slow access time , more complex and high overhead , cache inefficient 
### Advantages of Doubly ll 
Efficient traversal to both directions , efficient insertion and deletion 
### Advantages of circular linked list 
better memory utilization , traversal can start from any node 
# Search Algorithms 
## Linear Search 
sequential checking each element until it find sthe target element or reaches the end 
O(n)

## Binary Search 
repeatedly divide the sorted array and search in each half O(log n)

----------------------------
# Sorting Algorithms
## Terms
### Inplace Sorting
operates directly on the input data without relying on additional memory 
### Internal Sorting 
utilizes only the main memory 
### External sorting 
utilizes external storage like hard drives 
### Stable sorting 
maintains relative order of elements with equal keys 
### Hybrid sorting 
use of multiple algorithms for sorting 

## Selection sort
repeatedly select the smallest element from the unsorted part - O(n^2)- not stable - inplace 
adv - limited memory requirement  
## Bubble sort
repeatedly compares adjacent elements and swap them - O(n^2) - stable - inplace 
adv - limited memory requirement , stable 

## Insertion Sort 
iteratively insert each element of unsorted  part to the sorted part - O(n^2) - stable - inplace 
adv - better best case time complexity ,  limited memory reqirement , stable 

## Quick Sort 

## Merge Sort 


# Stack 

# Queue 

# Hash Map and Hash Set 


----------------------------




dynamic programming 
greedy algorithm 
unicode ascii utf8 




paging and segmentation


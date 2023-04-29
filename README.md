Emma Magyarics

# CS 33211
## Operating Systems
## Programming Assignment 2

### Description of Assignment
Topic: Banker’s Algorithm for deadlock avoidance

Considering a system with five processes P0 through P4 and three resources of type A, B, C. Resource type A has 10 instances, B has 5 instances and type C has 7 instances. Suppose at time t0 following snapshot of the system has been taken:
![image](https://user-images.githubusercontent.com/117095232/235279870-641db0fd-d672-4104-b8ae-f166f702f162.png)
Implement the Banker’s algorithm to answer the following question： Is the system in a safe state? If Yes, then what is the safe sequence?

### My code

I commented throughout my code how it works but here's a brief summary. I start by setting the number of processes and resources. Then I create a function for calculating the need matrix and a function to check if the system is in a safe state or not. If it is not in a safe state then it outputs a message that it's not, if it is then it outputs a message that it is and the safe sequence. Then in the main function, it initializes the processes and matrices, opens the input file and loops through the first line which is the available. Then it loops through the next 5 lines for the allocation matrix and then 5 more lines for the max matrix. Finally, it runs the isSafe function for checking if it is in a safe state or not and the program ends. When running the system given to us, my program returns that it is in a safe state and the safe sequence is 1 3 4 0 2.

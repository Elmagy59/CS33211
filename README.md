Emma Magyarics

# CS 33211
## Operating Systems
## Programming Assignment 1

### Description of Assignment
Topic: Producer-Consumer Problem

The producer generates items and puts items onto the table. The consumer will pick up items. The table can only hold two items at the same time. When the table is complete, the producer will wait. When there are no items, the consumer will wait. We use semaphores to synchronize producer and consumer.  Mutual exclusion should be considered. We use threads in the producer program and consumer program. Shared memory is used for the “table”.

### My code
My code doesn't work quite right but I cannot figure out how to fix it. Everything compiles and runs without errors but the output isn't doing what it is supposed to do. The producer is supposed to generate two numbers for the table and then wait. Then the consumer takes those numbers and waits until there are no items. This back and forth is supposed to loop 5 times in my code but it doesn't loop properly. 

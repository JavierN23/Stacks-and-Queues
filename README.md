# Stacks-and-Queues
Question 1:

![Stacks and Queues drawio (2)](https://github.com/user-attachments/assets/5cbc64a1-a3da-479b-a970-26ca1c99e3f5)

Question 2:

![Stacks and Queues Q2 drawio](https://github.com/user-attachments/assets/ef567747-bb93-4f05-86fb-88aa56b581fa)

Question 3: Rewrite Enqueue and Dequeue to detect Underflow and Overflow:

    Enqueue(Q,x) {
    if (Q[Q.tail] == Null) {
    Q[Q.tail]= x;
    if (Q.tail == Q.length) {
    Q.tail = 1
    } else {
    Q.tail = Q.tail + 1
    }
    } else {
    return "Overflow"
    }
    }


    Dqueue(Q) {  
    if (Q[Q.head! = Null) {
    x = Q[Q.head]
    if (Q.head == Q.length) {
    Q.head = 1
    } else {
    Q.head = Q.head+1
    }
    return x
    } else {
    return "Underflow"
    }
    }

Question 4 A stack allows insertion and deletion of elements at only end, and a queue allows insertion at one end and deletion at the other end, 
a deque (double-ended queue) allows insertion and deletion at both ends. Write four O(1)-time procedures to insert elements into and delete elements from both ends of a deque implemented by an array. Code is not required. :

  The four O(1)-time procedures are: InsertFront, InsertRear, DeleteFront, DeleteRear.

https://youtu.be/SnU7L3396Q8


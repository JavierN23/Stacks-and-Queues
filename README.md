# Stacks-and-Queues
Question 1:
![Stacks and Queues drawio](https://github.com/user-attachments/assets/ed41a701-d927-4bcf-9127-27638cae2407)

Question 2:
![Stacks and Queues Q2 drawio](https://github.com/user-attachments/assets/ef567747-bb93-4f05-86fb-88aa56b581fa)

Question 3 Rewrite Enqueue and Dequeue to detect Underflow and Overflow:
Enqueue(Q,x) {
  if (Q[Q.tail] == Null)
  Q[Q.tail]= x;
  if (Q.tail == Q.length)
  Q.tail = 1
  else
  Q.tail = Q.tail + 1
  else
  "Overflow"
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

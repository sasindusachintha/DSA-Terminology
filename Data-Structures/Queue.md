# Queue

## Definition
A queue is linear data structure and Abstract Data Type that stores elements in First-In-First-Out order (FIFO) .

---

## Key Characteristics
- Follows FIFO order.
- Insertion happens at the rear.
- Deletion happens at the front.
- Can be imlpemented using array or linked list.

---

## Types of Queues
- Simple Queue
- Circular Queue
- Priority Queue
- Deque

---

## Basic Operations
- Enqueue(x) -> (insert element x at the end)
- Dequeue   ->  (delete element from the front)
- Front/ peek -> (view the front element)
- Rear    ->    (peek last element)
- isEmpty
- isFull   ->   (for array implementation)
- poll    ->    (remove and return the first elemenet of the queue)
- Size    ->    (returns total number of elements in the queue)
- Clear   ->    (removes all elements from the queue)
- Display  ->   (Prints all elements from front to rear) -> Traerse

---

## Time Complexity
- Enqueue O(1)
- Dequeu  O(1)
- Peek    O(1)
- Search  O(n)

---

## Advantages
- Efficient data handling.
- Maintains order of elements.
- Useful in scheduling tasks.

---

## Disadvantages
- Limited access
- Overflow and underflow issues
- Fixed size in array implementation

---

## Real World Applications
- CPU scheduling
- Priner queue
- Breadth First Search (BFS)
- Customer service systems

---

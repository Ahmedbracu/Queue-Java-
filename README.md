### Queue Data Structure in Java

This project demonstrates a **Queue data structure** implemented using a **linked list** in Java. The queue supports basic operations such as:

✅ **Enqueue** (Add an element to the rear)
✅ **Dequeue** (Remove and return the front element)
✅ **Front** (View the front element without removing it)
✅ **IsEmpty** (Check if the queue is empty)
✅ **Display** (Print all elements in the queue)

---

## 🚀 Features
- Implemented using a **singly linked list**.
- **No fixed size limit** (dynamic memory allocation).
- **Efficient operations** for enqueue and dequeue.
- **Fully documented** with comments.

---

## 📜 Code Overview
The **Queue class** uses a linked list-based approach where each **Node** contains:

- **data**: Stores the integer value.
- **next**: Points to the next node in the queue.

The **Node class** represents each element in the queue.

---

## 🛠 Methods

1️⃣ **isEmpty()**
   - Checks if the queue is empty.

2️⃣ **enqueue(int data)**
   - Adds a new element to the **rear** of the queue.

3️⃣ **dequeue()**
   - Removes and returns the **front** element.
   - If the queue is empty, it prints "Queue is empty!".

4️⃣ **front()**
   - Returns the **front** element without removing it.
   - If the queue is empty, it prints "Queue is empty!".

5️⃣ **display()**
   - Prints all queue elements in order.

---

## 📌 Example Usage
```java
Queue queue = new Queue();

queue.enqueue(10);
queue.enqueue(20);
queue.enqueue(30);

System.out.println("Original Queue:");
queue.display();

queue.dequeue();
System.out.println("After Dequeue:");
queue.display();

System.out.println("Front element: " + queue.front());
System.out.println("Is queue empty? " + queue.isEmpty());
```

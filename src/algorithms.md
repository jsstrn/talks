---
marp: true
paginate: true
theme: default

header: "Data structures"
footer: "© Jesstern Rays"
---

# Data structures and algorithms

Jesstern Rays, Software Engineer @ ThoughtWorks

---

# Write a program to find a number in an unsorted list?

In an unsorted list, you must search through every single element in the list.

---

# Linear search

---

# Write a program to find a number in a sorted list?

In a sorted list, you can optimize your program and reduce the number of operations it makes.

---

# Binary search

Locate the middle element and ask one of three questions

1. Does this element match the one you're looking for?
1. If yes, then you've found the element. Job done!
1. If no, is the number you're looking for higher or lower?
1. Rinse and repeat

---

# Analyzing algorithms

---

# Arrays

- Data is stored contiguously (next to each other) in memory
- Makes reading data easy

---

# Linked-lists

---

# Implementing linked-list

```js
class Node {
  constructor() {
    // your code here
  }
}

class LinkedList {
  constructor() {
    // your code here
  }
}
```

[Solution](https://github.com/jsstrn/dsa/blob/master/data-structures/linked-list/linkedList.js)

---

# Queues

- First in first out (Fifo)
- Resembles a queue for bubble tea
- Used in printers to queue jobs

---

# Question

Q: Should we implement it using an array or a linked-list? Why?

---

# Comparing operations between linked-list and array

| Operation        | Linked-list | Array |
| ---------------- | ----------- | ----- |
| Enqueue (insert) | O(1)        | O(n)  |
| Dequeue (delete) | O(1)        | O(n)  |

---

# Implementing queue

```js
class Queue extends LinkedList {
  constructor() {
    super();
    // your code here
  }
}
```

[Solution](https://github.com/jsstrn/dsa/blob/master/data-structures/queue/queue.js)

---

# Stacks

- Last in first out (Lifo)
- Resembles a stack of plates
- Used in a programs callstack

---

# Question

Q: Should we implement it using an array or a linked-list? Why?

---

# Comparing operations between linked-list and array

| Operation     | Linked-list | Array |
| ------------- | ----------- | ----- |
| Push (insert) | O(1)        | O(n)  |
| Pop (delete)  | O(1)        | O(n)  |

---

# Implementing stack

```js
class Stack extends LinkedList {
  constructor() {
    super();
    // your code here
  }
}
```

[Solution](https://github.com/jsstrn/dsa/blob/master/data-structures/stack/stack.js)

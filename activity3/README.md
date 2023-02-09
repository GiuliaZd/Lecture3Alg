# Activities

## Task 1:

- Refer to the following link. Discuss how Queues based on linked lists works:
  https://www.cs.usfca.edu/~galles/visualization/QueueLL.html
  DONE in class

## Task 2:

- The following snippet is from `./src/queue.cpp` lines 8-10. What happens if `front`, `rear` and `temp` were not global variables?

```cpp
struct node *front = NULL;
struct node *rear = NULL;
struct node *temp;
```

## Task 3:

- The following snippet is from `./src/queue.cpp` lines 11-28. Discuss in groups how the code works:

```cpp
void Insert(int val)
{
    if (rear == NULL)
    {
        rear = new node;
        rear->next = NULL;
        rear->data = val;
        front = rear;
    }
    else
    {
        temp = new node;
        rear->next = temp;
        temp->data = val;
        temp->next = NULL;
        rear = temp;
    }
}
```

DONE in class

## Task 4: Individual, at home

- Discuss the various operations that can be performed on a linked list. Refer to the following link:
  https://www.softwaretestinghelp.com/linked-list/

  the answer:
  operations include:1) insertion (at the beginning of the linked list, after the given Node, at the end of the linked list); 2)deletion(Like insertion, deleting a node from a linked list also involves various positions from where the node can be deleted. We can delete the first node, last node or a random kth node from the linked list. After deletion, we need to adjust the next pointer and the other pointers in the linked list appropriately so as to keep the linked list intact); 3)count the number of Nodes

## Links

- https://cpp.sh/

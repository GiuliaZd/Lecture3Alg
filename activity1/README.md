# Activities

## Task 1

- Refer to the following link. Discuss how bubble sort works:
  https://opendsa-server.cs.vt.edu/embed/bubblesortAV
  DONE

## Task 2

- Refer to the following link. Your task is to show the behavior for one iteration of the outer for loop of Bubble Sort (Try at least 3 cases).
  https://opendsa-server.cs.vt.edu/ODSA/Exercises/Sorting/BubsortPRO.html
  DONE

## Task 3

- The following snippet is from `./src/bubble.cpp` lines 16-28. Discuss in groups how the code works:

```cpp

    for (i = 0; i < 10; i++)
    {
        for (j = i + 1; j < 10; j++)
        {
            if (a[j] < a[i])
            {
                temp = a[i];
                a[i] = a[j];
                a[j] = temp;
            }
        }
        pass++;
    }
```

- The following snippet is from `./src/selection.cpp` lines 34-41. Discuss in groups how the code works:

```cpp
    for (j = i + 1; j < 10; j++)
    {
        if (myarray[j] < ele_small)
        {
            ele_small = myarray[j];
            position = j;
        }
    }
```

DONE

## Task 4: Individual, at home

- Discuss the complexity analysis of selection sort. Refer to the link below:
  https://www.softwaretestinghelp.com/selection-sort/
  the answer:
  Selection sort requires two for loops nested with each other to complete itself. One for loop steps through all the elements in the array and we find the minimum element index using another for loop which is nested inside the outer for loop.
  Therefore, the time complexity of O(n2) is mainly because of the use of two for loops. Worth noting that the selection sort technique never takes more than O(n) swaps and is beneficial when the memory write operation proves to be costly.

## Links

- https://cpp.sh/

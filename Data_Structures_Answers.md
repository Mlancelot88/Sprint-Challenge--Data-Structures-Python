Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method?
The runtime complexity is O(n).

2. What is the space complexity of your ring buffer's `append` function?
The space complexity is O(1).

3. What is the runtime complexity of your ring buffer's `get` method?
The runtime complexity of my `get` method is 0(n).

4. What is the space complexity of your ring buffer's `get` method?
The space complexity is O(1).

5. What is the runtime complexity of the provided code in `names.py`?
The runtime complexity is O(n^2). We use a nested loop which leaves n squared.

6. What is the space complexity of the provided code in `names.py`?
The space complexity is O(log n). It only save the duplicated names.

7. What is the runtime complexity of your optimized code in `names.py`?
The runtime complexity is O(log n). I choose to save time by utilizing the built-in timesort algorithm.
From there, we use Binary Search for O (log n). This allows me to dismiss half of the list at each operation if the target string is larger to the midpoint string.

8. What is the space complexity of your optimized code in `names.py`?
The space complexity is O(n). Our first list is saved once, sorted, and saved again. Next, we check for duplicates in the second list.
If a duplicate exists, we save it to the duplicates list.

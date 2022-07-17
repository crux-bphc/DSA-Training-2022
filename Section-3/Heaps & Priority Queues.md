# Heaps

A Heap is a complete binary tree-based data structure with a specific ordering property. There are two types:

- Max-Heap: The key present at any node is greater than the keys present at both of its children. The largest key is at the root node.
- Min-Heap: The key present at any node is smaller than the keys present at both of its children. The smallest key is at the root node.

Heaps are used when the highest or lowest order/priority element needs to be removed. They allow quick access to this item in O(1) time. One use of a heap is to implement a priority queue.

## Resources

* [Hackerearth](https://www.hackerearth.com/practice/notes/heaps-and-priority-queues/)
* [Programiz](https://www.programiz.com/dsa/heap-data-structure)
* [GfG (Array implementation)](https://www.geeksforgeeks.org/building-heap-from-array/)


# Priority Queues

In a priority queue, elements are assigned a priority value. They then come out of the queue based on priority value (highest priority comes first). If two elements have the same priority value, they come out in the order they were queued (regular queue property).

There are many ways to implement a priority queue, the most common and efficient method being with the use of heaps. This allows for finding the highest priority element in O(1) and insertions/deletions in O(logn). It is recommended, however, to directly use the inbuilt STL priority queue (or their counterparts in Java/Python) instead of trying to implement your own.

There are many ways you can assign priority values, but the most commonly use is to find the current min/max. You may refer to the below links for details on syntax and usage.

## Resources

* [Programiz](https://www.programiz.com/dsa/priority-queue)

### Recommended to use

- [C++](https://www.geeksforgeeks.org/priority-queue-in-cpp-stl/)
- [Java](https://www.geeksforgeeks.org/priority-queue-class-in-java-2/)
- [Python](https://www.geeksforgeeks.org/heap-queue-or-heapq-in-python/)

## Problems

* [Interviewbit - k largest elements](https://www.interviewbit.com/problems/k-largest-elements/)
* [Leetcode 703](https://leetcode.com/problems/kth-largest-element-in-a-stream/)
* [Leetcode 1046](https://leetcode.com/problems/last-stone-weight/)
* [Leetcode 1673](https://leetcode.com/problems/find-the-most-competitive-subsequence/)
* [Atcoder ABC 141D](https://atcoder.jp/contests/abc141/tasks/abc141_d)

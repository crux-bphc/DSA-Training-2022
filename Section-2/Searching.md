# Searching

Searching is a very commonly asked type of programming problem. The most naive way of searching would be to perform a linear search. However, this will have a relatively high time complexity and will not be sufficient in many cases. Here we will discuss two much faster algorithms - binary and ternary search. Binary search in particular has many very useful applications.

## Binary Search

Binary search is used to search for a value from a collection of sorted values in logarithmic time. 



The most trivial use of binary search is directly searching for the presence of a value. However, the true power of binary search comes forward when we need to use search to find the answer to a problem. This is known as discrete binary search.



Consider the below table:

| x        | 1     | 2     | 3     |...    |...    | v     | v+1   | ...   | ...   | N  |
| -------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| check(x) | false  | false  | false  | false  | false  | false  | true | true | true | true |

We can binary search over all values of X and at each step check if the current X satisfies the problem. This can be used to find the highest value of false (v) or the
lowest value of true (v+1). Similar algorithm can be used if first 'v' values are true and rest are false.

For example in [this](https://codeforces.com/contest/1201/problem/C) question, you can binary search over the range of possible values `[1,2e9]`.

### Resources

* [Basic binary seach](https://www.hackerearth.com/practice/algorithms/searching/binary-search/tutorial/)
* [Basic binary search (Video)](https://www.youtube.com/watch?v=j5uXyPJ0Pew)
* [Discrete binary search](https://oldaddr.wordpress.com/2014/06/28/binary-search-the-answer/)
* [Both](https://www.topcoder.com/thrive/articles/Binary%20Search)

### Problems

* [Codeforces 706B](https://codeforces.com/problemset/problem/706/B)
* [Codeforces 1187B](https://codeforces.com/contest/1187/problem/B)
* [Codeforces 1208B](https://codeforces.com/contest/1208/problem/B)
* [Codeforces 812C](https://codeforces.com/contest/812/problem/C)
* [Codeforces 269B](https://codeforces.com/contest/269/problem/B)
* [Codeforces 118D2](https://codeforces.com/contest/1118/problem/D2)


## Ternary Search
Ternary Seach is used in specific situations when the given function has a **U or an inverted U shape** i.e has a **distinct minimum or maximum** over a given discrete valued range.
The algorithm finds the **maxima/minima of the given function in logarithmic time**.

### Resources
* [Geeks for Geeks](https://www.geeksforgeeks.org/ternary-search/)
* [HackerEarth](https://www.hackerearth.com/practice/algorithms/searching/ternary-search/tutorial/)
* [CP algorithms](https://cp-algorithms.com/num_methods/ternary_search.html) - try reading this. Very detailed explanation.

**Note**: Ternary search may not be as important and/or common, but it is good to know. You may skip it if you wish.

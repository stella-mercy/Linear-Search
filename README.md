# Linear-Search
In this article, we will discuss the Linear Search Algorithm. Searching is the process of finding some particular element in the list. If the element is present in the list, then the process is called successful, and the process returns the location of that element; otherwise, the search is called unsuccessful.

Two popular search methods are Linear Search and Binary Search. So, here we will discuss the popular searching technique, i.e., Linear Search Algorithm.

Linear search is also called as sequential search algorithm. It is the simplest searching algorithm. In Linear search, we simply traverse the list completely and match each element of the list with the item whose location is to be found. If the match is found, then the location of the item is returned; otherwise, the algorithm returns NULL.

It is widely used to search an element from the unordered list, i.e., the list in which items are not sorted. The worst-case time complexity of linear search is O(n).

The steps used in the implementation of Linear Search are listed as follows -

First, we have to traverse the array elements using a for loop. In each iteration of for loop, compare the search element with the current array element, and - If the element matches, then return the index of the corresponding array element. If the element does not match, then move to the next element. If there is no match or the search element is not present in the given array, return -1.

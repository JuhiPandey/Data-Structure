Types of algorithms-----


1.Searching algorithms and these pop up in cases where you need to find a specific piece of data inside a larger data structure. For example, searching for a substring inside of a larger string, or maybe finding a file within a set of nested folders on a file system. 


2.Sorting algorithms are another very common type used when working with ordered sets of data. And, as you might have guessed, they take a set of data, and place it into a particular order. 


3.Computational algorithms are used to take one set of data and derive another set of data from it. And a simple example might be calculating whether a given number is a prime number or maybe computing a temperature in one scale when you already have it in another scale. 


4.And finally, there are collection algorithms, which involve manipulating or navigating among sets of data that are stored within a particular structure. And again, it's not hard to imagine some examples here, counting specific items, filtering out unwanted data, and so on..
*****************************************************************************************************************************

Common BIG-O tearms-----

1.O(1)-Constant time

The simplest example is what's called constant time, and that corresponds to a Big-O of one. And essentially that means that the operation in question doesn't depend on the number of elements in the given data set. So a good example of this is calculating whether a number is even or odd, or looking up a specific element index in an array. 

2.O(logn)-Logrithmic

Next is the order of log n which is called logarithmic time. And a typical example of this kind of operation is finding a specific value in a sorted array using a binary search. So as the number of items in the sorted array grows, it only takes a logarithmic time relationship to find any given item. 

3.O(n)-Linear

The next step up from there is linear time which corresponds to a Big-O of n, and this level of time complexity corresponds to a typical example of searching for an item in an unsorted array. So as more items are added to the array in an unsorted fashion, it takes a corresponding linear amount of time to perform a search.

4.O(nlogn)-Log Linear

After that we have order of n times log n or what's called log-linear time complexity. And some good examples of this kind of operation are some sorting algorithms like heap sort and merge sort. 

5.O(n2)-Quadratic

And then there's order of n squared, which is called quadratic time complexity, and as you've probably guessed it's not a very good level of performance, because what that means is that as the number of items in the data set increases, the time it takes to process them increases at the square of that number. So some examples of this type of operation are some of the simpler sorting algorithms like the bubble sort and the selection sort. Now this is not an exhaustive list of the various types of time complexity rankings. Believe it or not, there are actually some worse ones than the quadratic time scale. But this is a good representative list of the ones that you are likely to encounter when programming, and it's a good way of comparing the different performance levels to each other. 

## Date: Aug 18<sup>th</sup> 2020

NOTE: Base of log is always **2**

- Binary search: O(log**n**)

- Selection sort:

  - **Step 1:** Search for the minimum element and move it to the front of the array
  - **Step 2:** Shorten the array by 1 element from the start of the array
  - Repeat step 3 until reaching end of array
  - **_Time complexity_** - O(n<sup>2</sup>)

- Merge sort: Break down the entire array in smaller pieces until you reach individual pieces and sort them on the smallest levels. Then merge the arrays by comparing the smallest elements of the 2 arrays.
  - **_Time complexity_** - O(**n** \* log**n**)

* Sequencing is additive, looping is additive.
  - Running a sequence of code is additive of complexity.
  - Running a loop of code is multiplicative of complexity.

## Date: Aug 25<sup>th</sup> 2020

- Big Oh: The upper bound of an algorithm
- Big Omega: The lower bound of an algorithm
- Big Theta: The upper & lower bound of an algorithm

## Date: Oct 1<sup>st</sup> 2020
- DAGs: Directed Acyclic Graphs
  - Used for causalities
  - Use topological sort to sort a DAG
- If a node is visited in a graph when it has been explored completely [both pre and post visited] it is not a cyclic graph.
- It is a cyclic graph when it has only been pre visited but not post visited.
- Source nodes have edges going out.
- Sink nodes hace edges coming in.
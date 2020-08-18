## Date: Aug 18<sup>th</sup> 2020

NOTE: Base of log is always **2**

- Binary search: O(log**n**)

- Selection sort: 
  - **Step 1:** Search for the minimum element and move it to the front of the array
  - **Step 2:** Shorten the array by 1 element from the start of the array
  - Repeat step 3 until reaching end of array
  - ***Time complexity*** - O(n<sup>2</sup>)

- Merge sort: Break down the entire array in smaller pieces until you reach individual pieces and sort them on the smallest levels. Then merge the arrays by comparing the smallest elements of the 2 arrays.
  - ***Time complexity*** -  O(**n** * log**n**)


- Sequencing is additive, looping is additive.
  - Running a sequence of code is additive of complexity.
  - Running a loop of code is multiplicative of complexity.
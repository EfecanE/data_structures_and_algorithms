# Insertion Sort

[22,27,16,2,18,6] (Insertion Sort)

* [2,27,16,22,18,6] &#8594; [2,6,16,22,18,27] &#8594; [2,6,16,22,18,27] &#8594; [2,6,16,18,22,27] &#8594; [2,6,16,18,22,27]

* Big O Notation &#8594; n+(n-1)+(n-2)+...1 = n*(n+1)/2 = (n^2 + n)/2 = O(n^2)

### Time Complexity: 
* Worst Case = O(n^2)
* Avarage Case = O(n^2)
* Best Case = O(n)


The number 18 is an example of an average case when sorting the array.

#### Example

[7,3,5,8,2,9,4,15,6] (Insertion Sort)

* [7,3,5,8,2,9,4,15,6] &#8594; [2,3,5,8,7,9,4,15,6] &#8594; [2,3,5,8,7,9,4,15,6] &#8594; [2,3,4,8,7,9,5,15,6] &#8594; [2,3,4,5,7,9,8,15,6]
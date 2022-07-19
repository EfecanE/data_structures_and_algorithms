# Merge Sort

[16,21,11,8,12,22] (Merge Sort)

* [16,21,11] + [8,12,22]
* [16] + [21,11] &nbsp;&nbsp;&nbsp; [8] + [12,22]
* [16] &nbsp;&nbsp; [21] + [11] &nbsp;&nbsp;&nbsp; [8] &nbsp;&nbsp; [12] + [22]

* [16] &nbsp;&nbsp; [11,21] &nbsp;&nbsp;&nbsp; [8] &nbsp; [12,22]

* [11,16,21] &nbsp;&nbsp;&nbsp; [8,12,22]

* [8,11,12,16,21,22]

### Big O Notation
O(n*log(n))
# Merge-Sort-Project
Veri Yapıları ve Algoritmalar bölümünde patika.dev tarafından verilen [Marge Sort Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)
### [16,21,11,8,12,22]

1. Write the stages of the above array according to the sort type. 



*Split the selected array to left and right subarrays*   [16,21,11,8,12,22]

 *                                                  [16,21,11] - [8,12,22]
 
 *                                              [16] - [21,11] - [8] - [12,22]
 
 *                                          [16] - [21] - [11] - [8] - [12] - [22]
 
*Combine them into the same manner in a sorted*  [16] - [21,11] - [8] - [12,22]

*                                                   [11,16,21] - [8,12,22]
 
*                                                      [8,11,12,16,21,22]


2. Write the Big-O notation.

> O(nlogn)

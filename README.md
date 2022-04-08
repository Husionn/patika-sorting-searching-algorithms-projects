# SORTING ve SEARCHING PROJELERI
*****
## Insertion Sorting
*****

Task: [Original page](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)
```
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
***
Solution:
1) ```
    [22,27,16,2,18,6] -Original
    [22,27,16,2,18,6] -22 is smaller than 27
    [16,22,27,2,18,6]
    [2,16,22,27,18,6]
    [2,16,18,22,27,6]
    [2,6,16,18,22,27]
    ```

2) ```
    Best Case: O(n)¹²³⁴⁵⁶⁷⁸⁹⁰
    Average & Worst Case: O(n²)
    ```

3) ```
    Average Case.
    ```

4) ```
    [7,3,5,8,2,9,4,15,6] -Original
    [3,7,5,8,2,9,4,15,6] 1
    [3,5,7,8,2,9,4,15,6] 2
    [3,5,7,8,2,9,4,15,6] 3
    [2,3,5,7,8,9,4,15,6] 4
    ```
*****
*****
*****
## Merge Sorting
***
Task: [Original Page](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)
```
Proje 2
[16,21,11,8,12,22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
```
*****
Solution:
1) ```
              [16,21,11,8,12,22] -Original
      [16,21,11]              [8,12,22]
    [16]    [21,11]          [8]    [12,22]
    [16]   [21] [11]         [8]   [12] [22]
    [16]    [11,21]          [8]    [12,22]
      [11,16,21]              [8,12,22]
              [8,11,12,16,21,22]
    ```

2) ```
    O(n*Logn)
    ```

***
***
***
## Binary Search Tree
***
Task: [Original Page](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)
```
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
***
Solution:
```
root 5'tir.
rootun solunda 3 bulunur.
3 ün solunda 1 bulunur. 
1 in solunda 0 bulunur.
1 in sağında 2 bulunur. 
3 ün sağında 4 bulunur.

rootun sağında 8 bulunur.
8 in solunda 7 bulunur.
7 in solunda 6 bulunur.
8 in sağında 9 bulunur.
```
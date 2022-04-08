# SORTING ve SEARCHING PROJELERI

## Insertion Sorting
*****

Task:
```
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

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


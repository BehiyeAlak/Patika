# Patika - Veri Yapıları ve Algoritmalar
## Proje 1 - Insertion Sort

### [22,27,16,2,18,6] -> Insertion Sort

**1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
```
[22, 27, 16, 2, 18, 6]
[2, 27, 16, 22, 18, 6]
[2, 6, 16, 22, 18, 27]
[2, 6, 16, 18, 22, 27]
```
**2. Big-O gösterimini yazınız.**
```
n + (n-1) + (n-2) + 1  

n.(n+1)/2   

n² +n/2  

O(n²)
```

**3. Time Complexity:**
```
Average case: O(n²) 
Worst case: O(n²)
Best case: O(n) 

[2, 6, 16, 18, 22, 27]

Average Case: 16 - 18
Worst Case: 27
Best Case: 2

```

**4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
```
Average case kapsamına girer. 
```

**5. [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

```
[7, 3, 5, 8, 2, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
```


## Proje 2 - Merge Sort


### [16, 21, 11, 8, 12, 22] -> Merge Sort

### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız:

```
        [16,21,11,8,12,22]
        
    [16,21,11]       [8,12,22]
  
  [16]  [21,11]       [8,12]  [22]

[16]  [21]  [11]       [8]  [12]  [22]
 
 [16]  [11,21]          [8,12]  [22]
   
   [11,16,21]            [8,12,22]
        
           [8,11,12,16,21,22]
```


### 2. Big-O gösterimini yazınız:

```
O(nlogn)
```


## Proje 3 - Merge Sort

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
```
Binary Search bu diziyi küçükten büyüğe sıralar: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

En küçük sayı:0
En büyük sayı:9

Ortadaki sayı: 4 ve root 4 olur.
4'ün sağında 7, solunda 3 bulunur.

Binary Search Tree aşağıdaki gibi olur: 

        4
      /   \
     3     7 
   /      /  \
  1      6    8
 / \     /     \
0   2   5       9

```


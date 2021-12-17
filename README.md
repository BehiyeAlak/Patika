# Patika - Veri Yapıları ve Algoritmalar
## Proje 1 - Insertion Sort

### [22,27,16,2,18,6] -> Insertion Sort

**1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
```
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```
**2. Big-O gösterimini yazınız.**
```
n + (n-1) + (n-2) + 1  

n.(n+1)/2   

n2+n/2  

O(n²)
```

**3. Time Complexity:**
```
Average case: O(n²) 
Worst case: O(n²)
Best case: O(n) 

[2,6,16,18,22,27]

Average Case: 16-18
Worst Case: 27
Best Case: 2

```

**4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
```
Average case kapsamına girer. 
```

**5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```


# Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. (Write the stages of the above given sequence according to the sort type.)
2. Big-O gösterimini yazınız. (Write the Big-O notation.)
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. (Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.)
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. (What case does the number 18 fall into after the array is sorted? Write.)
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. (Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.)

## 1. Sort Phases

[22, 27, 16, 2, 18, 6]

- [22, 27, 16, 2, 18, 6] 1
- [2, 6, 16, 22, 18, 27] 2 (n-1)
- [2, 6, 16, 18, 22, 27] 3 (n)


## 2. Big 0 Notation

- worst case  O(n^2)
- (0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2)

## 3. Time Complexity

- best case: O(n)
- average case: O(n^2)
- worst case: O(n^2)

## 4. Which Case Does the Number 18 Enter After the Array is Sorted?

- Average Case

## 5. [7,3,5,8,2,9,4,15,6] Insertion Sort First 4 Step

- [2,3,5,8,7,9,4,15,6] 1
- [2,3,4,8,7,9,5,15,6] 2
- [2,3,4,5,7,9,8,15,6] 3
- [2,3,4,5,6,9,8,15,7] 4

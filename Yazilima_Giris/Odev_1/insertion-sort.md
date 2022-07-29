# Patika Projeler
## İnsetion Sort 
[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
### Cevap
#### 1
[22,27,16,2,18,6]--1
[16,22,27,2,18,6]--2
[2,16,22,27,18,6]--3
[2,16,18,22,27,6]--4
[2,6,16,18,22,27]
#### 2
Big o Notation

Worst Case O(n²)
#### 3
Best Case Aradığımız Sayının Başta Olması
Avarege Case Aradığımız Sayının Ortada Olması
Worst Case Aradığımız Sayının Sonda Olması
18 sayısı avarege case kapsamında O(n²)
## Merge Sort
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
### Cevap
#### 1
                                        [16,21,11,8,12,22]
                                 [16,21,11]             [8,12,22]
                            [16] [21,11]                   [8] [12,22]
                        [16] [21] [11]                      [8] [12] [22]
                         [[16,21] [11]                     [8,12] [22]
                             [11,16,21]                   [8,12,22]
                                        [8,11,12,16,21,22]   
#### 2
Big O notation
O(logn)
## Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız
### Cevap
Root 7
5, 7'den küçük 7'nin solunda bulunur
1, 7 den küçük 7 nin solunda bulunur. 1 5'den de küçük 5'in solunda bulunur
8, 7'den büyük 7 nin solunda bulunur
3, 7 'den ve 5'den kçük ama 1'den büyük  1in sağında 
6 7'den küçük ama 5'den büyük 5'in sapında 
0 1'den küçük 1'in solunda 
9 7'den büyük 7'nin sağında 8'den de büyük 8'in de sağında bulunur
4 3'den büyük 3'ün sağında bulunur
2 3'den küçük 3'ün solunda bulunur
                                                    7
                                                  /   \
                                                5       8
                                               /  \       \
                                              1     6       9 
                                            /   \
                                           0     3
                                               /   \
                                              2      4   
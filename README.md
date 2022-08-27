Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.
3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


4- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevaplar

1- 1.asama
[22,27]ye bakılır ve sıralı olduğu görülür
1- 2.asama
[27,16]ye bakılır [16,27] olarak değiştirilir, [22,16]ye bakılır [16,22]olarak değiştirilir
yeni hali [16,22,27, ...] olur.
1- 3.asama
[27,2]ye bakılır [2,27] olarak değiştirilir, [22,2]ye bakılır [2,22]olarak değiştirilir, [16,2]ye bakılır [2,16] olarak
değiştirilir. Yeni hali [2,16,22,27, ...] olur.
1- 4.asama
[27,18]ye bakılır [18,27] olarak değiştirilir, [22,18]ye bakılır [18,22]olarak değiştirilir, 
 Yeni hali [2,16,18,22,27, ...] olur.
 1- 5.asama
[27,6]ye bakılır [6,27] olarak değiştirilir, [22,6]ye bakılır [6,22]olarak değiştirilir, [18,6]ye bakılır [6,18] olarak
değiştirilir, [16,6]ye bakılır [6,16]olarak değiştirilir. Yeni hali [2,6,16,18,22,27,] olur.

2- O(n^2)
3- Avarage Case olarak kullanilmaktadir.




4- 1.asama
[7,3]ye bakılır ve [3,7] olarak değiştirilir.
4- 2.asama
[7,5]ye bakılır ve [5,7] olarak değiştirilir.
4- 3.asama
[7,8]ye bakılır ve sıralı olduğu görülür.
4- 4.asama
[8,2]ye bakılır ve [2,8] olarak değiştirilir, [7,2]ye bakılır [2,7] olarak değiştilir,
[5,2]ye bakılır ve [2,5] olarak değiştirilir, [3,2]ye bakılır ve [2,3] olarak değiştirilir.
Yeni sıralama [2,3,5,7,8,...] olarak kaydedilir.

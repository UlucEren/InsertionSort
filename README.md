# InsertionSort

[22,27,16,2,18,6] -> Insertion Sort
1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-[2,27,16,22,18,6]
2-[2,6,16,22,18,27]
3-[2,6,16,22,18,27]  
4-[2,6,16,18,22,27]
5-[2,6,16,18,22,27] 

2.Big-O gösterimini yazınız.
O(n^2) --> n=6 --> O(36)

3.Time Complexity:

Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.
Average case: O(n^2)
Worst Case: O(n^2)
Best Case: O(n)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Worst case kapsamına girer. Çünkü dizide bulunmadığı için n tane arama işlemi gerçekleşir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Başlangıç:[7,3,5,8,2,9,4,15,6]

1. Aşama :[3,7,5,8,2,9,4,15,6]

2. Aşama :[3,5,7,8,2,9,4,15,6]

3. Aşama :[3,5,7,2,8,9,4,15,6]

4. Aşama :[3,5,2,7,8,9,4,15,6]

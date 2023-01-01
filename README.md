# patika-proje-1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
min=2 -> swap 2 and 22 -> [2, | 27, 16, 22, 18, 6]
min=6 -> swap 27 and 6 -> [2, 6, | 16, 22, 18, 27]
min=16 -> no need to swap -> [2, 6, 16, | 22, 18, 27]
min=18 -> swap 18 and 22 -> [2, 6 16 18 ,22, 27]
Big-O gösterimini yazınız.
Avarage case: O(nn)=O(n^2) Best case: O(n) Worst Case: O(nn)=O(n^2)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Dizi sıralandıktan sonra şu şekli alır:[ 2,6,16,18,22,27 ] 18 ortada olduğu için Avarage case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

7|3,5,8,2,9,4,15,6
3,7|5,8,2,9,4,15,6
3,5,7|8,2,9,4,15,6
3,5,7,8|2,9,4,15,6



# patika-proje-2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22]

[16,21,11] | [8,12,22]

[16,21][11] | [8,12][22]

[16][21][11] | [8][12][22]

[16,21][11] | [8,12][22]

[11,16,21] | [8,12,22]

	[8,11,12,16,21,22]
Big-O gösterimini yazınız.

O(nlogn)

# patika-proje-3

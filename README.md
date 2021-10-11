# Veri-Yapilari-ve-Algoritmalar-Proje
Veri Yapıları ve Algoritmalar Proje
### Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

	- [2,27,16,22,18,6]
	- [2,6,16,22,18,27]
	- [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

	n + (n-1) + (n-2) + ... + 1 = (n * (n+1) ) / 2 = (n<sup>2</sup> + n) / 2
	##### Big - O Notation : O (n<sup>2</sup>)
	
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
	- Worst Case : O (n<sup>2</sup>)
	- Average Case : O (n<sup>2</sup>)
	- Best Case : O (n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
	
		Average Case
	
	[7,3,5,8,2,9,4,15,6] dizisinin Insertion sort'a göre ilk 4 adımını yazınız.
	
	- [2,3,5,8,7,9,4,15,6]
	- [2,3,4,8,7,9,5,15,6]
	- [2,3,4,5,7,9,8,15,6]
	- [2,3,4,5,6,9,8,15,7]
	- [2,3,4,5,6,7,8,15,9]
	- [2,3,4,5,6,7,8,9,15]

### Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

![Merge Sort](https://user-images.githubusercontent.com/74915877/136799168-e31e5dc0-d433-4d21-999c-cee5d6185292.png)

2. Big-O gösterimini yazınız.

	2<sup>x</sup> = n 
	
	x = logn
	##### Big - O Notation : O(nlogn)
	
### Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

 - Root 7'dir.
 - 5, 7'nin solundadır.
 - 1, 5'in solundadır.
 - 8, 7'nin sağındadır.
 - 3, 1'in sağındadır.
 - 6, 5'in sağındadır.
 - 0, 1'in solundadır.
 - 9, 8'in sağındadır.
 - 4, 3'ün sağındadır.
 - 2, 3'ün solundadır.


![indir](https://user-images.githubusercontent.com/74915877/136794417-b43de929-04c5-4f33-8ca2-a31c852f9468.png)

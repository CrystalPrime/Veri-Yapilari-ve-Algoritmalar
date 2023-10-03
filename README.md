# Veri-Yapilari-ve-Algoritmalar


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6]
[2,22,27,16,18,6]
[2,6,22,27,16,18]
[2,6,16,18,22,27]

Big-O gösterimini yazınız.
n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2 Big-O = n^2

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
Aradığımız sayı dizinin ortasında. Average case.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]
[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]
[2,3,4,5,6,7,8,9,15]



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------



[16,21,11,8,12,22]] -> Insertion Sort

-dizi ikiye bölünür [16,21,11] ve [8,12,22]
-diziler 2 elementler ve 1 element olmak üzere yine bölünür
-2 elementli diziler 1 elementli olucak şekilde yine bölünür.
-16 ve 21 aynı kalır [16,21] ve 8 ve 12 de [8,12] şekilde
-11 ve 22 2 elementli diziler ile karşılaştırılarak 3 elementli diziler oluşturulur. [11,16,21] [8,12,22]
-Son olarak bu iki dizilerin öğeleri karşılaştırılır. 8 ile 11 sonra 12 ile 11 gibi ve [8,11,12,21.22] dizisi elde edilir.

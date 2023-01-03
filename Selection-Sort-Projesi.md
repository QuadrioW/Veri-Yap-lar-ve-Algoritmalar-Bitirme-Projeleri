# Veri-Yapıları-ve-Algoritmalar-Projeleri (www.patika.dev)
# Soru 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

# Soru 2
Big-O gösterimini yazınız.

# Soru 3
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

# Soru 4
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# ------------------------------------------------------------------------------

# Çözüm 1
Insertion Sort türünde aşamaları;

1) [22,27,16,2,18,6]
2) [22,16,27,2,18,6]
3) [16,22,27,2,18,6]
4) [16,22,2,27,18,6]
5) [16,2,22,27,18,6]
6) [2,16,22,27,18,6]
7) [2,16,22,18,27,6]
8) [2,16,18,22,27,6]
9) [2,16,18,22,6,27]
10) [2,16,18,6,22,27]
11) [2,16,6,18,22,27]
12) [2,6,16,18,22,27]

# Çözüm 2
Big-O gösterimi;
O(n^2)

# Çözüm 3
Dizi Insersiton Sort türüne göre sıralandıktan sonra 18 sayısı "Average Case" kapsamına girmektedir.
Çünkü, istenilen verilen olan "18" sayısı dizi içerisinde orta konumta yer almaktadır.

# Çözüm 4
Selection Sort türüne göre ilk 4 aşaması;
1) [2,3,5,8,7,9,4,15,6]
2) [2,3,4,8,7,9,5,15,6] (3 sayısı zaten 2. aşamada hem 2. sırada yer aldığı hem de en küçük eleman olduğu için sabit akalır ve 3. eleman olan 5 sayısına geçilir.)
3) [2,3,4,5,7,9,8,15,6]
4) [2,3,4,5,6,9,8,15,7]

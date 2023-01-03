# Veri-Yap-lar-ve-Algoritmalar-Merge-Sort-Projesi (www.patika.dev)

# Soru 1
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

# Soru 2
Big-O gösterimini yazınız.

# ------------------------------------------------------------------------------

# Çözüm 1
Merge Sort türünde gösterimi;

1) [16,21,11]  /  [8,12,22]
2) [16] - [21,11]  /  [8] - [12,22]
3) [16] - [21] - [11]  /  [8] - [12] - [22]
4) [16] - [11,21]  /  [8] - [12,22]
5) [11,16,21]  /  [8,12,22]
6) [8,11,12,16,21,22]

# Çözüm 2
Big-O gösterimi;
 O(nlogn)

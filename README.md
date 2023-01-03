# Veri-Yap-lar-ve-Algoritmalar-Binary-Search-Tree-Projesi (www.patika.dev)

# Soru 1

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# ------------------------------------------------------------------------------

# Çözüm 1
Binary Search Tree türünde aşamaları;

Root'u 4 alalım.

                    (4)                -----> Root Satırı
                   /   \                                         > "7" sayısı 4 sayısından büyük olduğu için sağına yazıldı.
                  /     \
                 /       \                                       > "5" sayısı 4 sayısından büyük olduğu için 4 sayısının sağına,
              (1)         (7)          -----> 1. Düğüm Satırı       7 sayısından küçük olduğu için 7 sayısının soluna yazıldı.
             /   \       /   \
            /     \     /     \                                  > "1" sayısı 4 sayısından küçük olduğu için 4 sayısının soluna yazıldı.
           /       \   /       \
         (0)      (3) (5)      (8)     -----> 2. Düğüm Satırı    > "8" sayısı 4 sayısından büyük olduğu için 4 sayısının sağına,
        /              \         \                                  7 sayısından da büyük olduğu için 7 sayısının da sağına yazıldı.
       /                \         \
      /                  \         \                             > "3" sayısı 4 sayısından küçük olduğu için 4 sayısının soluna,
    (2)                  (6)       (9) -----> 3. Düğüm Satırı       1 sayısından büyük olduğu için 1 sayısının sağına yazıldı.

                                                                 > "6" sayısı 4 sayısından büyük olduğu için 4 sayısının sağına,
                                                                    7 sayısından küçük olduğu için 7 sayısının soluna,
                                                                    5 sayısından büyük olduğu için 5 sayısının sağına yazıldı.

                                                                 > "0" sayısı 4 sayısından küçük olduğu için 4 sayısının soluna,
                                                                    1 sayısından da küçük olduğu için 1 sayısının da soluna yazıldı.

                                                                 > "9" sayısı 4 sayısından büyük olduğu için 4 sayısının sağına,
                                                                    7 sayısından büyük olduğu için 7 sayısının sağına,
                                                                    8 sayısından da büyü kolduğu için 8 sayısının da sağına yazıldı.

                                                                 > "2" sayısı 4 sayısından küçük olduğu için 4 sayısının soluna,
                                                                    1 sayısından büyük olduğu için 1 sayısının sağına,
                                                                    3 sayısından küçük olduğu için 3 sayısının soluna yazılarak
                                                                    3 Düğüm Satırında çözülmüştür.

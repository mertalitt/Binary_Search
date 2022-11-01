# Binary_Search
Patika.dev Binary Search Project [Patika.dev](https://www.patika.dev/tr) 
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
##### Önce kök belirlenir. Sayılar sıralı olmadıgı için soldan başlanır.
|  ROOT  |     7
##### 5 7'den küçük olduğu için sola yazılır.
|  ROOT  |     7
              / 
             5 
##### 1 hem 5'ten hem de 7'den kucuk oldugu icin en sola yazılır
|  ROOT  |     7
              / 
             5 
            /
           1 
##### 8, 1; 5 ve 7'den büyük olduğu için en sağa yazılır.
|  ROOT  |     7
              / \
             5   8 
            /
           1 
##### 3 5'ten küçük 1'den büyük olduğu icin 1'in sağına yazılır.
|  ROOT  |     7
              / \
             5   8 
            /
           1 
            \
             3
##### 6, 5'ten büyük 7'den küçük olduğu için 5'in sağına yazılır.
|  ROOT  |     7
              / \
             5   8 
            / \
           1   6
            \
             3
##### 0 en küçük olduğu icin en sola yazılır.
|  ROOT  |     7
              / \
             5   8 
            / \
           1   6
          / \
         0   3
##### 9 en büyük oldugu icin en sağa yazılır.
|  ROOT  |     7
              / \
             5   8 
            / \   \
           1   6   9  
          / \
         0   3
##### 4, 5'ten küçük 3'den büyük olduğu için 3'ün sağına yazılır.
|  ROOT  |     7
              / \
             5   8 
            / \   \
           1   6   9  
          / \
         0   3
              \
               4
##### 2, 3'ten küçük 1'den büyük olduğu için 3'ün soluna yazılır.
|  ROOT  |     7
              / \
             5   8 
            / \   \
           1   6   9  
          / \
         0   3
            / \
           2   4

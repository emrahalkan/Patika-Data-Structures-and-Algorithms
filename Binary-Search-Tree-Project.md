# Binary Search Tree Projesi
### Proje 3: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
***
#### İlgili sayı dizisinde root: 5 değerini seçelim
- 7 değeri 5'ten büyük olduğu için sağına yerleştirilir. Böylece 5'in sağında 7 vardır.
- 1 değeri 5'ten küçük olduğu için soluna yerleştirilir. Böylece 5'in solunda 1 vardır.
- 8 değeri 5'ten büyük olduğu için sağa ve 7'den büyük olduğu için sağına yazılır. Böylece 7'nin sağında 8 vardır.
- 3 değeri 5'ten küçük olduğu için sola ve 1 den büyük olduğu için sağına yazılır. Böylece 1'in sağında 3 vardır.
- 6 değeri 5'ten büyük olduğu için sağa ve 7 den küçük olduğu için soluna yazılır. Böylece 7'nin solunda 6 vardır.
- 0 değeri 5'ten küçük olduğu için sola ve 1 den küçük olduğu için soluna yazılır. Böylece 1'in solunda 0 vardır.
- 9 değeri 5'ten büyük olduğu için sağa, 7'den büyük olduğu için sağına ve 8'den de büyük olduğu için sağına yazılır. Böylece en sağda 9 sayısı vardır.
- 4 değeri 5'ten küçük olduğu için sola, 1'den büyük olduğu için sağına ve 3'ten de büyük olduğu için sağına yazılır. Böylece 3'ün sağında 4 vardır.
- 2 değeri 5'ten küçük olduğu için sola, 1'den büyük olduğu için sağına ve 3'ten de küçük olduğu için soluna yazılır. Böylece 3'ün solunda 2 vardır.

Verilen dizide Root: 5 'e göre Binary search tree aşağıda ki gibidir.

             5
          /     \
        1         7
      /   \      /   \
     0     3    6       8
          /  \            \
         2     4            9

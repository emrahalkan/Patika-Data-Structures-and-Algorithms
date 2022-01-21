# Proje 1 (Insertion Sort)
1. ### [22,27,16,2,18,6] bu dizinin sort türüne göre aşamaları
  - İlk elemanın solunda bir şey olmayacağı için ikinci elemandan başanır [22,|27|,16,2,18,6], solda ki elemana göre kıyaslama yapılır. 27 sayısı 22 den büyük olduğu için işlemden çıkılır yani dizi olduğu gibi kalır. 
  - İkinci aşamada 16 sayısına geçilir [22,27,|16|,2,18,6]. 16 sayısı soldaki sayı ile kıyaslanır ve küçük olduğu için 27 sayısı sağa kayar. 16 sayısı 22 sayısı ile karşılaştırılır 16 küçük olduğu için 22 sayısı sağa kayar. Sıralama en son hali [16,22,27,2,18,6] olur.
  - Aşamalar bu şekilde kendini tekrar eder ve en son hali [2,6,16,18,22,27] olarak sıralama işlemi bitmiş olur.
2. ### Big-O Gösterimi
  - Big-O gösterimi worst case ile hesaplanır. Worst case de dizimiz en kötü durumda hesaplamak istersek [27,22,18,16,6,2] şeklinde olur.
  - En küçük sayı en başa gelene kadar (n.(n+1))/2 işlem yapılır. Son durum O(n^2) olur.
3. ### Time Complexity sorusunda aranan sayı olarak istenilmiş ama burada sıralama işlemi yapılmaktadır bu sebeble sıralama işlemine göre time complexity hesaplar isek,
  - Worst Case   : En kötü durumu bir önceki sorumuzda hesaplamıştık. O(n^2)
  - Best Case    : Sıralanmış bir şekilde verilseydi n elemanlı olan bir dizi de n elemanlı bir işlem yapılırdı. O(n)
  - Average Case : Best case ile worst case ortalaması. O(n^2)
4. Dizi sıralandıktan sonra 18 sayısı "Average case" kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
1. [7,|3|,5,8,2,9,4,15,6] => [|3|,7,5,8,2,9,4,15,6]
2. [3,7,|5|,8,2,9,4,15,6] => [3,|5|,7,8,2,9,4,15,6]
3. [3,5,7,8,|2|,9,4,15,6] => [|2|,3,5,7,8,9,4,15,6]
4. [2,3,5,7,8,9,|4|,15,6] => [2,3,|4|,5,7,8,9,15,6]

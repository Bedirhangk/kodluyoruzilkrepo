#Insertion Sort aşamaları:

Başlangıçta, [22, 27, 16, 2, 18, 6] dizisi elemanlarından sadece ilk eleman olan 22 sıralı bölüme dahildir.
Dizi: [22 | 27, 16, 2, 18, 6]

Sıradaki eleman olan 27, sıralı bölüme doğru konumlandırılır.
Dizi: [22, 27 | 16, 2, 18, 6]

16, sıralı bölüme yerleştirilir.
Dizi: [16, 22, 27 | 2, 18, 6]

2, sıralı bölüme yerleştirilir.
Dizi: [2, 16, 22, 27 | 18, 6]

18, sıralı bölüme yerleştirilir.
Dizi: [2, 16, 18, 22, 27 | 6]

Son olarak, 6, sıralı bölüme yerleştirilir.
Dizi: [2, 6, 16, 18, 22, 27]

Insertion Sort, her adımda bir elemanı doğru konumuna yerleştirdiği için, tüm diziyi sıralamak için n elemanlı bir dizide n-1 adıma ihtiyaç duyar. Yukarıdaki dizi 6 eleman içerdiğinden dolayı 5 adımda sıralanır.

#Big-O gösterimi: Insertion Sort, en kötü durumda (worst case) O(n^2) zaman karmaşıklığına sahiptir. Ortalama ve en iyi durumlarda ise (average case ve best case) O(n) zaman karmaşıklığına sahiptir.

Time Complexity (Zaman Karmaşıklığı):
Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden "Average case" kapsamına girer. Çünkü aradığımız sayının ortada olması durumu ortalama durumdur.

#[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı:

İlk adımda, en küçük eleman olan 2 seçilir ve başa yerleştirilir.
Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

İkinci adımda, 3 en küçük eleman olarak seçilir ve 2 ile yer değiştirir.
Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

Üçüncü adımda, 4 en küçük eleman olarak seçilir ve 2 ile yer değiştirir.
Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]

Dördüncü adımda, 5 en küçük eleman olarak seçilir ve 2 ile yer değiştirir.
Dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]

Bu şekilde Selection Sort sıralama algoritması devam eder.
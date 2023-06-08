# Merge Sort aşamaları:

İlk aşamada, [16, 21, 11, 8, 12, 22] dizisi iki eşit boyuttaki alt dizilere bölünür.
Sol alt dizi: [16, 21, 11]
Sağ alt dizi: [8, 12, 22]

Her bir alt dizi tekrar ikiye bölünür.
Sol alt dizi: [16] [21, 11]
Sağ alt dizi: [8] [12, 22]

Tekrar bölünmeye devam edilir.
Sol alt dizi: [16] [21] [11]
Sağ alt dizi: [8] [12] [22]

Alt dizilerin birleştirilmesi işlemi başlar.
Sol alt diziler: [16] [21] [11]
Sağ alt diziler: [8] [12] [22]

Sol alt diziler birleştirilir: [16, 21] [11]
Sağ alt diziler birleştirilir: [8, 12] [22]

İki birleştirilmiş alt dizi, ana diziye sıralı bir şekilde birleştirilir.
Dizi: [16, 21, 11, 8, 12, 22]

En son aşamada, tüm alt diziler birleştirilerek tam sıralı dizi elde edilir.
Dizi: [8, 11, 12, 16, 21, 22]

Merge Sort, alt dizileri bölme ve birleştirme işlemlerini tekrarlayarak sıralama yapar. Her aşamada diziyi ikiye böldüğü için log(n) aşama sayısı vardır. Her aşamada ise alt dizilerin birleştirilmesi O(n) zaman karmaşıklığına sahiptir. Bu nedenle Merge Sort'un zaman karmaşıklığı Big-O olarak O(n log n) olarak gösterilir.
* 1.Merge sort türüne göre aşamalar
- Mid elemanı seçilir
    Dizinin boyutu 6 olduğu için mid elemanı 3. olur. 2. index deki 11 değerine karşılık gelir. Ardından mid kısmından 2 ye böleriz.
    [16,21,11] | [8,12,22] şeklinde 2 parçamız oluşur.
- Oluşan 2 parçada ki tüm elemanlar tek kalıncaya kadar mid elemanı seçilip bölünür.
    1. [16,21] | [11] | [8,12] | [22]
    2. [16] | [21] | [11] | [8] | [12] | [22]
    3. Tüm elemanlar tekli duruma geldi. Karşılaştır ve birleştir işlemlerimiz kaldı.
    4. [16,21] | [11] | [8,12] | [22]
    5. [11,16,21] | [8,12,22]
    6. [8,11,12,16,21,22]

    * 2.Big-O Gösterimi Yapınız.

Dizi bölünmeye uğradığı için n - n/2 - n/4 ... adımlarından en fazla (log n) değeri karşımıza gelir. Bir de inputtan gelen dizinin büyük
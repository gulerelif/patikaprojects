[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
İlk adım olarak diziyi sıralarız.
[0,1,2,3,4,5,6,7,8,9]
Binary-search tree için en güzel sıralama şekli root elemanını mid olarak seçmektir.
Burda 4 veya 5 seçmek bize kalmış bi durumdur. Ben 4 ü seçiyorum.
Artık dizimiz 2 ye ayrılmış durumda. Ayyırlan diziler içinde de mid elemanlarını seçerek en kısa uzunlukta bir ağaç yapısı oluşturacağım.

ROOT elemanımız : 4
Solunda 2 - Sağında 7
Sol tarafından devam ediyorum.
    2 düğümünün solunda 1 sağında 3 bulunuyor. 1 den daha küçük eleman da mevcut. 1 düğümünden devam ediyorum
    1 düğümünün solunda 0 sağı boş.
    Sol taraf bitti
Sağ tarafta ki 7 düğümünden devam ediyorum.
    7 düğümünün solunda 6 sağında 8 bulunuyor. 6 dan küçük eleman mevcut , büyük de mevcut ancak büyük olan sayı 8 den de büyük olduğu için onu şuan ele almıyorum.
    6 düğümünün soluna 5 yerleştirilir.
    8 düğümüne geçtiğim zaman 9 sayısı 8 den büyük olduğu için sağına yerleşir.
    Sağ taraf da bitti.

                          4
                        /   \
                       2     7
                      /\    / \ 
                     1  3  6   8
                    /     /     \
                   0     5       9
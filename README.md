## merg-sortproject
# diziyi sort türüne göre aşamalandırın
[16,21,11,8,12,22] ==> merge-sort 
- önce diziyi ikiye bölücez: [16,21,11] [8,12,21]
- sonra böldüğümüz sayıları tekrar ikiye ayırıyoruz: [16,21] [11] [8,12] [22]
- tek eleman kalana kadar devam ediyoruz: [16] [21] [11] [8] [12] [22]
- tekrardan birleştirme işlemine geçicez: [16,21] [11] [8,12] [22]
- kendi içlerinde sıralarız: [11,16,21] [8,12,22]
- en son birleştirdiğimizde: [8,11,12,16,21,22]
# Big-o gösterimini yazın
- Big-o gösterimi: 
- merge-sort diziyi tek eleman kalana kadar böler ve tekrar birleştirir. işlemin süresini kısaltır.
- o(nlogn)




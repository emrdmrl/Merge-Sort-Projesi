# Merge-Sort-Projesi
## [16,21,11,8,12,22] -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- [16,21,11] [8,12,22] listeyi parçalara ayırmaya başladı.
- [16] [21,11] [8] [12,22]
- [16] [21] [11] [8] [12] [22] tek eleman kalıncaya kadar liste parçalanmaya devam etti.
- [16] [11,21] [8] [12,22] bölme işlemi bittikten sonra sıralama yaparak birleştirme işlemine geçiyor. İki liste için en baştaki elamanları karşılaştırıp ilk sıraya yazıyor.
- [11,16,21] [8,12,22]
- [8,11,12,16,21,22] En son elimizde sıralanmış halde liste kalıyor.
2. Big-O Gösterimini yazınız.
- Big-O gösterimi: nlog(n)
# BinarySearchTreeProject


## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

İlk başta 7 sayısını referans olarak alırız. 5 sayısı 7'den küçük olduğu için sol tarafına yazılır. 1 sayısı 7'den küçül olduğu için sol tarafa yazılacaktır. 5'den de küçük olduğu için 5 sayısının sol altına yazılır. 8 sayısı 7'den büyük olduğu için 7'nin sağına yazılır. 3 sayısı 7'den ve 5'den küçüktür fakat 1'den büyük olduğu için sol tarafta bulunan 1 sayısının sağ altındaki dalı olacak şekilde yazılır. 6 sayısı 7'den küçük, 5'den büyük olduğu için 5'in sağ tarafına yazılır. 0 sayısı soldaki sayılardan en küçüğü olduğu için 1'in soluna yazılır. 9 sayısı 7'den büyük olduğu için 8 ile karşılaştırılır, ondan da büyük olduğu için 8'in sağına yazılır. 4 sayısı 7 ve 5'den küçük 1'den büyük olduğu için 1'in sağına yazılır. 2 sayısı 7 ve 5'den küçük, 1'den büyük ve 4'den küçük olduğu için 4'ün soluna yazılır. Bu işlemler sonucunda oluşan ağacı şu şekilde yazabiliriz.

Root 7'dir. Root'un sağında 8, solunda 5 bulunur. Root 8'dir. Root'un sağında 9 solunda bir sayı bulunmaz. Root 5'dir. Root'un sağında 6, solunda 1 bulunur. Root 6'dır. Root'un sağında ve solunda sayı bulunmaz. Root 1'dir. Root'un sağında 3, solunda 0 bulunur. Root 3'dür. Root'un sağında 4, solunda 2 bulunur. Root 4'dür. Root'un sağında ve solunda sayı bulunmaz. Root 2'dir. Root'un sağında ve solunda sayı bulunmaz. Root 0'dır. Root'un sağında ve solunda sayı bulunmaz.

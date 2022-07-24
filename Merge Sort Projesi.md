Proje 2

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


Cevaplar:

1. Sorunun Cevaplandırması:

[16,21,11,8,12,22]

Verilen dizi ile merge sort işlemi yapacağız,bunun için diziyi önce ikiye böleriz

[16,21,11] [8,12,22] dizisini elde ederiz tek dizi kalana kadar bölme işlemini devam ettiririz

[16] [21,11] [8] [12,22]
 
[16] [21] [11] [8] [12] [22]

Bütün dizi tek elemanlı gruplar haline gelene kadar parçalandıktan sonra küçükten büyüğe olacak şekilde sıralanır ve tekrar birleştirilir.

[16] [11,21] [8] [12,22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]


2.Sorunun Cevaplandırılması:

Big O gösterimi: 2^x = n logn olmak üzere  O(n*log n) 

# Proje 1 Instertion Sort


## **[22,27,16,2,18,6] -> Insertion Sort**

### Sorular: 

+ 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
+ 2. Big-O gösterimini yazınız.
+ 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
+ 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
+ 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort a göre ilk 4 adımını yazınız.

## Çözümleme Aşamaları: 

## 1. Soru

+ [22,27,16,2,18,6] sayi dizisi için intertion sort turune gore asamalarini yazacağız

    +   22 sayisindan sonraya siralamayi gruplandirmak adina | sembolu kullandigimizi varsayalim. 


   ### İlk Geçiş: 

   + [22,27,16,2,18,6]  sayı dizimizin ilk sayisi 22, ilk sayıyı sıralı kabul ederiz ve ilk geçis tamamlanır.


### İkinci Geçiş: 

+ [22,27|16,2,18,6] burada her adimda ikinci sayimiz 27 sayisinin soluna yani 22 sayisina bakacagiz

   + 22<27 olduğu için bir işlem yapılmaz.

### Üçüncü Geçiş: 
+ 1. [22,27,16|2,18,6] her adimda ucuncu sayimiz olan 16 sayisinin soluna bakariz 

+ 2. [22,27,16|2,18,6]  16<27 bu yüzden 16 ve 27 yer değiştirir.
+ 3. [22,16,27|2,18,6]  16<22 bu yüzden yer degisimi yapılır. 

+   **[16,22,27|2,18,6]  üçüncü geçis bu şekilde tamamlanır.**


### Dördüncü Geçiş: 

+ [16,22,27,2|18,6] dorduncu sayimiz olan 2 sayisinin soluna bakarak ilerleriz 

1. [16,22,27,2|18,6] 27>2  bu yuzden yer değiştirir.
2. [16,22,2,27|18,6] 22>2 bu yuzden yer degisimi yapilir.
3. [16,2,22,27|18,6] 16>2 oldugu icin tekrar yer degistirir. 
4. [2,16,22,27|18,6] dorduncu gecis bu sekilde tamamlanır.


Beşinci Geçis: [2,16,22,27,18|6] 5. sayimiz 18, 18 in soluna bakarak yukaridaki işlemleri tekrarlariz 

+ 1. [2,16,22,27,18|6]  27>18 yer degisimi yapilir, 
+ 2. [2,16,22,18,27|6] 22>18 yer degisimi yapilir
+ **3. [2,16,18,22,27|6] burada 16<18 oldugu icin uygun durumdadir besinci geçiş burada sonlanır.


Altinci Gecis: [2,16,18,22,27,6|] altinci sayimiz 6, soluna bakarak ayni islemleri tekrarliyoruz.
1. [2,16,18,22,27,6|] 27>6 yer degisimi yapilir.
2. [2,16,18,22,6,27|] 22>6 yer degisimi yapilir.
3. [2,16,18,6,22,27|] 18>6 yer degisimi yapilir.
4. [2,16,6,18,22,27|] 16>6 yer degisimi yapilir.
5. [2,6,16,18,22,27|] burada 2<6 dır ve dizi dogru sirasina girmis olur.

Final dizi siramiz: [2,6,16,18,22,27] olmus olur. 


2. Soru 

Big o notation gösterimi big o gösterimi O(n^2)

3. Soru
Best Case: Dizi tamamen sirali bicimde ise ve her sayinin uzerinden sadece bir defa geciyor isek buna Best Case deriz bunu O(n) ile ifade ederiz.

Bizim dizimiz icin best case [2, 6, 16, 18, 22, 27]

Worst Case: Dizide ele aldığımız her sayi kendisinden öncekinden kücük ise bu en kötü senaryodur buna Worst Case denir  O(n^2) ile ifade ederiz.

Bizim dizimiz icin Worst Case [27, 22, 18, 16, 6, 2]  

Average Case: Best Case ile Worst Case in ortalamasına Average case deriz. Average case elde etmek icin ayni sekilde O(n^2) kullaniriz.

4. Soru 

18 sayisi bu dizi icin  Average Case olarak degerlendirilir dizi siralandıgında tam ortadadir.

5. Soru 

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sorta göre ilk 4 adımını yazınız.

1. [7|3,5,8,2,9,4,15,6]
2. [3,7|,5,8,2,9,4,15,6]
3. [3,5,7|,8,2,9,4,15,6]
4. [3,5,7,8|,2,9,4,15,6]
5. [2,3,5,7,8,|,9,4,15,6]




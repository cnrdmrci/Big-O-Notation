# Big O Notation

- Big O Notation
- Big O, Omega, Theta
- Time and Space Complexity
- Best, Average, Worst Complexity

### Big O Notation

Bir kod parçacığının çalışma süresini hesaplamada ve harcadığı alanı analiz etmekte kullanılan matematiksel bir gösterimdir. 

-  O(1) : Sabit bir zamandaki işlem.(Constant Complexity)
```C#
int i = 5;
```

-  O(n): Lineer bir zamandaki işlem.(Linear Complexity)
```C#
for(int i = 0 ; i>10 ; i++)
{
  Console.WriteLine(i);
}
```

-  O(log n): Logaritmik bir zamandaki işlem.(Logarithmic Complexity)
```C#
for(int i = 1024 ; i>1 ; i/=2)
{
  Console.WriteLine(i);
}
```

### Big O, Omega, Theta

- Big O : Karmaşıklığın üst sınırlarını tanımlar. En kötü durumu simgeler.
- Omaga : Karmaşıklığın alt sınırlarını tanımlar. En iyi durumu simgeler.
- Theta : Ortalama karmaşıklığı ifade eder.

### Time and Space Complexity
- Time complexity: 
   - Algoritmanın çalışma zamanının hesaplanmasının analiz edildiği kısımdır.
- Space complexity: 
   - Algoritmanın çalıştığı zaman içerisinde kapladığı alanın analiz edildiği kısımdır. Kullanılacak bellek, analiz edilmesi gereken önemli bir faktördür.

### Best, Average, Worst Complexity

Kullanılan algoritmaların sonuca ulaşmada yapacağı tekrar sayısına bağlı olarak 
  - en iyi durum,
  - ortalama durum,
  - en kötü durum
 
şeklinde analizleri ortaya çıkmaktadır. 


Sıralama algoritmaları üzerinden örnek vermek istersek;
 - Bir sıralı listenin küçükten büyüğe sıralanmasında sadece ilk 2 sayının yerlerinin değişmesiyle tamamlanması 
 - Büyükten küçüğe sıralı bir listenin küçükten büyüğe sıralanması

En iyi ve en kötü durumlara örnek verilebilir.

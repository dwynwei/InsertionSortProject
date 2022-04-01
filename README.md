# InsertionSortProject

    [22,27,16,2,18,6] -> Insertion Sort 
    
1.	[2,27,16,22,18,6]   n adet eleman dolaşıldı.
2.	[2,6,16,22,18,27]   n-1 adet eleman dolaşıldı.
3.	[2,6,16,18,22,27]   n-2 adet eleman dolaşıldı.

“n” sürekli düşerek 1 e kadar gider. (n2+n)/2 den dominant olan n2 notasyon gösterimi için seçilir. O(n2) olarak time complexity tanımı yapılır.

18 elemanı burda Average Case durumundadır. Çünkü, 3. Adımda bitmiş gibi görünsede 22 ve 27 elemanlarının kontrolleri aslında 4. Ve 5. Adımda devam etmektedir. Bu da 18 sayısının bulunma aralığının ortalarda olduğunu göstermektedir. 

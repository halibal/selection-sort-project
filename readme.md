# Selection Sort Project

## [22,27,16,2,18,6] -> Selection Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
   - Birinci asamada 22, en kucuk sayi olan 2 ile yer degistirir.
     - [22,27,16,2,18,6] -> [2,27,16,22,18,6]
   - Ikinci asamada 27, ikinci en kucuk sayi olan 6 ile yer degistirir.
     - [2,27,16,22,18,6] -> [2,6,16,22,18,27]
   - Ucuncu asamada kendisinden daha kucuk baska eleman kalmadigindan, ucuncu en kucuk sayi olan 16'nin yeri sabit kalir.
     - [2,6,16,22,18,27]
   - Dorduncu asamada 22, dorduncu en kucuk sayi olan 18 ile yer degistirir.
     - [2,6,16,22,18,27] -> [2,6,16,18,22,27]
   - Besinci asamada 22, dizinin son sayisi 27'den kucuk oldugu icin yerinde sabit kalir ve dizi kucukten buyuge siralanmis olur.
     - [2,6,16,18,22,27]
  
2. Big-O gösterimini yazınız.
   - Ilk seferde n, ikincide n-1, ucuncude n-2 seklinde ve nihayetinde +1 olana kadar...
   - `n + (n-1) + (n-2) ... + 1 = n.(n+1)/2 = (n²+n)/2`
   - Bu islem sayisina gore mevcut en buyuk katsayili n, Big-O'yu ifade eder -> `O(n²)`

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
   - Average Case:
     - `O(n²)`
   - Worst Case:
     - `O(n²)`
   - Best Case:
     - `O(n²)`

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   - Aranan sayi dizinin ortasinda bulundugu icin Average Case kapsamina girmektedir.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız

    1. [2,3,5,8,7,9,4,15,6] -> 7 ile 2 yer degisir
    2. [2,3,5,8,7,9,4,15,6] -> 3 yerinde sabit kalir
    3. [2,3,4,8,7,9,5,15,6] -> 5 ile 4 yer degisir
    4. [2,3,4,5,7,9,8,15,6] -> 8 ile 5 yer degisir

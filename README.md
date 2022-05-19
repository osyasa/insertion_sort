# INSERTION SORT

## [22,27,16,2,18,6] -> Insertion Sort

## 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

# code block
    [22,27,16,2,18,6]
    ---
    [2,27,16,22,18,6] -> İlk Geçiş
    [2,6,16,22,18,27] -> İkinci Geçiş
    [2,6,16,22,18,27] -> Üçüncü Geçiş
    [2,6,16,18,22,27] -> Dördüncü Geçiş
    [2,6,16,18,22,27] -> Beşinci Geçiş

## 2. Big-O gösterimini yazınız.

ilk geçiş için -> n
ikinci geçiş için -> n-1
üçüncü geçiş için -> n-2
.
.
.
son geçiş için -> 1

Toplam: n(n+1) / 2 = ![Image](http://www.sciweavers.org/upload/Tex2Img_1652991773/render.png)

## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Worst Case -> ![Image](http://www.sciweavers.org/upload/Tex2Img_1652991773/render.png)

Average Case -> ![Image](http://www.sciweavers.org/upload/Tex2Img_1652991773/render.png)

Best Case -> ![Image](http://www.sciweavers.org/upload/Tex2Img_1652991819/render.png)

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı ortada bulunduğu için average case kapsamına girer.
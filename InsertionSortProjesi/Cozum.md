# Insertion Sort Örneği

## Dizinin ilk hali [22,27,16,2,18,6]


1. [2,27,16,22,18,6] -> 2 ve 22 yer değiştirdi.
2. [2,6,16,22,18,27] -> 6 ve 27 yer değiştirdi.
3. [2,6,16,18,22,27] -> 18 ve 22 yer değiştirdi.

## Big-O
O(n^2)

18 sayısı avarage case olur.

### Açıklaması 

Dizide değerler artan bir şekilde sıralanmalı . Örneğin ilk adımda 
dizinin en küçük değeri olan 2 yi 22 ile yer değiştirdik . İkinci adımda dizinin 2. indisine gelmesi gereken en küçük değer 6 dır . 6 ile indis 2 de bulunan 27 nin yerlerini değiştirdik . Bu şekilde dizi sıralı bir hale gelene kadar işlem tekrarlanır . Bu dizi 3 adımda sıralı hale geldi.


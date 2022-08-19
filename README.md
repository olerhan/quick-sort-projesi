# Quick Sort Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Quick Sort aşamalarını yazınız.

|[7|5|1|8|3|6|0|9|4|2]|Quick Sort|
|-|-|-|-|-|-|-|-|-|-|-|
|[5|1|3|0|4|2]|-[6]-|[7|8|9]|1. Aşama: Pivot 6 seçildi|
|[1|0|2]|-[3]-|[5|4]|-[6]-|[7]|-[8]-|[9]|2. Aşama: Pivot 3 ve 8 seçildi|
|[0]|-[1]-|[2]|-[3]-|-[4]-|[5]|-[6]-|[7]|-[8]-|[9]|3. Aşama: Pivot 1 ve 4 seçildi|

* Big-O gösterimini yazınız.

>Avarage Case: O(nlogn)

>Pivot seçimlerim düzgünce yarıya bölemediği durumlarda Worst Case: O(n^2)

# Link
[www.patika.dev](https://www.patika.dev/)
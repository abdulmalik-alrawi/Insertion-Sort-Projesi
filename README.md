# Insertion-Sort-Projesi


[22,27,16,2,18,6] 

[22,27,16,2,18,6] Sort Türüne göre . verilen öbeğin en küçük elemanı 2'dir 2 ile 22 swap yapar.
[2,27,16,22,18,6] ikinci en küçük eleman olan 6 ile 27 swap yapar.
[2,6,16,22,18,27] üçüncü en küçük elaman olan 16 zaten olması gereken yerde olduğu için swap yapmaz.dördüncü en küçük eleman olan 18 ile 22 swap yapar.
[2,6,16,18,22,27] 22 ve 27 elemanları zaten olması gereken yerde olduğu için herhangi bir swap yapmazlar ve aşamalar tamamlanır.

2-Big-O =>  O(n^2)

3-Time Complexity:   . Worst Case:Aradığımız sayının sonda olması 
                     . Average Case:Aradığımız sayının ortada olması 
                     . Best Case:Aradığımız sayının dizinin en başında olması

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? . 

Dizinin sıralanmış halinde .
[2,6,16,18,22,27]  18  sayısı average case kapsamına girer.

[7,3,5,8,2,9,4,15,6]  ilk 4 adımını .

1- [2,3,5,8,7,9,4,15,6] 
2- [2,3,5,8,7,9,4,15,6] 
3- [2,3,4,8,7,9,5,15,6] 
4- [2,3,4,5,7,9,8,15,6] 

www.patika.dev

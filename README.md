# PatikaDev-Proje1
# [Patika.Dev] (www.patika.dev)
### Insertion Sort Project
## SORU-1:
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
#### [22,27,16,2,18,6] (n)
#### [2,27,16,22,18,6] (n-1)
#### [2,6,16,22,18,27] (n-2)
#### [2,6,16,22,18,27] (n-3)
#### [2,6,16,18,22,27] (n-4)

## SORU-2:
### Big-O gösterimini yazınız.
#### O(n^2)

## SORU-3:
### Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
#### Insertion sortta en küçüğü bulmaya çalıştığımızda işlev yavaş olduğu için buna en uygun case worst casedir. çünkü worst case algoritmanın en yavaş olduğu casedir. Worst Case=> O(n^2)
## SORU-4
### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
#### [2,6,16,18,22,27]-dizinin sıralanmış hali
#### Aranan sayının ortada olması nedeniyle avarage case kapasamına girer.

## SORU-5
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#### [2,3,5,8,7,9,4,15,6]  2 ile 7 sayısı yer değiştirdi
#### [2,3,5,8,7,9,4,15,6]  (n-1) adımda 3 en küçük olduğu için herhangi bir yer değişimi olmadı.
#### [2,3,4,8,7,9,5,15,6]  5 ile 4 sayısı yer değiştirdi
#### [2,3,4,5,7,9,8,15,6]  8 ile 5 sayısı yer değiştirdi


# Insertion-sort-Project
## [22,27,16,2,18,6] -> Insertion Sort

## 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
- [2,27,16,22,18,6] En küçük sayı 2'dir bu nedenle 2 ve 22 sayısı yer değiştirmiştir..
- [2,6,16,22,18,27] Diğer en küçük sayımız 6 olduğu için 27 ve 6 sayılarımız yer değiştirmiştir.
- [2,6,16,22,18,27] Bu aşamadaki sayımız zaten en küçük olduğundan yerine karışmıyoruz.
- [2,6,16,18,22,27] Dördüncü en küçük sayımız olan 18, 22 ile yer değiştirmiştir.
- [2,6,16,18,22,27] Projemizde istenilen sıralama bu olduğundan sıralamaya dokunulmadı.
## 2.Big-O gösterimini yazınız. 
- O (n^2)
## 3.Time Complexity:

### Average case 
- Aradığımız sayının ortada olmasıdır.
### Worst case 
- Aradığımız sayının sonda olmasıdır.
### Best case
- Aradığımız sayının dizinin en başında olmasıdır.

## 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

- Aradığımız sayı sıralamamıza göre ortada bulunduğundan **Average Case** kapsamındadır.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
-  [2,3,5,8,7,9,4,15,6] En küçük sayımızı 2 olarak belirleyip 7 rakamıyla değiştirdik.
-  [2,3,5,8,7,9,4,15,6] Sıradaki sayımız 3 zaten 2'den sonra en küçük sayı olduğundan yerinde kaldı.
-  [2,3,4,8,7,9,5,15,6] Üçüncü en küçük rakamımız 4, 5 ile yer değiştirmiştir.
-  [2,3,4,5,7,9,8,15,6] Son adımımızda5 ile 8 sayımız yer değiştirmiştir.

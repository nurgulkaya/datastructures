# Binary Search Tree Projesi

## Soru

- [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız. 
- (Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.)

## Cevap

![binary](https://user-images.githubusercontent.com/83287902/189889651-f97c5b80-32e8-41ff-8cdc-83c21bcf0846.png)

#### Kendinden küçük olan eleman sola, büyük olan sağa eklenir.

- Root 7'dir.
- 5, 7'den küçük olduğu için soluna yerleşir.
- 1, 7 ve 5'ten küçüktür. O yüzden 5'in soluna eklenir.
- 8, 7'den büyük olduğu için 7'nin sağına yazılır.
- 3, 7 ve 5'ten küçük o yüzden sola geçer, 1'den de büyük o sebeple sağa yazılır.
- 6, 7'den küçük sola geçer, 5'ten büyüktür, 5'in sağına yerleştirilir.
- 0, 7, 5 ve 1'den küçüktür. 1'in soluna yazılır.
- 9, 7 ve 8'den büyüktür. 7'nin sağına sonra 8'in sağına yazılır.
- 4, 7 ve 5'ten küçük o yüzden sola geçer, 1 ve 3'ten büyük olduğundan 3'ün sağına yazılır.
- 2, 7 ve 5'ten küçük olduğunda sola, 1'den büyük o yüzden sağa 3'ten küçük olduğu için sola yazılır.

## [Patika Profilim](https://app.patika.dev/nurkaya)

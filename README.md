[22,27,16,2,18,6] -> Insertion Sort

1. Dizin insertion sort türünden verildiğinden en küçük sayıyı bulup en baştakiyle değiştirme yapacaktır, dolayısıyla basamaklar şöyle olacaktır.

	1. Basamak
		[2,27,16,22,18,6] 
	2. Basamak
		[2,6,16,22,18,27] 
	3. Basamak ( Bu basamakta bir değişiklik yapmaz, çünkü sıralı)
		[2,6,16,22,18,27] 
	4. Basamak
		[2,6,16,18,22,27] 
	5. Basamak
		[2,6,16,18,22,27] 
2. Big-O gösterimi
	Big - O (n^2)
3. 18 sayısı average case kapsamındadır.

2. Soruya cevap -- [7,35,8,2,9,4,15,6] dizisinin ilk dört basamağı
    1. [2,35,8,7,9,4,15,6]
    2. [2,4,8,7,9,35,15,6]
    3. [2,4,6,7,9,35,15,8]
    4. [2,4,6,7,9,35,15,8] - 4. basamakta yer değiştirme olmaz. 7 yi diğerleriyle karşılaştırır ve onlardan küçük olduğu için yerinde bırakıp bir sonraki basamağa geçer.
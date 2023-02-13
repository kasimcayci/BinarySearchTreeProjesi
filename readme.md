# BİNARY SERACH TREE PROJESİ
Veri Yapıları ve Algoritmalar Dersi Binary Search Tree Projesi

# Proje Hakkında
Projede verilen dizinin Binary-Search-Tree aşamaları gerçekleştirilmiştir.



## Proje 3 Binary Search Tree Projesi

7, 5, 1, 8, 3, 6, 0, 9, 4, 2 dizisinin Binary-Search-Tree aşamaları


i. Öncelikle bir root node vardır. Sonrasında sayılar root node'den büyük veya küçük oluşuna göre sağına veya soluna yerleştirilerek Binary tree oluşturulur.

Bu dizimizde root node 7 olarak kabul edip başlayalım. Root= 7


ii. İkinci değer 5, root değerden küçük mü, büyük mü bakılır. Küçük olduğundan sol alt tarafa yazılır

								7			Seviye 0
						5					Seviye 1

iii. Üçüncü değer 1, root değerden küçük olduğu için soluna yazılacak, sol tarafta 5 değeri de var. Onunla da karşılaştırıp ondan küçük olduğu görülür ve onun da soluna yazılır.

								7			Seviye 0
						5					Seviye 1
		1									Seviye 2

iv. Dördüncü değer 8, root değerden büyük olduğu için sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1									Seviye 2

v. Beşinci değer 3, root değerden küçük olduğu için soluna yazılacak, sol tarafta 5 değeri de var. Onunla da karşılaştırıldığında ondan da küçük olduğu görülür. Sol altta 1 değeri de var. Onunla da karşılaştırılıp büyük olduğu görülüp sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1									Seviye 2
				3							Seviye 3

vi. Altıncı değer 6, root değerden küçük olduğu için soluna yazılacak, sol altta 5 değeri de var. Onunla karşılaştırıldığında ondan büyük olduğu için onun sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1					6				Seviye 2
				3							Seviye 3

vii. Yedinci değer 0, root değerden küçük olduğu için soluna yazılacak, sol altta 5 değeri de var. Onunla karşılaştırıldığında ondan da küçük olduğu için yine sola yazılacak. Sol altta 1 değeri de var. Onunla karşılaştırılıp küçük olduğu görülnce sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1					6				Seviye 2
	0			3							Seviye 3

viii. Sekizinci değer 9, root değerden büyük olduğu için sağına yazılacak. Sağ altta 8 değeri de var. Onunla karşılaştırılıp büyük olduğu için sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1					6			9	Seviye 2
	0			3							Seviye 3

ix. Dokuzuncu değer 4, root değerden küçük olduğu için soluna yazılacak, sol altta 5 değeri de var. Ondan küçük olduğu için yine sola yazılacak. Sol altta 1 değeri var. ondan büyük olduğu için sağına yazılacak. Onunla karşılaştırılıp büyük olduğu görülünce sağına yazılacak. Sağ altta 3 var. Onunla karşılaştırılıp büyük olduğu için sağına yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1					6			9	Seviye 2
	0			3							Seviye 3
					4						Seviye 4

x. Onuncu değer 2, root değerden küçük olduğu için soluna yazılacak, sol altta 5 değeri de var. Ondan küçükolduğu için yine sola yazılacak. Sol altta 1 değeri var. Ondan büyük olduğu için sağına yazılacak. Onunla karşılaştırılıp büyük olduğu görülünce sağına yazılacak. Sağ altta 3 var. onunla karşılaştırılıp küçük olduğu için soluna yazılır.

								7			Seviye 0
						5			8		Seviye 1
		1					6			9	Seviye 2
	0			3							Seviye 3
			2		4						Seviye 4


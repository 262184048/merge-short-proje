# merge-short-proje

# PROJE-2 (Merge Sort Projesi)
 ## [10,35,30,25,20,15] -> Merge Sort    16,21,11,8,12,22
- ### Yukarıdaki dizinin sort türüne göre aşamaları aşağıda belirtilmiştir.
### 
**1)** [10,35,30,25,20,15] dizisini ikiye bölelim.

**2)** [10,35,30] ve [25,20,15] olmak üzere iki dizi oluştu.

**3)** [10,35] - [30] ve [25,20] - [15] olarak tekrar bölelim.

**4)** Verileri teker teker olmak üzere ayıralım: [10]-[35]-[30]-[25]-[20]-[15]

**5)** Birer parçaya ayırdığımız verileri küçükten büyüğe kendi grupları içinde birleştirelim: [10,20]-[35]-[15,25]-[30] => [10,15,20] - [25,30,35]

**6)** Son olarak,iki grup da birleştirilir. [10,15,20,25,30,35]

- ### Big-O gösterimini yazınız.
### cevap: 
O(nLogn) 'dir.

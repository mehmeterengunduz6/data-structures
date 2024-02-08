## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

---

**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

22 ve 27'yi ele aldık. 22 daha küçük. Listenin yeni hali: [22,27,16,2,18,6]  
27 ve 16'yı ele aldık. 16 daha küçük. Listenin yeni hali: [22,16,27,2,18,6]  
22 ve 16'yı ele aldık. 16 daha küçük. Listenin yeni hali: [16,22,27,2,18,6]  
27 ve 2'yi ele aldık. 2 daha küçük. Listenin yeni hali: [16,22,2,27,18,6]  
22 ve 2'yi ele aldık. 2 daha küçük. Listenin yeni hali: [16,2,22,27,18,6]  
16 ve 2'yi ele aldık. 2 daha küçük. Listenin yeni hali: [2,16,22,27,18,6]  
27 ve 18'i ele aldık. 18 daha küçük. Listenin yeni hali: [2,16,22,18,27,6]  
22 ve 18'i ele aldık. 18 daha küçük. Listenin yeni hali: [2,16,18,22,27,6]  
27 ve 6'yı ele aldık. 6 daha küçük. Listenin yeni hali: [2,16,18,22,6,27]  
22 ve 6'yı ele aldık. 6 daha küçük. Listenin yeni hali: [2,16,18,6,22,27]  
18 ve 6'yı ele aldık. 6 daha küçük. Listenin yeni hali: [2,16,6,18,22,27]  
16 ve 6'yı ele aldık. 6 daha küçük. Listenin yeni hali: [2,6,16,18,22,27]  

---

Big-O gösterimini yazınız.

O(n^2)

---

**Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız**

**Average case: Aradığımız sayının ortada olması**
**Worst case: Aradığımız sayının sonda olması**
**Best case: Aradığımız sayının dizinin en başında olması.**

Average case

---

**[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**

Lowest value is 2. Swap 2 and 7. [2,3,5,8,7,9,4,15,6]

Second lowest value is 3. No change required. [2,3,5,8,7,9,4,15,6]

Third lowest value is 4. Swap 4 and 5. [2,3,4,8,7,9,5,15,6]

Fourth lowest value is 5. Swap 5 and 8. [2,3,4,5,7,9,8,15,6]

Fifth lowest value is 6. Swap 7 and 6. [2,3,4,5,6,9,8,15,7]

Sixth lowest value is 7. Swap 9 and 7. [2,3,4,5,6,7,8,15,9]

Seventh lowest value is 8. No change required. [2,3,4,5,6,7,8,15,9]

Ninth lowest value is 9. Swap 15 and 9. [2,3,4,5,6,7,8,9,15]

---

## Proje 2

[16,21,11,8,12,22] -> Merge Sort

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

Subarray 1: [16,21,11]

Subarray 2: [8,12,22]


Subarray 1a: [16,21]
Subarray 1b: [11]

Subarray 2a: [8,12]
Subarray 2b: [11]


Subarray 1ax: [16]
Subbarray 1ay: [21]

Subarray 2ax: [8]
Subarray 2ay: [12]



Sorted Subarray 1a: [16,21]
Sorted Subarray 2a: [8,12]

Sorted Subarray 1: [11,16,21]
Sorted Subarray 2: [8,12,22]

**Sorted array: [8,11,12,16,21,22]**

---

**Big-O gösterimini yazınız.**

O(nlogn)

---

## Proje 3
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

**Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.**

Root 7'dir. 

7'nin solunda 5 bulunur. 

5'in solunda 1 bulunur. 

7'nin sağında 8 bulunur.

1'in sağında 3 bulunur.

5'in sağında 6 bulunur.

1'in solunda 0 bulunur.

8'in sağında 9 bulunur.

3'ün sağında 4 bulunur.

3'ün solunda 2 bulunur.
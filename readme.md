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

**Big-O gösterimini yazınız.**

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


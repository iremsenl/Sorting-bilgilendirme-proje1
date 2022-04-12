# Insertion sorting
## [22,27,16,2,18,6] n tane elemana bakılır.
-[2,27,16,22,18,6] n-1 tane elemana bakılır.
-[2,6,16,22,18,27] n-2 tane elemana bakılır.
-[2,6,16,18,22,27] n-3 tane elemana bakılır
*Insertion Sorting dizileri sıralanırken; küçükten büyüğe sırasıyla yer değiştirme yapılır.*


# Big O Notation 
## [22,27,16,2,18,6]
### Ben 18 sayısını arıyorsam:
- A Algoritmam --> 18 sayısını bulmak için; algoritmam n tane elemanın hepsini tarar. 
- B Algoritmam --> 18 sayısını bulmak için; algoritmam n tane sayının ortasından başlar, 18 sayısı sağında kaldığından sağa doğru sayıları tarar. 
- A Algoritmam --> 6 birim zamanda elemanlarımı tararken  *hepsi tarandığından 6 birim zaman*
- B Algoritmam --> 2 veya 3 birim zamanda elemanlarımı tarar  *2ˣ=6 ise 2< x <3 birim zaman*
*Big O Notation bizim arama yapmamızı kolaylaştırır. Zamandan kazandırır.*
*A Algoritmam Big O Notation'a sahip değil; B Algoritmam sahip!*

# Time Complexity 

## Average Case [22,27,16,2,18,6] "Aradığım sayı ortanca olmalı: 16-2"
*Average case genelde beklenilen durumdur. Analizi diğer algoritmalara göre daha zordur.*
### --> Sayım 16 olduğunda:
- 22 -> 27 -> 16 olarak analiz ederim.
### --> Sayım 2 olduğunda:
- 22 -> 27 -> 16 -> 2 olarak analiz ederim.

## Worst Case [22,27,16,2,18,6] "Aradığım sayı sonda olmalı: 6"
*Worst Case beklenilen "en yavaş" analiz durumudur.*
- En yavaş olduğu ve sayı sonda olduğundan analize baştan (22 sayısı) başlanır.
- 22 -> 27 -> 16 -> 2 -> 18 -> 6 olarak analiz edilir.

## Best Case [22,27,16,2,18,6] "Aradığım sayı başta olmalı : 22"
*Best Case beklenilen "en hızlı" durumdur*
- 22 sayısına en hızlı şekilde ulaşılması için analiz baştan başlatılır
- -> 22 olarak bulunur

## 18 sayısı için "Time Complexity"

### Average Case [22,27,16,2,18,6] 
- 18 sayısına 5 birim zamanda ulaşılacağından; kolay bir analiz olmaz. Tercih etmiyorum.
- 22 -> 27 -> 16 -> 2 -> 18 olarak analiz edilir.

### Worst Case [22,27,16,2,18,6]
- 18 sayısını en yavaş durumda analiz edeceğinden; analize 22 sayısından başlanır.
- 5 birim zamanda ulaşır. 
- Kolay bir analiz olmaz. Tercih etmiyorum.
- 22 -> 27 -> 16 -> 2 -> 18

### Best Case [22,27,16,2,18,6]
- 18 sayısını en hızlı şekilde analiz edeceğinden; analize 6 sayısından başlanır.
- 6 -> 18
*18 sayısına en kolay şekilde Best Case ile ulaşılır. Tercih ederim.*

# [7,3,5,8,2,9,4,15,6] Dizisinin Insertion Sort'a göre ilk 4 adımı:
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]








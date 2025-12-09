# zebra
Zebra Problemi

---

# Zebra Puzzle (Modified Version)

There are 5 houses in a row, each of a different color. In each house lives a person of a different nationality. Each person drinks a different beverage, eats a different food, plays a different sport, and keeps a different pet.

Clues:

    The Turk lives in the red house, drinks ayran, eats lahmacun, wrestles, and keeps a cat.

    The Japanese lives in the green house, drinks tea, eats sushi, practices judo, and keeps a rabbit.

    The Italian eats pizza, plays football, drinks coffee, and keeps a parrot.

    The Brazilian eats feijoada, plays tennis, drinks smoothie, and keeps a dog.

    The Swede eats köttbullar, plays ice hockey, lives in the white house, drinks water, and keeps fish.

    In the middle house they drink water.

    The cat lives in the house of the person who drinks ayran.

    The dog lives in the house immediately to the left of the person who drinks ayran.

    The parrot lives in the house of the person who drinks coffee.

    The person who drinks smoothie plays tennis.

Question:

Determine who lives in each house, the color of each house, what each person drinks, eats, plays, and which pet they keep.

The houses are numbered 1 to 5 from left to right.

Regarding your statement:

This question is not a direct quotation. It has been rewritten originally, only modeled after the Zebra Puzzle.

---

# Zebra Problemi

5 ev var, her evde farklı bir milletten bir kişi yaşıyor. Her kişinin farklı bir ev rengi, farklı bir içecek, farklı bir yemek, farklı bir spor aktivitesi ve farklı bir evcil hayvanı var.
Kısıtlar:

    Türk, kırmızı evde yaşıyor, ayran içiyor, lahmacun yiyor, güreş yapıyor, kedi besliyor.
        
    Japon, yeşil evde yaşıyor, çay içiyor, sushi yiyor, judo yapıyor, tavşan besliyor.
        
    İtalyan, pizza yiyor, futbol oynuyor, kahve içiyor, papağan besliyor.
        
    Brezilyalı, feijoada yiyor, tenis oynuyor, smoothie içiyor, köpek besliyor.
        
    İsveçli, köttbullar yiyor, buz hokeyi oynuyor, beyaz evde yaşıyor, su içiyor, balık besliyor.
        
    Ortadaki evde su içiliyor.
        
    Kedi, ayran içen kişinin evinde yaşıyor.
        
    Köpek, ayran içen kişinin solundaki evde yaşıyor.
        
    Papağan, kahve içen kişinin evinde yaşıyor.
        
    Smoothie içen kişi, tenis oynuyor.

Soru:

Her evde kimin yaşadığını, evin rengini, kişinin içtiği içeceği, yediği yemeği, yaptığı sporu ve beslediği hayvanı belirleyiniz.

Evler soldan sağa 1'den 5'e kadar numaralandırılmıştır. (1: en soldaki ev, 5: en sağdaki ev)

Not: Tüm bu kısıtlar aynı anda sağlanmalıdır.

Bu soru birebir alıntı değildir. Sâdece Zebra Problemine benzetilerek orijinal olarak tekrar yazılmıştır.

---

=========================================
ZEBRA PUZZLE/PROBLEM DEFINITIVE SOLUTION
=========================================

There are 2 valid solutions. Both satisfy all constraints:

The only difference between the two solutions is the colors of the Italian and Brazilian.

--------------------------------------------------------------------------------
SOLUTION 1:
--------------------------------------------------------------------------------
House  Nation       Color      Drink      Food         Sport        Pet       
--------------------------------------------------------------------------------
1      Brazilian    yellow     smoothie   feijoada     tennis       dog       
2      Turkish      red        ayran      lahmacun     wrestling    cat       
3      Swedish      white      water      meatballs    ice hockey   fish      
4      Japanese     green      tea        sushi        judo         rabbit    
5      Italian      blue       coffee     pizza        football     parrot    

--------------------------------------------------------------------------------
SOLUTION 2:
--------------------------------------------------------------------------------
House  Nation       Color      Drink      Food         Sport        Pet       
--------------------------------------------------------------------------------
1      Brazilian    blue       smoothie   feijoada     tennis       dog       
2      Turkish      red        ayran      lahmacun     wrestling    cat       
3      Swedish      white      water      meatballs    ice hockey   fish      
4      Japanese     green      tea        sushi        judo         rabbit    
5      Italian      yellow     coffee     pizza        football     parrot    

===========================================================
VERIFICATION OF ALL CONSTRAINTS (Valid for both solutions):
===========================================================

1. ✓ Turkish: lives in red house, drinks ayran, eats lahmacun, does wrestling, owns a cat.
2. ✓ Japanese: lives in green house, drinks tea, eats sushi, does judo, owns a rabbit.
3. ✓ Italian: eats pizza, plays football, drinks coffee, owns a parrot.
4. ✓ Brazilian: eats feijoada, plays tennis, drinks smoothie, owns a dog.
5. ✓ Swedish: eats meatballs, plays ice hockey, lives in white house, drinks water, owns fish.
6. ✓ Water is drunk in the middle house (house 3).
7. ✓ The cat lives with the person who drinks ayran (Turkish).
8. ✓ The dog (house 1) lives in the house to the LEFT of the person who drinks ayran (house 2).
9. ✓ The parrot lives with the person who drinks coffee (Italian).
10.✓ The person who drinks smoothie (Brazilian) plays tennis.

===========
CONCLUSION:
===========

The Zebra problem has been successfully solved!
2 valid solutions were found.
Both solutions satisfy all 10 constraints.
The only difference between solutions: The colors of the Brazilian and Italian are swapped.

================================================================================

---

============================
ZEBRA PROBLEMİ KESİN ÇÖZÜMÜ
============================

2 adet geçerli çözüm vardır. Her ikisi de tüm kısıtları sağlar:

İki çözüm arasındaki tek fark İtalyan ve Brezilyalı'nın renkleridir.

--------------------------------------------------------------------------------
ÇÖZÜM 1:
--------------------------------------------------------------------------------
Ev   Millet       Renk     İçecek     Yemek        Spor         Hayvan    
--------------------------------------------------------------------------------
1    Brezilyalı   sarı     smoothie   feijoada     tenis        köpek     
2    Türk         kırmızı  ayran      lahmacun     güreş        kedi      
3    İsveçli      beyaz    su         köttbullar   buz hokeyi   balık     
4    Japon        yeşil    çay        sushi        judo         tavşan    
5    İtalyan      mavi     kahve      pizza        futbol       papağan   

--------------------------------------------------------------------------------
ÇÖZÜM 2:
--------------------------------------------------------------------------------
Ev   Millet       Renk     İçecek     Yemek        Spor         Hayvan    
--------------------------------------------------------------------------------
1    Brezilyalı   mavi     smoothie   feijoada     tenis        köpek     
2    Türk         kırmızı  ayran      lahmacun     güreş        kedi      
3    İsveçli      beyaz    su         köttbullar   buz hokeyi   balık     
4    Japon        yeşil    çay        sushi        judo         tavşan    
5    İtalyan      sarı     kahve      pizza        futbol       papağan   

========================================================
TÜM KISITLARIN KONTROLÜ (Her iki çözüm için de geçerli):
========================================================

1. ✓ Türk: kırmızı evde, ayran içiyor, lahmacun yiyor, güreş yapıyor, kedi besliyor.
2. ✓ Japon: yeşil evde, çay içiyor, sushi yiyor, judo yapıyor, tavşan besliyor.
3. ✓ İtalyan: pizza yiyor, futbol oynuyor, kahve içiyor, papağan besliyor.
4. ✓ Brezilyalı: feijoada yiyor, tenis oynuyor, smoothie içiyor, köpek besliyor.
5. ✓ İsveçli: köttbullar yiyor, buz hokeyi oynuyor, beyaz evde, su içiyor, balık besliyor.
6. ✓ Ortadaki evde (3. ev) su içiliyor.
7. ✓ Kedi, ayran içen kişinin (Türk) evinde yaşıyor.
8. ✓ Köpek (1. ev), ayran içen kişinin (2. ev) SOLUNDAKİ evde yaşıyor.
9. ✓ Papağan, kahve içen kişinin (İtalyan) evinde yaşıyor.
10.✓ Smoothie içen kişi (Brezilyalı), tenis oynuyor.

======
SONUÇ:
======

Zebra problemi başarıyla çözüldü!
2 adet geçerli çözüm bulundu.
Her iki çözüm de tüm 10 kısıtı sağlamaktadır.
Çözümler arasındaki tek fark: Brezilyalı ve İtalyan'ın renklerinin yer değiştirmesidir.

---

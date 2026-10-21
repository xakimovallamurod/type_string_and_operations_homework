# Satr turi va satrlar ustida amallar

## String01

Allamurodning ismini satr ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: 
Chiqarish: "Allamurod"
```

---

## String02

Allamurodning familiyasini faqat bosh harflar bilan yozilgan satr ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: 
Chiqarish: "XAKIMOV"
```

---

## String03

`=` belgisidan iborat va uzunligi 10 bo'lgan satrni `*` operatori yordamida qaytaring.

**Misol 1:**

```Python
Kirish: 
Chiqarish: "=========="
```

---

## String04

Ism berilgan. Uni ikkala tomondan qo'shtirnoq bilan o'rab qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod"
Chiqarish: "\"Allamurod\""
```

---

## String05

Ism va familiya berilgan. Ularni orasiga bo'sh joy qo'yib birlashtiring va qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: "Allamurod Xakimov"
```

---

## String06

Satr s va butun son n berilgan. Satrni n marta takrorlab qaytaring.

**Misol 1:**

```Python
Kirish: s="Ha", n=3
Chiqarish: "HaHaHa"
```

**Misol 2:**

```Python
Kirish: s="uz", n=2
Chiqarish: "uzuz"
```

---

## String07

Ism va familiya berilgan. Ulardan "familiya, ism" ko'rinishidagi satrni qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: "Xakimov, Allamurod"
```

---

## String08

Allamurodning yoshi butun son ko'rinishida berilgan. `str()` yordamida "Yoshim: <yosh>" satrini qaytaring.

**Misol 1:**

```Python
Kirish: yosh=26
Chiqarish: "Yoshim: 26"
```

---

## String09

Allamurodning yoshi, bo'yi (sm) va vazni (kg) — uchta butun son berilgan. Ularni "[x1, x2, x3]" ko'rinishidagi satrga aylantirib qaytaring.

**Misol 1:**

```Python
Kirish: x1=26, x2=178, x3=74
Chiqarish: "[26, 178, 74]"
```

---

## String10

Shahar nomi berilgan. "Men <shahar>da yashayman" satrini qaytaring.

**Misol 1:**

```Python
Kirish: shahar="Toshkent"
Chiqarish: "Men Toshkentda yashayman"
```

**Misol 2:**

```Python
Kirish: shahar="Samarqand"
Chiqarish: "Men Samarqandda yashayman"
```

---

## String11

Belgi, son n va matn berilgan. Matnning ikkala tomoniga belgini n martadan takrorlab qo'shing va qaytaring.

**Misol 1:**

```Python
Kirish: belgi="*", n=3, matn="Allamurod"
Chiqarish: "***Allamurod***"
```

**Misol 2:**

```Python
Kirish: belgi="-", n=2, matn="Python"
Chiqarish: "--Python--"
```

---

## String12

Ikki butun son x va y berilgan. "(x+y)*2=<javob>" ko'rinishidagi satrni qaytaring. Masalan, Allamurodning yoshi 26 va tajribasi 4 yil.

**Misol 1:**

```Python
Kirish: x=26, y=4
Chiqarish: "(26+4)*2=60"
```

**Misol 2:**

```Python
Kirish: x=1, y=2
Chiqarish: "(1+2)*2=6"
```

---

## String13

Ism, yosh va shahar berilgan. "Ism: <ism> | Yosh: <yosh> | Shahar: <shahar>" satrini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", yosh=26, shahar="Toshkent"
Chiqarish: "Ism: Allamurod | Yosh: 26 | Shahar: Toshkent"
```

---

## String14

Ism va tug'ilgan yil berilgan. Yoshni 2026-yil bo'yicha hisoblang va "<ism> <yil>-yilda tug'ilgan, hozir <yosh> yoshda" satrini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", yil=2000
Chiqarish: "Allamurod 2000-yilda tug'ilgan, hozir 26 yoshda"
```

---

## String15

Allamurod do'kondan bir xil mahsulot oldi. Narx va soni berilgan. Chek satrini qaytaring: "<soni> x <narx> = <jami> so'm".

**Misol 1:**

```Python
Kirish: narx=12000, soni=3
Chiqarish: "3 x 12000 = 36000 so'm"
```

---

## String16

Matn va uning uzunligi n berilgan. Matnni ramkaga oling: yuqori va pastki qator "+" + "-" * n + "+", o'rta qator "|" + matn + "|". Qatorlarni `\n` bilan ajratib, bitta satr qilib qaytaring.

**Misol 1:**

```Python
Kirish: matn="Python", n=6
Chiqarish: "+------+\n|Python|\n+------+"
```

---

## String17

Ikki butun son a va b berilgan. "<a> / <b> = <natija>" satrini qaytaring, natija `round()` yordamida 2 xona aniqlikda yaxlitlansin.

**Misol 1:**

```Python
Kirish: a=22, b=7
Chiqarish: "22 / 7 = 3.14"
```

**Misol 2:**

```Python
Kirish: a=10, b=4
Chiqarish: "10 / 4 = 2.5"
```

---

## String18

Allamurodning ismi va uchta fandan olgan bali berilgan. "<ism>: <b1> + <b2> + <b3> = <yig'indi>" satrini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", b1=87, b2=92, b3=78
Chiqarish: "Allamurod: 87 + 92 + 78 = 257"
```

---

## String19

Butun son son va n berilgan. Sonni satrga aylantiring, n marta takrorlang, so'ng yana butun songa aylantirib 2 ga ko'paytiring. Natijani son (int) ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: son=26, n=2
Chiqarish: 5252
```

**Misol 2:**

```Python
Kirish: son=7, n=3
Chiqarish: 1554
```

---

## String20

Ism, familiya, tug'ilgan yil va bo'y (sm) berilgan. Yoshni 2026-yil bo'yicha va bo'yni metrda hisoblang. "<ism> <familiya> | <yosh> yosh | <bo'y> m" satrini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov", yil=2000, boy_sm=178
Chiqarish: "Allamurod Xakimov | 26 yosh | 1.78 m"
```


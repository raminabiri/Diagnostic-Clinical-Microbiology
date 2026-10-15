# الگوریتم اصلی: باسیل‌های گرم مثبت

> **مسیریاب** از رنگ گرم تا ماژول خانواده. ⚠️ در شک به ***Bacillus anthracis*** (کلنی بزرگ غیرهمولیتیک، بی‌حرکت، چسبنده) پیش از هر آزمون دیگر ← **توقف و BSC** ← [ماژول ۱۵](../../15_Aerobic_GPB/README.md).

```mermaid
flowchart TD
A[باسیل گرم مثبت] --> B{اسید–فست؟<br/>ZN یا اورامین}
B -->|مثبت| M[مایکوباکتری‌ها<br/>ماژول 23]
B -->|منفی| C{اسید–فست اصلاح‌شده<br/>اگر رشته‌ای منشعب}
C -->|مثبت| N[Nocardia، Rhodococcus، Gordonia<br/>ماژول 15]
C -->|منفی یا غیرمنشعب| D{رشد هوازی؟}
D -->|فقط بی‌هوازی| E{اسپور}
E -->|+| E1[Clostridium<br/>ماژول 22]
E -->|−| E2[Actinomyces، Cutibacterium، Eggerthella<br/>ماژول 22]
D -->|بله| F{اسپور و اندازه}
F -->|باسیل بزرگ اسپوردار| F1[Bacillus<br/>ماژول 15]
F -->|بدون اسپور| G{کاتالاز}
G -->|مثبت| H{شکل و حرکت}
H -->|کورینه‌فرم، چینی| H1[Corynebacterium<br/>ماژول 15]
H -->|کوتاه، حرکت غلتان در 25 درجه| H2[Listeria<br/>ماژول 15]
G -->|منفی| I{H2S در TSI}
I -->|+| I1[Erysipelothrix<br/>ماژول 15]
I -->|−| I2[Arcanobacterium، Lactobacillus، Gardnerella<br/>ماژول 15]
```

## نقاط تصمیم کلیدی
| گام | نکته | ارجاع |
|---|---|---|
| **اسید–فست کامل در برابر اصلاح‌شده** | مایکوباکتری‌ها با ZN؛ *Nocardia* فقط با رنگ‌بر ضعیف (H₂SO₄ ۱٪) | [12/01 بخش ۱.۲](../../12_Identification_Tests/01_Microscopy_Stains.md) |
| **هوازی‌تحملی** | *C. tertium* در هوا رشد می‌کند (بدون اسپور، **کاتالاز −**)؛ *Actinomyces*، *Cutibacterium* اغلب در CO₂ | [12/03 بخش ۳.۸](../../12_Identification_Tests/03_Disk_and_Growth_Tests.md) |
| **گرم‌متغیر بودن** | *Clostridium ramosum* و برخی *Bacillus* گرم منفی دیده می‌شوند ← **دیسک ونکومایسین ۵ µg** ([12/03 بخش ۳.۴](../../12_Identification_Tests/03_Disk_and_Growth_Tests.md)) یا **KOH ۳٪** ([12/01 بخش ۱.۳](../../12_Identification_Tests/01_Microscopy_Stains.md)) | |
| **«دیفتروئید» در نمونهٔ استریل** | ممکن است *Listeria* (CSF، بارداری) یا *C. jeikeium* (کاتتر) باشد | [ماژول ۱۵](../../15_Aerobic_GPB/03_Pitfalls_and_Reporting.md) |

## ماژول‌های مقصد
- [15_Aerobic_GPB](../../15_Aerobic_GPB/README.md) · [22_Anaerobes](../../22_Anaerobes/README.md) · [23_Mycobacteria](../../23_Mycobacteria/README.md)
- آنتی‌بیوگرام: CLSI **M45** و **M24** ← [AST/05](../../AST/05_Fastidious_Anaerobes/README.md) · [AST/06](../../AST/06_Mycobacteria/01_Mycobacteria_AST.md)

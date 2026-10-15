# الگوریتم اصلی: کوکسی‌های گرم مثبت

> **مسیریاب** است، نه شناسایی کامل: از رنگ گرم و چند تست اولیه به **ماژول خانوادهٔ درست** می‌رسد. جدول‌ها، دام‌ها و گزارش‌دهی در خود ماژول‌ها است.

```mermaid
flowchart TD
A[کوکسی گرم مثبت] --> B{رشد هوازی یا در CO2؟}
B -->|فقط بی‌هوازی| Z[کوکسی گرم مثبت بی‌هوازی<br/>Finegoldia، Parvimonas، Peptostreptococcus<br/>ماژول 22]
B -->|بله| C{کاتالاز<br/>از کلنی، نه از آگار خون}
C -->|مثبت| D{آرایش و کلنی}
D -->|خوشه‌ای| D1[Staphylococcus<br/>ماژول 13]
D -->|تتراد، کلنی زرد خشک| D2[Micrococcus، Kocuria<br/>ماژول 13]
D -->|چسبنده، کاتالاز ضعیف| D3[Rothia mucilaginosa<br/>ماژول 13]
C -->|منفی| E{همولیز روی آگار خون}
E -->|β| F[استرپتوکوک β-همولیتیک<br/>لانسفیلد، PYR<br/>ماژول 14]
E -->|α| G{اپتوچین یا حلالیت صفرا}
G -->|حساس یا محلول| G1[S. pneumoniae<br/>ماژول 14]
G -->|مقاوم| G2[ویریدانس، Enterococcus، Aerococcus، NVS<br/>ماژول 14]
E -->|γ| H{BEA و NaCl 6.5%}
H -->|هر دو +| H1[Enterococcus<br/>ماژول 14]
H -->|BEA + ، NaCl −| H2[گروه S. bovis<br/>ماژول 14]
H -->|رشد فقط اطراف S. aureus| H3[Abiotrophia، Granulicatella<br/>ماژول 14]
```

## نقاط تصمیم کلیدی
| گام | چرا مهم است | ارجاع |
|---|---|---|
| **کاتالاز** | استاف/میکروکوک را از استرپ/انتروکوک جدا می‌کند؛ کاتالاز از آگار خون **مثبت کاذب** می‌دهد | [12/02 بخش ۲.۱](../../12_Identification_Tests/02_Spot_Rapid_Tests.md) |
| **هوازی‌تحملی** | کوکسی‌های بی‌هوازی در کشت هوازی رشد نمی‌کنند | [12/03 بخش ۳.۸](../../12_Identification_Tests/03_Disk_and_Growth_Tests.md) |
| **همولیز** | β ← استرپ‌های پیوژن؛ α ← پنوموکوک/ویریدانس؛ γ ← انتروکوک | [11/01](../../11_Culture_Media/01_Basic_Enriched.md) |
| **کوکوباسیل کاتالاز + در زنجیره** | ممکن است ***Listeria*** باشد، نه استرپ | [ماژول ۱۵](../../15_Aerobic_GPB/README.md) |

## ماژول‌های مقصد
- [13_GPC_Catalase_Positive](../../13_GPC_Catalase_Positive/README.md) · [14_GPC_Catalase_Negative](../../14_GPC_Catalase_Negative/README.md) · [22_Anaerobes](../../22_Anaerobes/README.md)
- آنتی‌بیوگرام: [AST/03_Other_Resistance](../../AST/03_Other_Resistance/README.md)

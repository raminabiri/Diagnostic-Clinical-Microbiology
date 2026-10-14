# فلوچارت‌های تشخیصی: کوکسی‌های گرم مثبت کاتالاز منفی

## فلوچارت ۱: بر اساس همولیز

```mermaid
flowchart TD
A[کوکسی گرم مثبت زنجیره یا جفت<br/>کاتالاز منفی] --> B{همولیز روی آگار خون گوسفند}
B -->|β| C{اندازهٔ کلنی}
C -->|ریز کمتر از 0.5mm<br/>بوی کارامل| C1[S. anginosus group<br/>VP + ; MALDI-TOF]
C -->|بزرگ| D{PYR}
D -->|+| D1[S. pyogenes<br/>تأیید: لانسفیلد A]
D -->|−| E{CAMP یا هیپورات}
E -->|+| E1[S. agalactiae<br/>تأیید: لانسفیلد B]
E -->|−| E2[لانسفیلد C یا G<br/>SDSE / S. equi]
B -->|α| F{اپتوچین 5µg}
F -->|S ≥14mm| F1[S. pneumoniae]
F -->|R یا هالهٔ مرزی| G{حلالیت صفرا}
G -->|+| F1
G -->|−| H{BEA و NaCl 6.5%}
B -->|γ| H
H -->|BEA + و NaCl +| H1[Enterococcus<br/>PYR + ; گونه: تحرک، رنگدانه، MALDI]
H -->|BEA + و NaCl −| H2[S. bovis / gallolyticus group<br/>PYR −]
H -->|BEA − و NaCl −| H3[ویریدانس<br/>یا NVS، Gemella<br/>MALDI-TOF]
H -->|BEA − و NaCl +| H4[Aerococcus / Globicatella<br/>PYR و LAP]
```

### منطق شاخه‌ها
1. **همولیز** اولین شاخه است، ولی کافی نیست: GBS غیرهمولیتیک، انتروکوک β‌همولیتیک، پنوموکوک گاه γ در محیط بی‌هوازی.
2. در β: **اندازهٔ کلنی** پیش از لانسفیلد؛ کلنی ریز با آنتی‌ژن A = *S. anginosus* group، **نه GAS**.
3. در α: **اپتوچین** غربالگری؛ هالهٔ مرزی (به‌ویژه در CO₂) ← **حلالیت صفرا** (قطعی‌تر).
4. **BEA + NaCl ۶٫۵٪ + PYR** سه تست ارزان برای جدا کردن انتروکوک از *S. bovis* (ارتباط با سرطان کولون).

---

## فلوچارت ۲: کوکسی گرم مثبت کاتالاز منفی **مقاوم به ونکومایسین**

```mermaid
flowchart TD
A[کوکسی گرم مثبت کاتالاز منفی<br/>ونکومایسین R یا رشد روی آگار VRE] --> B{BEA + و NaCl +<br/>PYR +}
B -->|بله| C{تحرک و رنگدانه}
C -->|متحرک ± زرد| C1[E. gallinarum / E. casseliflavus<br/>vanC: VRE محسوب نمی‌شود]
C -->|بی‌حرکت| C2[E. faecium / E. faecalis<br/>VRE: MIC + PCR vanA/vanB<br/>کنترل عفونت]
B -->|خیر| D{مورفولوژی و LAP}
D -->|کوکوباسیل، گاز از گلوکز، LAP −| D1[Leuconostoc / Weissella]
D -->|تتراد، LAP +| D2[Pediococcus]
D -->|باسیل یا کوکوباسیل| D3[Lactobacillus]
D1 --> E[مقاومت ذاتی به ونکومایسین<br/>VRE نیست]
D2 --> E
D3 --> E
```

---

## فلوچارت ۳: اقمار و استرپتوکوک‌های نیازمند تغذیه (NVS)

```mermaid
flowchart TD
A[کشت خون مثبت: کوکسی گرم مثبت زنجیره<br/>رشد در بطری، عدم رشد یا رشد ضعیف روی آگار خون] --> B[زیرکشت روی آگار خون + خط S. aureus<br/>و آگار شکلات]
B --> C{رشد اقماری اطراف S. aureus<br/>یا فقط روی شکلات؟}
C -->|بله| D[Abiotrophia / Granulicatella<br/>PYR + ; MALDI-TOF]
D --> E[AST: CLSI M45 با CAMHB-LHB + پیریدوکسال<br/>اطلاع: احتمال اندوکاردیت کشت‌منفی]
C -->|خیر| F[سایر ارگانیسم‌های سخت‌رشد<br/>H. influenzae در صورت گرم منفی]
```

# فلوچارت‌های تشخیصی: باسیل‌های گرم منفی غیرتخمیری

## فلوچارت ۱: از K/K تا جنس

```mermaid
flowchart TD
A[باسیل یا کوکوباسیل گرم منفی<br/>TSI یا KIA: K/K] --> B{اکسیداز}
B -->|منفی| C{تحرک و شکل}
C -->|بی‌حرکت، کوکوباسیل| C1[Acinetobacter<br/>نیترات −، رشد 44 درجه: A. baumannii]
C -->|متحرک، باسیل| C2{DNase و مالتوز}
C2 -->|DNase + ، مالتوز قوی| C3[S. maltophilia<br/>LDC +، کلنی اسطوخودوسی]
C2 -->|منفی| C4[سایر: B. gladioli، Pseudomonas oryzihabitans<br/>MALDI-TOF]
B -->|مثبت یا ضعیف| D{رنگدانه یا بوی انگور}
D -->|آبی-سبز، بوی انگور| D1[P. aeruginosa<br/>رشد 42 درجه، استامید +]
D -->|فقط فلورسانس| D2[P. fluorescens یا P. putida<br/>42 درجه منفی]
D -->|زرد یا نارنجی| D3{ایندول}
D3 -->|+| D4[Elizabethkingia یا Chryseobacterium]
D3 -->|−| D5[Sphingomonas یا BCC<br/>MALDI-TOF]
D -->|بدون رنگدانه| E{کلنی خشک چروکیده، جنتامایسین و کولیستین R؟}
E -->|بله| E1[مشکوک به B. pseudomallei<br/>توقف، BSC، ارجاع]
E -->|خیر| F{OF گلوکز}
F -->|اکسیداتیو| F1[BCC، Achromobacter، P. stutzeri، Ralstonia<br/>MALDI-TOF]
F -->|غیرواکنش‌گر| F2[Alcaligenes، Moraxella غیر catarrhalis<br/>H2S + : Shewanella]
```

### منطق شاخه‌ها
- **K/K** باید پیش از هر چیز تأیید شود؛ اکسیداز + و K/A یعنی تخمیرکننده ← [18](../18_Oxidase_Positive_Fermenters/README.md).
- ***Acinetobacter*** تنها غیرتخمیری شایع **اکسیداز منفی و بی‌حرکت** است؛ کوکوباسیل‌های آن در رنگ گرم ممکن است **دیپلوکوک** یا حتی **گرم مثبت** دیده شوند.
- **B. pseudomallei** را قبل از استفاده از سیستم خودکار یا MALDI-TOF در نظر بگیرید (سابقهٔ سفر یا زندگی در مناطق آندمیک، دیابت).

## فلوچارت ۲: خلط بیمار فیبروز کیستیک (CF)

```mermaid
flowchart TD
A[خلط CF] --> B[آگار خون، شکلات، MacConkey<br/>BCSA تا 5 روز، مانیتول سالت]
B --> C{کلنی روی BCSA}
C -->|رشد| D[MALDI-TOF با پایگاه به‌روز]
D -->|BCC| D1[گزارش: B. cepacia complex<br/>ارسال به آزمایشگاه مرجع CF برای گونه با recA<br/>اطلاع به کنترل عفونت]
D -->|Achromobacter، Ralstonia، Pandoraea، Stenotrophomonas| D2[گزارش در سطح جنس یا گروه<br/>ممکن است با BCC اشتباه شوند]
C -->|بدون رشد| E[P. aeruginosa و S. aureus از سایر محیط‌ها]
E --> E1[P. aeruginosa موکوئید یا SCV:<br/>همهٔ مورفوتیپ‌ها جداگانه AST]
```

## فلوچارت ۳: مسیر AST

```mermaid
flowchart TD
A[غیرتخمیری از نمونهٔ معنی‌دار] --> B{ارگانیسم}
B -->|P. aeruginosa| C{همهٔ بتالاکتام‌ها و FQ غیرحساس؟}
C -->|بله، DTR-PA| C1[AST: C/T، CZA، IMR، سفیدروکول<br/>آزمون کارباپنماز: mCIM یا مولکولی]
C -->|خیر| C2[گزارش طبق Cascade]
B -->|A. baumannii complex| D{کارباپنم غیرحساس؟}
D -->|بله، CRAB| D1[AST: سولباکتام–دورلوباکتام، مینوسایکلین<br/>سفیدروکول، کولیستین با BMD<br/>PCR OXA-23، 24، 58]
D -->|خیر| D2[گزارش طبق Cascade]
B -->|S. maltophilia| E[فقط TMP-SMX، لووفلوکساسین، مینوسایکلین، سفیدروکول<br/>کارباپنم‌ها: R ذاتی، گزارش نشود]
B -->|BCC| F[CLSI Ed36: نقطهٔ برش حذف شده است<br/>AST روتین انجام نشود، با یادداشت گزارش]
B -->|سایر| G[CLSI M100 Table 2B-5 یا گزارش MIC بدون تفسیر]
```

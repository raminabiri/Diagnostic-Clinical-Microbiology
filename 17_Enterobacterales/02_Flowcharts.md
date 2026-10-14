# فلوچارت‌های تشخیصی: Enterobacterales

## فلوچارت ۱: از باسیل گرم منفی تا گروه

```mermaid
flowchart TD
A[باسیل گرم منفی روی آگار خون و MacConkey] --> B{اکسیداز}
B -->|مثبت| B1[Vibrio، Aeromonas، Plesiomonas<br/>یا غیرتخمیری ← ماژول 18 و 19]
B -->|منفی| C{TSI یا KIA}
C -->|K/K یا K/NC| C1[غیرتخمیری اکسیداز منفی<br/>Acinetobacter، Stenotrophomonas ← ماژول 19]
C -->|K/A یا A/A| D[Enterobacterales<br/>MALDI-TOF یا سیستم بیوشیمیایی]
D --> E{لاکتوز روی MacConkey}
E -->|تخمیرکننده| F[E. coli، Klebsiella، Enterobacter<br/>Citrobacter گاه]
E -->|غیرتخمیرکننده| G{اوره‌آز سریع و PAD}
G -->|هر دو مثبت| G1[Proteeae<br/>Proteus، Morganella، Providencia]
G -->|منفی| H[Salmonella، Shigella، Serratia<br/>Yersinia، Hafnia، Citrobacter]
```

## فلوچارت ۲: تخمیرکنندگان لاکتوز

```mermaid
flowchart TD
A[Enterobacterales، لاکتوز مثبت] --> B{ایندول اسپات}
B -->|مثبت| C{سیترات}
C -->|منفی| C1[E. coli<br/>کلنی صاف، همولیز گاه]
C -->|مثبت| C2[K. oxytoca یا C. koseri<br/>VP: K. oxytoca +]
B -->|منفی| D{تحرک}
D -->|بی‌حرکت| D1[K. pneumoniae<br/>کلنی موکوئید، VP +، اوره w]
D -->|متحرک| E{LDC و ADH}
E -->|LDC + ، ADH −| E1[K. aerogenes]
E -->|LDC − ، ADH +| E2[E. cloacae complex]
E -->|LDC − ، H2S +| E3[C. freundii]
```

## فلوچارت ۳: غیرتخمیرکنندگان لاکتوز و پاتوژن‌های روده‌ای

```mermaid
flowchart TD
A[کلنی لاکتوز منفی از XLD، HE یا MacConkey] --> B[غربالگری: TSI، LIA، اوره‌آز، تحرک]
B --> C{اوره‌آز}
C -->|مثبت سریع| C1[Proteeae یا Y. enterocolitica<br/>کنار گذاشتن برای پاتوژن روده‌ای به‌جز Yersinia]
C -->|منفی| D{TSI H2S و LIA}
D -->|TSI K/A H2S + ، LIA K/K| E[مشکوک به Salmonella]
E --> E1[آنتی‌سرم O پلی‌والان و Vi<br/>سپس گروه O]
E1 --> E2[گزارش اولیه: Salmonella سروگروه ...<br/>ارسال به آزمایشگاه مرجع]
D -->|TSI K/A بدون گاز و H2S ، LIA K/A ، بی‌حرکت| F[مشکوک به Shigella]
F --> F1[آنتی‌سرم A، B، C، D<br/>رد E. coli غیرفعال: استات، موکات]
F1 --> F2[گزارش Shigella سروگروه ...<br/>AST و اطلاع به بهداشت]
D -->|TSI K/A بدون H2S ، تحرک 25 +| G[Yersinia یا Hafnia<br/>MALDI-TOF]
```

### منطق شاخه‌ها
- **اوره‌آز اول** در مدفوع: *Proteus* (کلنی H₂S + روی XLD/HE) شایع‌ترین «شبه‌*Salmonella*» است؛ اوره‌آز سریع آن را حذف می‌کند.
- **LIA:** *Salmonella* لیزین + (K/K) و *Proteus* دآمیناز + (R/A) است.
- **MALDI-TOF** *Salmonella* را تا جنس شناسایی می‌کند ولی **سروتیپ نمی‌دهد**؛ *Shigella* را از *E. coli* **جدا نمی‌کند**.
- سرولوژی **روی کلنی از محیط غیرانتخابی** (آگار خون یا TSI شیب) انجام شود.

## فلوچارت ۴: کشت خون یا ادرار با Enterobacterales ← مسیر AST

```mermaid
flowchart TD
A[Enterobacterales از خون یا ادرار] --> B[ID و AST روتین]
B --> C{سفالوسپورین نسل 3 غیرحساس؟}
C -->|بله| D{ارگانیسم با AmpC کروموزومی؟<br/>Enterobacter، K. aerogenes، C. freundii}
D -->|خیر| D1[احتمال ESBL<br/>تأیید فقط اگر سیاست آزمایشگاه بخواهد]
D -->|بله| D2[احتمال AmpC<br/>پیام درمانی IDSA]
C -->|خیر| E{کارباپنم غیرحساس یا MIC بالا؟}
D1 --> E
D2 --> E
E -->|بله| F[Carba NP یا mCIM و eCIM<br/>یا آزمون مولکولی یا ایمونوکروماتوگرافی]
F --> F1[نوع کارباپنماز: KPC، NDM، OXA-48، VIM، IMP<br/>اطلاع به کنترل عفونت]
E -->|خیر| G[گزارش طبق قواعد Cascade]
```

> جزئیات: [ESBL](../AST/02_Beta_Lactamases/03_ESBL.md) · [AmpC](../AST/02_Beta_Lactamases/04_AmpC.md) · [کارباپنمازها](../AST/02_Beta_Lactamases/05_Carbapenemases.md) · [انتخاب و گزارش](../AST/00_Principles/03_Selection_and_Reporting.md).

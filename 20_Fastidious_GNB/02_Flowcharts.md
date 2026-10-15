# فلوچارت‌های تشخیصی: گرم منفی‌های سخت‌رشد

## فلوچارت ۱: کوکوباسیل گرم منفی که روی MacConkey رشد نمی‌کند

```mermaid
flowchart TD
A[کوکوباسیل یا باسیل گرم منفی<br/>رشد روی شکلات یا آگار خون، نه MacConkey] --> B{کلنی ریز و کند، 48 تا 72 ساعت<br/>کوکوباسیل بسیار ریز؟}
B -->|بله| S[توقف کار باز، BSC<br/>بررسی Brucella و Francisella<br/>فلوچارت 3]
B -->|خیر| C{رشد روی آگار خون}
C -->|فقط روی شکلات یا اقمار| H[Haemophilus<br/>X، V، پورفیرین]
C -->|رشد دارد| D{کاتالاز}
D -->|منفی| E{اکسیداز}
E -->|+ ، pitting، بوی کلر| E1[Eikenella corrodens]
E -->|+ ، β-همولیز باریک| E2[Kingella kingae]
E -->|+ ، ایندول + ، روزت| E3[Cardiobacterium hominis]
E -->|w یا −| E4[A. aphrophilus]
D -->|مثبت| F{اکسیداز}
F -->|+ ، باسیل دوکی، لبهٔ لغزشی| F1[C. canimorsus<br/>سابقهٔ سگ، اسپلنکتومی]
F -->|+ ، ایندول +| F2[Pasteurella ← ماژول 18]
F -->|w یا − ، کلنی ستاره‌ای چسبنده| F3[A. actinomycetemcomitans]
```

### منطق شاخه‌ها
- **ایمنی اول:** پیش از هر آزمون، الگوی «کوکوباسیل ریز + رشد کند + MacConkey منفی» را بسنجید.
- **کاتالاز** HACEK را دو نیم می‌کند: *Cardiobacterium*، *Eikenella*، *Kingella*، *A. aphrophilus* منفی؛ *A. actinomycetemcomitans* مثبت.
- **MALDI-TOF** برای HACEK و *Capnocytophaga* معمولاً خوب است؛ برای *Brucella*/*Francisella* استفاده نشود.

## فلوچارت ۲: *Haemophilus*

```mermaid
flowchart TD
A[کوکوباسیل گرم منفی پلئومورف<br/>رشد روی شکلات، نه آگار خون] --> B{پورفیرین ALA}
B -->|منفی، نیاز X دارد| C{همولیز روی خون اسب}
C -->|منفی| C1[H. influenzae<br/>جدایهٔ تهاجمی: سروتایپ یا PCR کپسول]
C -->|مثبت| C2[H. haemolyticus<br/>فلور]
B -->|مثبت، نیاز X ندارد| D{همولیز}
D -->|منفی| D1[H. parainfluenzae]
D -->|مثبت| D2[H. parahaemolyticus]
C1 --> E[نیتروسفین و AST طبق CLSI Table 2E<br/>BLNAR را در نظر بگیرید]
```

## فلوچارت ۳: شک به *Brucella* یا *Francisella* ☣️

```mermaid
flowchart TD
A[کوکوباسیل گرم منفی ریز، رشد کند<br/>MacConkey منفی] --> B[همهٔ کار بعدی در BSC<br/>بدون MALDI-TOF، بدون سیستم خودکار<br/>پلیت‌ها با چسب بسته شوند]
B --> C{اکسیداز و اوره‌آز}
C -->|اکسیداز + ، اوره‌آز سریع +| D[Brucella رد نشده است]
C -->|اکسیداز − ، کاتالاز w| E[Francisella رد نشده است]
C -->|الگوی دیگر| F[Haemophilus، Psychrobacter و ...<br/>با احتیاط ادامه]
D --> G[اطلاع به مدیر آزمایشگاه و پزشک<br/>ارسال به آزمایشگاه مرجع]
E --> G
G --> H[ارزیابی مواجههٔ کارکنان<br/>پیگیری طبق دستورالعمل]
```

# میکروب‌شناسی بالینی تشخیصی (Diagnostic Clinical Microbiology)

راهنمای آموزشی **فارسی** برای **دستیاران و کارشناسان میکروب‌شناسی پزشکی**، از سطح پایه تا پیشرفته؛ بر پایهٔ روند واقعی کار در آزمایشگاه بالینی. دامنهٔ فعلی: **باکتری‌ها**.

> *A Persian-language teaching handbook of diagnostic clinical bacteriology for microbiology residents: specimen workflows, a media and test library, organism-family identification modules with Mermaid flowcharts and case scenarios, and an AST section aligned with CLSI M100-Ed36, EUCAST v16.1 and IDSA 2026.*

## ساختار

| بخش | محتوا | از کجا شروع کنیم؟ |
|---|---|---|
| **[01](01_Blood_Culture/README.md)–[09](09_Sterile_Fluids_and_Other/README.md)** — ماژول‌های **نمونه** | کشت خون، ادرار، CSF، گوارش، تناسلی، تنفسی، پوست و بافت نرم، زخم و بافت، مایعات استریل؛ هر کدام: تئوری، پروتکل (نمونه‌گیری تا گزارش، QC، عیب‌یابی)، آنتی‌بیوگرام، ۲۰ سناریو | «این نمونه را چطور کار کنم؟» |
| **[10](10_Quality_Control/README.md)** — **کنترل کیفی** | چارچوب QC، فهرست یکپارچهٔ سویه‌های QC، تجهیزات، شاخص‌ها، EQA | «QC آزمایشگاه» |
| **[11](11_Culture_Media/README.md)** — **محیط‌های کشت** | هر محیط **یک بار**، به ترتیب استفاده در روند کار | «این محیط چیست؟» |
| **[12](12_Identification_Tests/README.md)** — **تست‌های شناسایی** | رنگ‌آمیزی، تست‌های سریع، دیسک‌ها، سرولوژی، سیستم‌ها (MALDI-TOF)، **مولکولی جدا** | «این تست چطور انجام و تفسیر می‌شود؟» |
| **[13](13_GPC_Catalase_Positive/README.md)–[24](24_Non_Culturable/README.md)** — ماژول‌های **خانواده** | جدول‌های افتراقی، فلوچارت‌ها، دام‌ها و گزارش‌دهی، ۱۰ سناریو | «این کلنی چیست؟» |
| **[AST](AST/README.md)** | اصول، روش‌های فنوتیپی، بتالاکتامازها، سایر مقاومت‌ها، نقاط برش، QC، پیوند با درمان | «آنتی‌بیوگرام را چطور انجام و گزارش کنم؟» |
| **[Shared](Shared/README.md)** | **[الگوریتم‌های اصلی](Shared/Algorithms/README.md)** (از رنگ گرم تا ماژول خانواده)، واژه‌نامه، الگوها | کلنی ناشناخته ← از این‌جا |

### ماژول‌های خانواده
| # | خانواده | # | خانواده |
|---|---|---|---|
| [13](13_GPC_Catalase_Positive/README.md) | کوکسی گرم مثبت کاتالاز + | [19](19_Non_Fermenters/README.md) | غیرتخمیری‌ها |
| [14](14_GPC_Catalase_Negative/README.md) | کوکسی گرم مثبت کاتالاز − | [20](20_Fastidious_GNB/README.md) | گرم منفی‌های سخت‌رشد |
| [15](15_Aerobic_GPB/README.md) | باسیل گرم مثبت هوازی | [21](21_Curved_GNB/README.md) | باسیل‌های خمیده |
| [16](16_Gram_Negative_Cocci/README.md) | کوکسی گرم منفی | [22](22_Anaerobes/README.md) | بی‌هوازی‌ها |
| [17](17_Enterobacterales/README.md) | Enterobacterales | [23](23_Mycobacteria/README.md) | مایکوباکتری‌ها |
| [18](18_Oxidase_Positive_Fermenters/README.md) | تخمیرکنندگان اکسیداز + | [24](24_Non_Culturable/README.md) | غیرقابل‌کشت‌ها (کلامیدیا، مایکوپلاسما، اسپیروکت‌ها، ریکتزیا) |

## اصول طراحی
- **هر روش یک بار:** هر محیط، تست و موضوع AST فقط در یک جا شرح داده می‌شود و بقیه به آن **پیوند** می‌دهند.
- **روند واقعی کار:** از نمونه ← رنگ گرم ← کشت ← شناسایی ← AST ← گزارش.
- **فلوچارت‌ها با Mermaid** (مستقیم روی GitHub نمایش داده می‌شوند).
- **سناریوهای آزمایشگاهی** با پاسخ تشریحی در پایان هر ماژول.

## مبانی و استانداردها
- **CLSI M100-Ed36 (2026)**، **EUCAST v16.1**، **IDSA 2026** (درمان عفونت‌های گرم منفی مقاوم)؛ CLSI M22، M45، M24، M47، M48.
- *Manual of Clinical Microbiology* (13th ed.)، *Koneman's* (7th ed.)، *Bailey & Scott's* (15th ed.)، *Clinical Microbiology Procedures Handbook* (ASM)، ASM Sentinel Level Guidelines، رهنمودهای WHO.
- اعداد AST با متن **CLSI M100-Ed36**، جدول **EUCAST v16.1** و سند **IDSA 2026** تطبیق داده شده‌اند. مواردی که با سند اصلی بررسی **نشده‌اند** (مثلاً بخش‌هایی از M24S، M45، WHO) در خود فایل **علامت‌گذاری** شده‌اند.

## ⚠️ هشدار
- این مخزن **آموزشی** است و جایگزین **دستورالعمل‌های رسمی، IFU سازندگان و نسخهٔ جاری استانداردها** نیست. پیش از کاربرد بالینی، هر عدد و روش را با نسخهٔ جاری منبع تطبیق دهید.
- متن اسناد دارای حق نشر (CLSI و …) **بازنشر نشده** است؛ محتوا خلاصه و بازنویسی شده و شمارهٔ جدول‌ها ذکر شده است.
- در بخش‌های مربوط به عوامل خطرناک (*B. anthracis*، *Brucella*، *Francisella*، *Y. pestis*، *B. pseudomallei*)، فقط اقدامات **رد تشخیص و ارجاع** آزمایشگاه سنتینل آمده است.

## وضعیت
همهٔ ماژول‌های ۰۱ تا ۲۴ و بخش AST نوشته شده‌اند. در حال تکمیل: فایل‌های «مرجع ایران» آنتی‌بیوگرام (`03_Antibiogram/04_Iran_Reference.md`) و بازبینی اعداد علامت‌گذاری‌شده. برای مشارکت ← [CONTRIBUTING.md](CONTRIBUTING.md)؛ برای ارجاع ← [CITATION.cff](CITATION.cff).

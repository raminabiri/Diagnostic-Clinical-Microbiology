# Urine Microbiology and Urinary Tract Infection Education

<div dir="rtl">

# میکروب‌شناسی ادرار و آموزش تشخیص آزمایشگاهی عفونت‌های ادراری

این بخش از پروژه **Clinical Practical Microbiology Education** یک منبع آموزشی ساختاریافته برای آموزش تشخیص آزمایشگاهی عفونت‌های ادراری (*Urinary Tract Infections; UTIs*) است.

محتوا از مرحله دریافت نمونه تا تفسیر نهایی کشت و آنتی‌بیوگرام را پوشش می‌دهد و برای دانشجویان علوم آزمایشگاهی، میکروب‌شناسی، پاتوبیولوژی، پزشکی، کارآموزان آزمایشگاه و مدرسین طراحی شده است.

> **Educational use only — فقط برای اهداف آموزشی**  
> این محتوا جایگزین SOP رسمی آزمایشگاه، استانداردهای جاری CLSI یا EUCAST، کنترل کیفیت داخلی، مسئول فنی آزمایشگاه یا تصمیم‌گیری درمانی پزشک نیست.

</div>

---

## Table of Contents

- [Scope](#scope)
- [Learning Objectives](#learning-objectives)
- [Educational Structure](#educational-structure)
- [Repository Structure](#repository-structure)
- [Protocols](#protocols)
- [Reference Tables](#reference-tables)
- [Case Studies](#case-studies)
- [Assessments](#assessments)
- [Assets and Images](#assets-and-images)
- [Antibiogram and AST](#antibiogram-and-ast)
- [Recommended Learning Path](#recommended-learning-path)
- [For Instructors](#for-instructors)
- [For Students](#for-students)
- [Standards and Interpretation](#standards-and-interpretation)
- [Safety and Limitations](#safety-and-limitations)
- [Version Control](#version-control)
- [Citation and License](#citation-and-license)
- [Contributing](#contributing)

---

## Scope

<div dir="rtl">

این بخش بر **میکروب‌شناسی بالینی ادرار** متمرکز است، نه آنالیز کامل بالینی/بیوشیمیایی ادرار.

موضوعات اصلی شامل موارد زیر هستند:

- پاتوفیزیولوژی و طبقه‌بندی عفونت‌های ادراری
- نمونه‌گیری ادرار برای کشت میکروبی
- حمل، نگهداری، پذیرش و رد نمونه
- بررسی مستقیم نمونه و رنگ‌آمیزی گرم
- نقش محدود دیپ‌استیک در تشخیص میکروب‌شناسی UTI
- کشت کمی ادرار با لوپ کالیبره
- شمارش کلنی و محاسبه CFU/mL
- شناسایی اولیه ارگانیسم‌های شایع ادراری
- تمایز آلودگی، کلونیزاسیون، باکتریوری بدون علامت و UTI واقعی
- انتخاب پنل آنتی‌بیوگرام بر اساس ارگانیسم و محل عفونت
- اصول گزارش‌دهی میکروب‌شناسی
- سناریوهای آموزشی، سوالات تشریحی و ارزیابی مهارت عملی

</div>

### خارج از محدوده اصلی

<div dir="rtl">

این بخش به‌صورت محدود به موارد زیر اشاره می‌کند، اما هدف اصلی آن‌ها نیست:

- بیماری‌های گلومرولی
- تفسیر کامل پروتئینوری
- دیابت و گلوکز ادرار
- کتواسیدوز
- بیماری‌های کبدی
- کریستال‌ها و سنگ‌شناسی غیرعفونی
- تفسیر نفرولوژی یا اورولوژی غیرمیکروبی

برای پروژه حاضر، دیپ‌استیک عمدتاً از نظر دو شاخص **Leukocyte esterase** و **Nitrite** در ارتباط با عفونت ادراری بررسی می‌شود.

</div>

---

## Learning Objectives

<div dir="rtl">

پس از تکمیل این بخش، فراگیر باید بتواند:

1. روش مناسب نمونه‌گیری ادرار را بر اساس شرایط بیمار انتخاب کند.
2. تفاوت نمونه MSU، نمونه کاتتر، سوپراپوبیک آسپیراسیون و نمونه کیسه‌ای کودک را بیان کند.
3. معیارهای پذیرش، رد یا درخواست تکرار نمونه ادرار را تعیین کند.
4. اهمیت زمان انتقال، نگهداری در دمای مناسب و استفاده از ظرف استریل را توضیح دهد.
5. یافته‌های لام مستقیم و رنگ‌آمیزی گرم ادرار را تفسیر کند.
6. ارتباط LE و Nitrite را با احتمال UTI توضیح دهد.
7. کشت کمی ادرار را با لوپ کالیبره انجام دهد.
8. CFU/mL را از تعداد کلنی محاسبه کند.
9. رشد خالص، رشد مختلط، آلودگی نمونه و کلونیزاسیون را از یکدیگر تفکیک کند.
10. ارگانیسم‌های رایج ادراری مانند *Escherichia coli*، *Klebsiella pneumoniae*، *Proteus mirabilis*، *Enterococcus spp.*، *Pseudomonas aeruginosa* و *Staphylococcus saprophyticus* را در سطح اولیه شناسایی کند.
11. پنل آنتی‌بیوگرام را بر پایه گروه یا گونه باکتری انتخاب کند.
12. محدودیت گزارش داروهای صرفاً ادراری، مانند Nitrofurantoin و Fosfomycin، را در پیلونفریت، باکتریمی و پروستاتیت تشخیص دهد.
13. نتایج نمونه، لام، کشت، CFU/mL و AST را در یک گزارش میکروب‌شناسی منسجم تلفیق کند.
14. در کیس‌های آموزشی، بین UTI واقعی، آلودگی، باکتریوری بدون علامت، CA-UTI و sterile pyuria تمایز ایجاد کند.

</div>

---

## Educational Structure

<div dir="rtl">

این بخش با چهار لایه آموزشی طراحی شده است:

| لایه آموزشی | هدف | محتوای اصلی |
|---|---|---|
| **Protocols** | یادگیری روش کار استاندارد | نمونه‌گیری، لام، کشت، CFU، AST، گزارش |
| **Reference Tables** | مرور سریع در محیط آموزشی یا آزمایشگاه | جدول پذیرش نمونه، CFU، تفسیر لام، پنل AST |
| **Case Studies** | تمرین استدلال بالینی-آزمایشگاهی | کیس‌های UTI ساده، پیچیده، کاتتر، بارداری، MDR و غیره |
| **Assessments** | ارزشیابی یادگیری نظری و عملی | سوال تشریحی، Rubric، OSPE، آزمون کوتاه و کلید پاسخ |

</div>

---

## Repository Structure

```text
01-urine/
│
├── README.md
│
├── pathophysiology/
│   └── uti-pathophysiology-and-classification.md
│
├── protocols/
│   ├── 01-specimen-collection-for-microbiology.md
│   ├── 02-acceptance-and-rejection-criteria.md
│   ├── 03-direct-examination-and-gram-stain.md
│   ├── 04-dipstick-for-microbiology.md
│   ├── 05-urine-culture-methods.md
│   ├── 06-colony-count-and-cfu-interpretation.md
│   ├── 07-antibiogram-for-urinary-isolates.md
│   └── 08-microbiology-reporting-and-comments.md
│
├── reference-tables/
│   ├── 01-specimen-acceptance-rejection.md
│   ├── 02-dipstick-and-direct-smear-interpretation.md
│   ├── 03-colony-count-and-cfu-interpretation.md
│   ├── 04-ast-master-table-urine.md
│   └── urine-microbiology-summary-tables.xlsx
│
├── case-studies/
│   ├── README.md
│   ├── 01-20-urine-microbiology-cases.md
│   ├── answer-key-01-20.md
│   ├── practice-scenarios.xlsx
│   └── detailed-answer-key.xlsx
│
├── assessments/
│   ├── README.md
│   ├── uti-essay-questions-with-answers.xlsx
│   ├── marking-rubric-case-studies.md
│   ├── ospe-practical-checklist.md
│   └── short-answer-quiz-template.md
│
└── assets/
    ├── README.md
    ├── image-captions.md
    ├── image-sources.md
    ├── images/
    │   ├── urine-sediment/
    │   ├── gram-stain/
    │   └── culture-plates/
    └── figures/
        └── README.md
```

---

# Protocols

<div dir="rtl">

پروتکل‌ها مسیر آموزشی اصلی این بخش هستند. پیشنهاد می‌شود به همان ترتیب شماره‌گذاری‌شده مطالعه یا تدریس شوند.

</div>

| شماره | فایل | موضوع | خروجی مورد انتظار |
|---:|---|---|---|
| 01 | `01-specimen-collection-for-microbiology.md` | نمونه‌گیری ادرار | انتخاب روش صحیح نمونه‌گیری |
| 02 | `02-acceptance-and-rejection-criteria.md` | پذیرش و رد نمونه | تشخیص نمونه نامناسب یا آلوده |
| 03 | `03-direct-examination-and-gram-stain.md` | لام مستقیم و گرم | مشاهده WBC، باکتری، قارچ و مورفولوژی گرم |
| 04 | `04-dipstick-for-microbiology.md` | دیپ‌استیک مرتبط با UTI | تفسیر LE و Nitrite |
| 05 | `05-urine-culture-methods.md` | کشت ادرار | کشت با لوپ کالیبره و محیط‌های مناسب |
| 06 | `06-colony-count-and-cfu-interpretation.md` | شمارش کلنی | محاسبه CFU/mL و تفسیر رشد |
| 07 | `07-antibiogram-for-urinary-isolates.md` | آنتی‌بیوگرام | انتخاب پنل گونه‌محور و گزارش انتخابی |
| 08 | `08-microbiology-reporting-and-comments.md` | گزارش نهایی | نوشتن گزارش قابل‌استفاده برای پزشک |

---

## Protocol Learning Flow

```text
Specimen Collection
        ↓
Transport and Sample Acceptance
        ↓
Direct Examination / Gram Stain
        ↓
Dipstick: LE and Nitrite
        ↓
Quantitative Urine Culture
        ↓
Colony Count and CFU/mL
        ↓
Organism Identification
        ↓
AST Panel Selection
        ↓
Selective Reporting and Final Microbiology Report
```

---

# Reference Tables

<div dir="rtl">

پوشه `reference-tables/` برای استفاده سریع در کلاس، کارگاه یا ایستگاه کاری آزمایشگاه طراحی شده است. این جدول‌ها را می‌توان به‌صورت Markdown در GitHub مشاهده یا نسخه Excel را برای چاپ استفاده کرد.

</div>

| فایل | کاربرد |
|---|---|
| `01-specimen-acceptance-rejection.md` | تشخیص نمونه قابل قبول، مشکوک یا قابل رد |
| `02-dipstick-and-direct-smear-interpretation.md` | تطابق LE، Nitrite، WBC، باکتری و کیفیت نمونه |
| `03-colony-count-and-cfu-interpretation.md` | تبدیل تعداد کلنی به CFU/mL و تفسیر کمی |
| `04-ast-master-table-urine.md` | جدول مادر انتخاب پنل آنتی‌بیوگرام بر اساس ارگانیسم |
| `urine-microbiology-summary-tables.xlsx` | جدول‌های آماده چاپ برای کارگاه یا آزمایشگاه |

### Reference Table Topics

- معیارهای پذیرش و رد نمونه
- نمونه MSU، نمونه کاتتر، SPA و نمونه کیسه‌ای
- نقش LE و Nitrite در غربالگری UTI
- عناصر مهم لام مستقیم از منظر میکروب‌شناسی
- نحوه محاسبه CFU/mL با لوپ 1 µL و 10 µL
- رشد خالص، رشد مختلط و آلودگی
- آستانه‌های تفسیری در بیمار علامت‌دار، بارداری، کودک و بیمار کاتترشده
- پنل‌های AST برای Enterobacterales، *Pseudomonas*, *Enterococcus* و Staphylococcus
- داروهای مناسب فقط برای lower UTI
- موارد نیازمند پنل تکمیلی ESBL, AmpC, CRE, VRE یا MDR

---

# Case Studies

<div dir="rtl">

پوشه `case-studies/` برای آموزش مبتنی بر سناریو طراحی شده است. هر کیس داده‌های آزمایشگاهی را در اختیار فراگیر قرار می‌دهد و از او می‌خواهد به‌صورت مرحله‌به‌مرحله تفسیر انجام دهد.

</div>

## Case Study Learning Tasks

برای هر کیس، فراگیر باید به پنج پرسش پاسخ دهد:

1. آیا نمونه از نظر میکروب‌شناسی قابل قبول است؟
2. لام مستقیم، گرم و دیپ‌استیک چه شواهدی از التهاب یا باکتریوری نشان می‌دهند؟
3. نتیجه کشت و CFU/mL چه معنایی دارند؟
4. آیا رشد، عفونت واقعی، آلودگی یا کلونیزاسیون است؟
5. پنل AST، گزارش نهایی و کامنت مناسب چیست؟

## Case Study Files

| فایل | محتوا |
|---|---|
| `01-20-urine-microbiology-cases.md` | 20 کیس آموزشی بدون پاسخ برای دانشجو |
| `answer-key-01-20.md` | کلید پاسخ تشریحی برای مدرس |
| `practice-scenarios.xlsx` | سناریوهای تمرینی قابل استفاده در کارگاه |
| `detailed-answer-key.xlsx` | پاسخ گام‌به‌گام و تفصیلی هر سناریو |

## Case Topics

کیس‌ها شامل موضوعات زیر هستند:

- سیستیت ساده با *E. coli*
- پیلونفریت با *E. coli*
- باکتریوری بدون علامت در بارداری
- نمونه آلوده و رشد مختلط
- *Proteus mirabilis* همراه با احتمال سنگ یا انسداد
- *Enterococcus faecalis* در سیستیت
- *Enterococcus faecium* مقاوم به وانکومایسین
- CA-UTI با *Pseudomonas aeruginosa*
- سودوموناس MDR در بیمار ICU
- UTI با سابقه ESBL
- UTI مردانه همراه با احتمال پروستاتیت
- کشت با CFU پایین پس از مصرف آنتی‌بیوتیک
- sterile pyuria
- candiduria در بیمار کاتترشده
- *Staphylococcus saprophyticus*
- *Staphylococcus aureus* در ادرار
- نمونه کیسه‌ای در کودک
- کلونیزاسیون یا آلودگی در بیمار با کاتتر مزمن
- شمارش پایین اما معنی‌دار در زن علامت‌دار
- *Klebsiella pneumoniae* در UTI پیچیده و مقاوم

---

# Assessments

<div dir="rtl">

پوشه `assessments/` ابزارهای ارزشیابی نظری و عملی را در اختیار مدرس قرار می‌دهد.

</div>

| فایل | کاربرد |
|---|---|
| `uti-essay-questions-with-answers.xlsx` | 20 سوال تشریحی با پاسخ کلیدی |
| `marking-rubric-case-studies.md` | Rubric استاندارد نمره‌دهی کیس‌ها |
| `ospe-practical-checklist.md` | چک‌لیست مهارت عملی برای OSPE یا کارگاه |
| `short-answer-quiz-template.md` | آزمون کوتاه، پیش‌آزمون یا پس‌آزمون |

## Assessment Domains

ارزیابی فراگیر در چهار حوزه اصلی انجام می‌شود:

| حوزه | نمونه مهارت |
|---|---|
| **Specimen Quality** | تشخیص نمونه آلوده، نمونه کیسه‌ای، نمونه کاتتر و معیار رد |
| **Direct Examination** | تفسیر WBC، باکتری، اپی‌تلیال، گرم مستقیم و LE/Nitrite |
| **Culture Interpretation** | محاسبه CFU/mL، رشد خالص، رشد مختلط و معنی بالینی شمارش |
| **AST and Reporting** | انتخاب پنل بر اساس ارگانیسم، حذف داروهای نامناسب و گزارش نهایی |

## Case Study Rubric

هر کیس می‌تواند از 10 نمره ارزیابی شود:

| معیار | نمره |
|---|---:|
| ارزیابی کیفیت نمونه | 2 |
| تفسیر لام و بررسی مستقیم | 2 |
| تفسیر کشت و CFU/mL | 2 |
| انتخاب پنل AST و محدودیت‌های گزارش | 2 |
| گزارش نهایی میکروب‌شناسی | 2 |
| **مجموع** | **10** |

---

# Assets and Images

<div dir="rtl">

پوشه `assets/` شامل تصاویر واقعی، نمودارها، زیرنویس‌ها و اطلاعات مجوز تصاویر است.

</div>

| فایل/پوشه | کاربرد |
|---|---|
| `assets/README.md` | اصول استفاده از تصاویر و دارایی‌های آموزشی |
| `assets/image-captions.md` | زیرنویس فارسی یک‌خطی برای تصاویر |
| `assets/image-sources.md` | ثبت منبع، صاحب اثر، لینک و مجوز تصویر |
| `assets/images/urine-sediment/` | تصاویر رسوب و لام مستقیم |
| `assets/images/gram-stain/` | تصاویر رنگ‌آمیزی گرم |
| `assets/images/culture-plates/` | تصاویر پلیت‌های کشت و کلنی |
| `assets/figures/` | فلوچارت‌ها، دیاگرام‌ها و فایل‌های قابل ویرایش |

## Image Policy

<div dir="rtl">

فقط در یکی از شرایط زیر می‌توان تصویر را در مخزن عمومی استفاده کرد:

1. تصویر توسط نگهدارنده پروژه تهیه شده باشد.
2. تصویر در مالکیت عمومی (*Public Domain*) باشد.
3. تصویر دارای مجوز بازنشر سازگار مانند CC BY یا CC BY-SA باشد.
4. برای استفاده از صاحب اثر مجوز کتبی وجود داشته باشد.

برای هر تصویر، فایل، زیرنویس، منبع، مجوز و تاریخ دسترسی باید در `image-sources.md` ثبت شود.

> هیچ تصویر یا داده‌ای که بتواند بیمار را شناسایی کند نباید در GitHub عمومی منتشر شود.

</div>

---

# Antibiogram and AST

<div dir="rtl">

آنتی‌بیوگرام باید بر اساس **گونه یا گروه باکتری** انتخاب شود، نه صرفاً بر اساس نوع نمونه یا جنس بیمار.

عوامل بیمارمحور، مانند سن، بارداری، عملکرد کلیه، سابقه مقاومت، آنتی‌بیوتیک اخیر، کاتتر، بستری اخیر و احتمال پروستاتیت، بیشتر در **گزارش انتخابی، پرچم‌گذاری، کامنت تفسیری و انتخاب بالینی دارو** نقش دارند.

</div>

## AST Decision Framework

```text
1. Identify the organism
        ↓
2. Select the organism-specific core AST panel
        ↓
3. Define infection syndrome
   - Lower UTI / cystitis
   - Pyelonephritis
   - Complicated UTI
   - CA-UTI
   - Prostatitis
   - Bacteremia / sepsis
        ↓
4. Assess resistance-risk factors
   - Previous ESBL/CRE/VRE/MDR isolate
   - Recent antimicrobial use
   - Recent hospitalization or ICU stay
   - Urinary catheter or instrumentation
        ↓
5. Add only indicated supplementary tests
        ↓
6. Exclude agents inappropriate for the organism or infection site
        ↓
7. Apply one standard only: CLSI or EUCAST
        ↓
8. Produce selective AST report and laboratory comment
```

## Key AST Principles

- برای *E. coli*، *Klebsiella* و سایر Enterobacterales، پنل پایه با پنل *Pseudomonas aeruginosa* یا *Enterococcus* یکسان نیست.
- برای *Pseudomonas aeruginosa* فقط داروهای ضدسودومونایی مناسب باید تست و گزارش شوند.
- Nitrofurantoin و Fosfomycin باید فقط در شرایط مناسب lower UTI مطرح شوند و برای پیلونفریت، باکتریمی یا پروستاتیت گزینه تفسیری مناسب نیستند.
- در *Enterococcus spp.*، داروهای نامناسب مانند سفالوسپورین‌ها نباید به‌عنوان گزینه حساس درمانی گزارش شوند.
- در موارد ESBL، AmpC، CRE، VRE یا MDR، باید الگوریتم مقاومت آزمایشگاه و SOP محلی اجرا شود.
- در یک گزارش، breakpointهای CLSI و EUCAST را با هم ترکیب نکنید.
- رده `I` در EUCAST به‌معنای **Susceptible, Increased Exposure** است.

---

# Recommended Learning Path

<div dir="rtl">

## مسیر پیشنهادی برای دانشجو

1. ابتدا بخش پاتوفیزیولوژی و طبقه‌بندی UTI را بخوانید.
2. پروتکل نمونه‌گیری، انتقال و پذیرش نمونه را مطالعه کنید.
3. بخش لام مستقیم، گرم و LE/Nitrite را مرور کنید.
4. روش کشت کمی و محاسبه CFU/mL را تمرین کنید.
5. جداول مرجع را به‌عنوان ابزار مرور سریع استفاده کنید.
6. ابتدا 20 کیس را بدون مشاهده پاسخ حل کنید.
7. سپس پاسخ خود را با کلید تشریحی مقایسه کنید.
8. در پایان، سوالات تشریحی و آزمون کوتاه را پاسخ دهید.
9. برای تمرین عملی، از چک‌لیست OSPE استفاده کنید.

</div>

## Suggested Learning Path for Instructors

<div dir="rtl">

1. پیش‌آزمون کوتاه را پیش از شروع جلسه اجرا کنید.
2. نمونه‌گیری و پذیرش/رد نمونه را با مثال‌های واقعی تدریس کنید.
3. چند لام مستقیم و پلیت کشت واقعی را نمایش دهید.
4. یک یا دو کیس را به‌صورت گروهی حل کنید.
5. دانشجویان را به گروه‌های کوچک تقسیم و کیس‌های دیگر را توزیع کنید.
6. با Rubric استاندارد، پاسخ‌ها را ارزیابی کنید.
7. جلسه را با بحث درباره پنل AST و گزارش انتخابی تمام کنید.
8. پس‌آزمون را برای سنجش میزان یادگیری اجرا کنید.

</div>

---

# For Instructors

<div dir="rtl">

این بخش برای استفاده در فرمت‌های زیر مناسب است:

- کلاس نظری میکروب‌شناسی بالینی
- کارگاه عملی کشت ادرار
- آموزش کارآموزان علوم آزمایشگاهی
- ایستگاه OSPE
- آموزش مورد-محور (*case-based learning*)
- تمرین گزارش‌دهی در بخش میکروب‌شناسی
- جلسه مرور آنتی‌بیوگرام و antimicrobial stewardship

### پیشنهاد برای یک جلسه 90 دقیقه‌ای

| زمان | فعالیت |
|---:|---|
| 10 دقیقه | پیش‌آزمون کوتاه |
| 15 دقیقه | نمونه‌گیری، حمل و پذیرش نمونه |
| 15 دقیقه | لام مستقیم، گرم، LE و Nitrite |
| 20 دقیقه | کشت کمی و CFU/mL |
| 15 دقیقه | انتخاب پنل AST و گزارش انتخابی |
| 10 دقیقه | حل گروهی یک Case Study |
| 5 دقیقه | جمع‌بندی و پس‌آزمون |

</div>

---

# For Students

<div dir="rtl">

برای استفاده مؤثر از این مجموعه:

- ابتدا پروتکل‌ها را به ترتیب شماره مطالعه کنید.
- هنگام مطالعه، از جدول‌های مرجع برای مرور سریع استفاده کنید.
- کیس‌ها را ابتدا بدون کلید پاسخ حل کنید.
- در پاسخ به هر کیس، همیشه از این ترتیب استفاده کنید:

```text
نوع و کیفیت نمونه
        ↓
یافته‌های لام / گرم / LE / Nitrite
        ↓
کشت، گونه و CFU/mL
        ↓
عفونت واقعی، آلودگی یا کلونیزاسیون؟
        ↓
پنل AST مناسب
        ↓
گزارش نهایی و کامنت لازم
```

- فقط نام باکتری را ننویسید؛ باید دلیل علمی تفسیر خود را بر پایه نوع نمونه، علائم، کیفیت نمونه، رشد و شمارش کلنی بیان کنید.

</div>

---

# Standards and Interpretation

<div dir="rtl">

تمام روش‌های عملی، پنل‌های آنتی‌بیوگرام، breakpointها، کیفیت محیط کشت، کنترل کیفیت و تفسیر حساسیت باید با SOP رسمی آزمایشگاه و یکی از استانداردهای زیر هماهنگ باشد:

- **CLSI**
- **EUCAST**

از به‌کاربردن هم‌زمان breakpointهای CLSI و EUCAST در یک گزارش اجتناب کنید.

محتوای این مخزن برای آموزش طراحی شده است؛ بنابراین هر فایل باید تاریخ بازبینی، نسخه و منبع استاندارد مورد استفاده را مشخص کند.

</div>

### Suggested Header for Protocol Files

```markdown
> Version: 0.1.0  
> Last reviewed: October 2026  
> Standard used: Local SOP + current CLSI or EUCAST  
> Intended use: Education only
```

---

# Safety and Limitations

<div dir="rtl">

- نمونه‌های ادرار ممکن است حاوی عوامل بیماری‌زا باشند و باید مانند نمونه بالینی بالقوه عفونی مدیریت شوند.
- تمام کشت‌ها، AST، کنترل کیفیت و دفع پسماند باید طبق سطح ایمنی زیستی، SOP و سیاست مؤسسه انجام شوند.
- نتیجه حساسیت آزمایشگاهی به‌تنهایی به‌معنای مناسب‌بودن دارو برای همه محل‌های عفونت نیست.
- انتخاب درمان نهایی به وضعیت بالینی، نفوذ دارو، PK/PD، عملکرد کلیه، آلرژی، بارداری، شدت بیماری، source control و گایدلاین محلی وابسته است.
- محتوای این پروژه جایگزین مشاوره پزشک عفونی، اورولوژیست، نفرولوژیست یا مسئول فنی آزمایشگاه نیست.

</div>

---

# Version Control

```text
Version: 0.1.0
Last updated: October 2026
Status: Initial educational release
```

## Planned Updates

- [ ] تکمیل پروتکل پاتوفیزیولوژی و طبقه‌بندی UTI
- [ ] افزودن تصاویر واقعی دارای مجوز بازنشر
- [ ] افزودن فلوچارت گرافیکی پذیرش نمونه
- [ ] افزودن فلوچارت گرافیکی انتخاب پنل AST
- [ ] تکمیل 20 کیس با پاسخ‌های تشریحی در Markdown
- [ ] ایجاد نسخه PDF قابل چاپ از جداول مرجع
- [ ] افزودن نمونه‌های گزارش واقعیِ ناشناس‌سازی‌شده
- [ ] افزودن بخش کنترل کیفیت کشت و AST
- [ ] افزودن بخش مقاومت‌های مهم: ESBL، AmpC، CRE، VRE و MDR

---

# Citation and License

## Citation

If you use this educational resource, please cite the repository according to:

```text
Clinical Practical Microbiology Education.
Urine Microbiology and Urinary Tract Infection Education.
Version 0.1.0, October 2026.
```

A machine-readable citation file should be available in the root repository:

```text
CITATION.cff
```

## License

This project is recommended to be released under:

```text
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
CC BY-NC-SA 4.0
```

Under this license, users may share and adapt the content for non-commercial purposes, provided that attribution is given and derivative work is shared under the same license.

---

# Contributing

<div dir="rtl">

از مشارکت علمی، پیشنهاد اصلاح، گزارش خطا و افزودن محتوای آموزشی استقبال می‌شود.

پیش از ارسال Pull Request:

1. محتوا را با SOP و استاندارد جاری تطبیق دهید.
2. منابع علمی را ذکر کنید.
3. از انتشار اطلاعات شناسایی‌کننده بیمار خودداری کنید.
4. برای تصاویر، منبع و مجوز بازنشر را ثبت کنید.
5. از نام‌گذاری استاندارد فایل‌ها با حروف کوچک و خط تیره استفاده کنید.
6. در هر فایل، Version و Last reviewed را وارد کنید.

برای جزئیات بیشتر، فایل `CONTRIBUTING.md` در ریشه مخزن را مطالعه کنید.

</div>

---

# Maintainer

```text
Maintained by: [Your Name]
Repository: Clinical Practical Microbiology Education
Section: Urine Microbiology and UTI
Language: Persian / English scientific terminology
Last updated: October 2026
```

---

## Suggested Topics

```text
microbiology
clinical-microbiology
urine-culture
urinary-tract-infection
uti
antibiogram
antimicrobial-susceptibility-testing
medical-education
laboratory-science
clinical-laboratory
persian
microbiology-education
```

# اوقات شرعی شهرهای ایران

استخراج شده از متولی تقویم و اوقات شرعی رسمی کشور، مرکز تقویم دانشگاه تهران

## ساختار فایل

- 1402 / data
  - Ostan.json
  - Shahrestan.json
  - ShahrDehestan.json
  - [`ostan.id`]
    - [`shahrestan.id`-`shahrDehestan.id`].json

## روش استفاده از فایل‌ها

### فایل Ostan.json

آرایه‌ای از نام و کد هر استان

### فایل Shahrestan.json

آرایه‌ای از نام و کد هر شرهستان به همراه کد استان

### فایل ShahrDehestan.json

آرایه‌ای از نام و کد منطقه به همراه کد شهرستان و کد استان

### فایل هر منطقه

هر فایل شهر/دهستان از یک آرایه به طول تعداد روزهای سال (365) تشکیل شده که هر آیتم آن یک آرایه از نوع رشته است که در خود زمان را به صورت ساعت و دقیقه نمایش می‌دهد.
که هر کدام از این زمان‌ها به ترتیب به موارد زیر اشاره می‌کند:

- اذان صبح
- طلوع خورشید
- اذان ظهر
- غروب آفتاب
- اذان مغرب
- نیمه شب شرعی

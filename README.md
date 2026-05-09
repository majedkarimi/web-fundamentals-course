# ۱. مفاهیم پایه وب (قبل از کدنویسی)

خیلی کوتاه ولی مهم.

- وب‌سایت چیست
- مرورگر چیست
- سرور چیست
- HTML / CSS / JS هرکدام چه کاری می‌کنند
- فایل و پوشه چیست
- ساخت پروژه در یک فولدر
- ساخت فایل `.html`

---

# ۲. HTML (ساختار صفحه)

هدف: بتوانند یک صفحه کامل بسازند.

## ساختار پایه

- `<!DOCTYPE html>`
- `html`
- `head`
- `body`
- `title`
- `meta`

## تگ‌های متنی

- `h1 → h6`
- `p`
- `br`
- `span`

## لینک و رسانه

- `a`
- `img`
- `target`
- `alt`

## لیست‌ها

- `ul`
- `ol`
- `li`

## ساختار صفحه

- `div`
- `section`
- `header`
- `footer`
- `nav`
- `main`

## فرم‌ها

- `form`
- `input`
- `label`
- `textarea`
- `button`
- `select`
- `option`

## مفاهیم مهم

- attribute
- class
- id
- nesting
- تگ‌های معنایی (semantic)

---

# ۳. CSS (استایل دادن)

هدف: بتوانند ظاهر سایت را کنترل کنند.

## اضافه کردن CSS

- inline (درون خطی)
- internal (داخلی)
- external (خارجی - فایل جدا)

## انتخاب‌گرها (Selectors)

- انتخاب‌گر عنصر (element)
- انتخاب‌گر کلاس (class)
- انتخاب‌گر آیدی (id)
- nesting (تودرتو)
- انتخاب‌گر گروهی (group)

## متن

- `color`
- `font-size`
- `font-family`
- `font-weight`
- `text-align`

## پس‌زمینه

- `background-color`
- `background-image`

## باکس مدل (Box Model)

مفهوم بسیار مهم:

- `margin` (فاصله بیرونی)
- `padding` (فاصله درونی)
- `border` (حاشیه)
- `width` (عرض)
- `height` (ارتفاع)

## Display

- `block` (بلوکی)
- `inline` (خطی)
- `inline-block` (خطی-بلوکی)

## فلکس باکس (Flexbox) — خیلی مهم

- `display: flex`
- `justify-content` (چینش افقی)
- `align-items` (چینش عمودی)
- `flex-direction` (جهت)
- `gap` (فاصله بین آیتم‌ها)

## چیدمان ساده (Layout)

- وسط‌چین کردن یک عنصر
- ساخت کارت (card)
- ساخت نوبار ساده (navbar)

## واکنش‌گرایی خیلی ساده (Responsive)

- `max-width`
- `media query` ساده

---

# ۴. جاوااسکریپت پایه (Basic JavaScript)

هدف: فهم منطق برنامه‌نویسی.

## متغیرها

- `let`
- `const`

## انواع داده

- string (رشته)
- number (عدد)
- boolean (درست/غلط)

## عملگرها

- `+`
- `-`
- `*`
- `/`
- `===`

## شرط‌ها

```
if (اگر)
else (در غیر این صورت)
else if (در غیر این صورت اگر)
```

## توابع

```
function (تعریف تابع)
return (برگشت مقدار)
parameters (پارامترها)
```

## آرایه‌ها

- ساخت آرایه
- دسترسی به عناصر
- `push` (اضافه کردن)
- `map` (نگاشت)
- `forEach` (برای هر عنصر)
- `filter` (فیلتر کردن)
- `find` (پیدا کردن)
- `includes` (شامل بودن)
- `has` (داشتن)

## آبجکت‌ها (خیلی ساده)

- key / value (کلید / مقدار)

---

# ۵. جاوااسکریپت در مرورگر

اینجا برنامه‌نویسی واقعی شروع می‌شود.

## اتصال JS به HTML

- `<script>`

## کنسول

- `console.log`

## انتخاب عنصر

- `document.querySelector`
- `getElementById`

## تغییر محتوا

- `innerText`
- `innerHTML`

## تغییر استایل

- `.style`

## رویدادها (Events)

- `click` (کلیک)
- `input` (ورودی)

## شنونده رویداد (Event Listener)

```
addEventListener
```

## ایجاد عنصر

- `createElement`
- `appendChild`

## حذف عنصر

- `remove`

---

# ۶. پروژه‌های تمرینی

خیلی مهم است که پروژه بسازند.

پروژه‌های مناسب این سطح:

- صفحه معرفی شخصی
- کارت پروفایل
- صفحه علایق
- نوبار ساده
- گالری عکس
- **لیست کارهای روزانه (Todo list) ساده**
- دکمه تغییر رنگ
- شمارنده

---

# ۷. گیت (Git) — خیلی پایه

فقط در حد استفاده برای پروژه.

## مفاهیم

- version control (کنترل نسخه) چیست
- repository (مخزن) چیست

## دستورات

```
git init
git add
git commit
git status
```

---

# ۸. گیت‌هاب (GitHub)

هدف: پروژه را آنلاین بگذارند.

- ساخت اکانت
- ساخت repository (مخزن)
- push کردن پروژه

## دستورات

```
git remote add origin
git push
```

## مفاهیم

- commit (ثبت تغییرات)
- repo (مخزن)
- push (ارسال)

---

# ۹. مهارت‌هایی که باید یاد بگیرند

این‌ها حتی از تکنولوژی مهم‌ترند.

- خواندن ارورها
- استفاده از Google
- استفاده درست از AI
- دیباگ با `console.log`
- شکستن مسئله به بخش‌های کوچک

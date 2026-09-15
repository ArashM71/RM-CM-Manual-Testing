# باگ‌های قراردادها

> این فایل از شیت اصلی تست استخراج شده است. تاریخ‌ها مطابق فایل مبدا (شمسی) نگه داشته شده‌اند.

**تعداد کل:** 117  |  **Open:** 52  |  **Partially Fixed:** 3  |  **Closed:** 62

---

## CON-001 — روی اعلان ها که کلیک میکنیم 1 تا 2 ثانیه delay دارد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/25
- **Detected Time:** 19:10-19-25
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
روی اعلان ها که کلیک میکنیم 1 تا 2 ثانیه delay دارد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 00:25
- **Update:** 1405/03/26

---

## CON-002 — وقتی یکبار بر روی ایجاد قرارداد نماینده از صفحه درخواست قراردادها که کلیک میکنیم از سری بعد باید از طریق…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/25
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی یکبار بر روی ایجاد قرارداد نماینده از صفحه درخواست قراردادها که کلیک میکنیم از سری بعد باید از طریق قسمت اعلان ها اقدام به درست کردن قرارداد کنیم

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 00:25
- **Update:** 1405/03/26

---

## CON-003 — برای ساخت قرارداد راننده به طور خودکار قالب اشتباه انتخاب میشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/25
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
برای ساخت قرارداد راننده به طور خودکار قالب اشتباه انتخاب میشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 21:30

---

## CON-004 — قالب قابل تغییر نیست

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/25
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
قالب قابل تغییر نیست

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 21:30

---

## CON-005 — پورسانت نمایندگی در قالب نمایش داده نمیشود

- **Status:** Closed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/03/26
- **Detected Time:** 22:00
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, priority:major, status:closed`

### Description
پورسانت نمایندگی در قالب نمایش داده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** آرون: تیبل تعرفه ها ساخته شد 1405/04/06

مشکل ماژول تعرفه تخفیف میباشد که تعرفه را ادیت کرده و خراب میکند (اما این مورد باید در دیتابیس قرارداد ها به ازای قالب ها و قرارداد ذخیره گردد تا مشکل دیپندنسی به ماژول تعرفه و تخفیف برای قالب های ساخته شده و قرارداد های ساخته شده حل شود.)

---

## CON-006 — محتوای قرارداد در قرارداد راننده هنگام مشاهده و یا مابقی مراحل ناقص نمایش داده میشود

- **Status:** Closed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/03/26
- **Detected Time:** 01:00
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, priority:major, status:closed`

### Description
محتوای قرارداد در قرارداد راننده هنگام مشاهده و یا مابقی مراحل ناقص نمایش داده میشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

آرون: مشکل زمانی ایجاد میشد که تعداد کاراکترهای متن اصلی از یک تعدادی بیشتر میشد

---

## CON-007 — در مدیریت اسناد ،جایگزینی عکس، عکس جدید را نشان نمیدهد…

- **Status:** Partially Fixed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/03/26
- **Detected Time:** 01:14
- **Original Test Result:** Fail
- **Reviewer:** آریا
- **Labels:** `bug, module:قراردادها, priority:major, status:partially-fixed`

### Description
در مدیریت اسناد ،جایگزینی عکس، عکس جدید را نشان نمیدهد.و برای پاک کردن به تعداد عکس های جایگزین شده باید از گزینه حذف استفاده کرد.

### Fix / Verification
- **Verification Result:** partially fixed
- **Update:** آرون: 500 میخوره 1405/04/06

آرون: برای جایگزینی عکس باید از /api/v1/file/replace استفاده بشه، api قبلا زده شده بود، فرانت باید فیکس کنه. آپدیت: فیکس شد

---

## CON-008 — در قالب نمایندگی،میتوان نوع شخص حقوقی (تیپاکس) را تغییر داد

- **Status:** Open
- **Priority:** medium
- **Module:** قراردادها
- **Detected Date:** 1405/03/27
- **Detected Time:** 22:10
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, priority:medium, status:open`

### Description
در قالب نمایندگی،میتوان نوع شخص حقوقی (تیپاکس) را تغییر داد

---

## CON-009 — هنگام ویرایش قالب، فیلدهای پویا ساخته شده نمایش داده نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/27
- **Detected Time:** 22:15
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
هنگام ویرایش قالب، فیلدهای پویا ساخته شده نمایش داده نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-010 — وقتی یک فیلد پویا را از لیست فیلدهای پویا پاک میکنیم…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/03/27
- **Detected Time:** 17:00
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی یک فیلد پویا را از لیست فیلدهای پویا پاک میکنیم،تمامی فیلدهایی که در متن قرارداد تغییر دادیم به حالت قبل برمیگردد.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 17:45

---

## CON-011 — در انتخاب طرفین میتوان نام نماینده را تغییر داد و به مرحله بعد رفت اما در مرحله بعد تاثیری نمیگذارد

- **Status:** Open
- **Priority:** medium
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Reviewer:** آریا
- **Labels:** `bug, module:قراردادها, priority:medium, status:open`

### Description
در انتخاب طرفین میتوان نام نماینده را تغییر داد و به مرحله بعد رفت اما در مرحله بعد تاثیری نمیگذارد

---

## CON-012 — شماره شناسنامه،نام پدر و کد پستی نماینده در فیلدهای پویا به صورت اتوماتیک پر نمیشود

- **Status:** Closed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, priority:major, status:closed`

### Description
شماره شناسنامه،نام پدر و کد پستی نماینده در فیلدهای پویا به صورت اتوماتیک پر نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-013 — شماره شناسنامه ضامن اول، شماره شناسنامه تلفن ثابت و تلفن همراه ضامن دوم به صورت اتومات پر نمیشود

- **Status:** Closed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, priority:major, status:closed`

### Description
شماره شناسنامه ضامن اول، شماره شناسنامه تلفن ثابت و تلفن همراه  ضامن دوم به صورت اتومات پر نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-014 — در مرحله بررسی مسول مربوطه و امضا و همچنین مشاهده قرارداد تکمیل شده…

- **Status:** Closed
- **Priority:** major
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, priority:major, status:closed`

### Description
در مرحله بررسی مسول مربوطه و امضا و همچنین مشاهده قرارداد تکمیل شده،قسمت طرفین قرارداد(آخر صفحه)نام نماینده نشان داده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

---

## CON-015 — وقتی الحاقیه روی قرارداد میزنیم ،باید طرف اول و دوم را مشخص کنیم

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی الحاقیه روی قرارداد میزنیم ،باید طرف اول و دوم را مشخص کنیم

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

---

## CON-016 — پس از ثبت قرار داد، قرارداد سمت سامانه نمایندگان فرستاده نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
پس از ثبت قرار داد، قرارداد سمت سامانه نمایندگان فرستاده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-017 — در صفحه در خواست قراردادها، وضعیت تمامی نمایندگان فعال میباشد و استتوس دیگری مشاهده نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Reviewer:** آرش
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در صفحه در خواست قراردادها، وضعیت تمامی نمایندگان فعال میباشد و استتوس دیگری مشاهده نمیشود

### Fix / Verification

آرون: برای تست، وضعیت یک نماینده رو به "غیرفعال" تغییر بدید (در سامانه نمایندگان) و بعد در قراردادها چک کنید که درست نشون میده یا نه

---

## CON-018 — در مرحله انتخاب طرفین، نمیتوان مشخصات ضامنین را مشاهده کرد…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در مرحله انتخاب طرفین، نمیتوان مشخصات ضامنین را مشاهده کرد.از طریق گزینه تعریف ضامنین میتوان مشاهده کرد که در آنجا شماره شناسنامه، سطح تحصیلات، طرف قرارداد ضامنین نمایش داده نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

آرون: به جز سطح تحصیلات (که از سامانه نمایندگان ارسال نمیشه) باقی موارد کاملند

---

## CON-019 — در صفحه انتخاب طرفین،نوع شخص هم کارفرما و هم پیمانکار میتوان نوع شخص را تغییر داد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در صفحه انتخاب طرفین،نوع شخص هم کارفرما و هم پیمانکار میتوان نوع شخص را تغییر داد

---

## CON-020 — میتوان برای تیپاکس، ضامن تعریف کرد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
میتوان برای تیپاکس، ضامن تعریف کرد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-021 — وقتی ضامنین از سامانه نمایندگان خوانده میشود،گزینه تعریف ضامنین در صفحه انتخاب طرفین نباید وجود داشته باش…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی ضامنین از سامانه نمایندگان خوانده میشود،گزینه تعریف ضامنین در صفحه انتخاب طرفین نباید وجود داشته باشد.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-022 — فیلد های پویا نام نمایندگی و کد نمایندگی نمایش داده نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
فیلد های پویا نام نمایندگی و کد نمایندگی نمایش داده نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-023 — فیلد پویا تاریخ عقد قرارداد به صورت اتومات پر نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
فیلد پویا تاریخ عقد قرارداد به صورت اتومات پر نمیشود

---

## CON-024 — پجینیش نوتیف حذف شود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
پجینیش نوتیف حذف شود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

آرون: در سمت بک اند انجام شد 1405/04/06

---

## CON-025 — مشخصات ضامنین در صفحه انتخاب طرفین وجود ندارد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
مشخصات ضامنین در صفحه انتخاب طرفین وجود ندارد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-026 — دیتای ضامنین در صفحه افراد حقیقی نمیاد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
دیتای ضامنین در صفحه افراد حقیقی نمیاد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/06

آرون: همزمان با نماینده، ضامنین هم در منابع قرارداد تعریف میشن

---

## CON-027 — در هر مرحله از روند ثبت قرارداد نماینده حتی اگر ذخیره کنیم ولی به یک صفحه دیگری برویم…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در هر مرحله از روند ثبت قرارداد نماینده حتی اگر ذخیره کنیم ولی به یک صفحه دیگری برویم، مراحل را باید از اول طی کرد.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

---

## CON-028 — گزینه تعریف ضامنین برای هر قراردادی که ضامنین انها از جای دیگر پر میشود برداشته شود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
گزینه تعریف ضامنین برای هر قراردادی که ضامنین انها از جای دیگر پر میشود برداشته شود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-029 — درخواست اصلاح قرارداد را که میزنیم همچنان میتوان ان قرارداد را بدون تغییر تایید کرد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/06
- **Original Test Result:** Fail
- **Reviewer:** نیاز به مشورت
- **Labels:** `bug, module:قراردادها, status:open`

### Description
درخواست اصلاح قرارداد را که میزنیم همچنان میتوان ان قرارداد را بدون تغییر تایید کرد

---

## CON-030 — در کارتابل قراردادها، قسمت سرچ، placeholder عنوان نام نماینده نوشته شود.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در کارتابل قراردادها، قسمت سرچ، placeholder عنوان نام نماینده نوشته شود.

---

## CON-031 — در منابع قرارداد قسمت حقیقی، ستون نام و نام خانوادگی جابجا شود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در منابع قرارداد قسمت حقیقی، ستون نام و نام خانوادگی جابجا شود

---

## CON-032 — مرحله انتخاب طرفین، از سمت فرانت، اسم نماینده نمیرود..(کلمه نماینده ارسال میشود.)

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
مرحله انتخاب طرفین، از سمت فرانت، اسم نماینده نمیرود..(کلمه نماینده ارسال میشود.)

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-033 — نوتیف نماینده جدید نمیاد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
نوتیف نماینده جدید نمیاد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

---

## CON-034 — صفحه تکمیل جزییات، وقتی ذخیره را میزنیم وارد مرحله بعدی میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
صفحه تکمیل جزییات، وقتی ذخیره را میزنیم وارد مرحله بعدی میشود

---

## CON-035 — مدارک نماینده نمایش داده نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
مدارک نماینده نمایش داده نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/07

---

## CON-036 — در الحاقیه طرف اول و دوم اتو فیل نیستند

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در الحاقیه طرف اول و دوم اتو فیل نیستند

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-037 — فیلد های پویا رانندگان پر نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
فیلد های پویا رانندگان پر نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-038 — ضامن راننده نمایش داده نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
ضامن راننده نمایش داده نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-039 — پس از درخواست اصلاح،امضا قرارداد ارور میدهد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/08
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
پس از درخواست اصلاح،امضا قرارداد ارور میدهد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-040 — ضامنین و طرفین در الحاقیه نمایش داده نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/08
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
ضامنین و طرفین در الحاقیه نمایش داده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/08

---

## CON-041 — در قسمت فیلدهای پویا،بعضی از فیلدها دوپلیکیت شده اند.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/09
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در قسمت فیلدهای پویا،بعضی از فیلدها دوپلیکیت شده اند.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/04/13

---

## CON-042 — وقتی از درخواست قراردادها یک قرارداد میخواهیم درست کنیم…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/10
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی از درخواست قراردادها یک قرارداد میخواهیم درست کنیم،در هر مرحله ای که باشیم وقتی وارد صفحه دیگری شویم ان قرارداد را باید دوباره مراحل را از اول طی کنیم.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-043 — قرارداد را رد میکنیم جایی نمایش داده نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/10
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
قرارداد را رد میکنیم جایی نمایش داده نمیشود

---

## CON-044 — در مرحله امضای طرفین قرارداد راننده، کد ملی امضا کننده(تیپاکس) وشماره تلفن امضا کننده وجود ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/10
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در مرحله امضای طرفین قرارداد راننده، کد ملی امضا کننده(تیپاکس) وشماره تلفن امضا کننده وجود ندارد

---

## CON-045 — فیلد پویا تاریخ تولد قرارداد راننده از جایی خوانده نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/10
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
فیلد پویا تاریخ تولد قرارداد راننده از جایی خوانده نمیشود

---

## CON-046 — نوتیف نماینده جدید و درخواست قرارداد فرستاده شده از سمت نمایندگان به درستی کار نمیکند

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
نوتیف نماینده جدید و درخواست قرارداد فرستاده شده از سمت نمایندگان به درستی کار نمیکند

---

## CON-047 — در قسمت فیلدهای پویا،بعضی از فیلدها دوپلیکیت شده اند.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در قسمت فیلدهای پویا،بعضی از فیلدها دوپلیکیت شده اند.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-048 — در قسمت الحاقیه، اگر ضامنین تغییر کرده باشند، ضامنین جدید نمایش داده نمیشود.ضامنین قبلی نمایش داده میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در قسمت الحاقیه، اگر ضامنین تغییر کرده باشند، ضامنین جدید نمایش داده نمیشود.ضامنین قبلی نمایش داده میشود

---

## CON-049 — انتخاب طرفین الحاقیه، جای تیپاکس و نماینده بر عکس میباشد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
انتخاب طرفین الحاقیه، جای تیپاکس و نماینده بر عکس میباشد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/04/17

---

## CON-050 — تبصره و ماده وقتی از تمپلیت حذف میکنیم باز هم نمایش داده میشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
تبصره و ماده وقتی از تمپلیت حذف میکنیم باز هم نمایش داده میشود.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-051 — هنگام ذخیره چرخه انتخاب شده،ارور 400 میدهد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/16
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
هنگام ذخیره چرخه انتخاب شده،ارور 400 میدهد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-052 — گزینه کد ملی جدید(در صفحه انتخاب طرفین) در قراردادی که از قسمت درخواست قرارداد ایجاد میشود حذف شود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/17
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
گزینه کد ملی جدید(در صفحه انتخاب طرفین) در قراردادی که از قسمت درخواست قرارداد ایجاد میشود حذف شود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/04/23

---

## CON-053 — ایا ضامنین حتما باید امضا کنند یا اختیاری میباشد؟

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/17
- **Reviewer:** نیاز به مشورت
- **Labels:** `bug, module:قراردادها, status:open`

### Description
ایا ضامنین حتما باید امضا کنند یا اختیاری میباشد؟

---

## CON-054 — در قرارداد راننده، کد ملی و شماره تلفن یکی میباشد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/18
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در قرارداد راننده، کد ملی و شماره تلفن یکی میباشد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-055 — در قسمت مدیریت اسناد، وقتی روی پروفایل یک شخص کلیک میکنیم، صفحه سفید میشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/23
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در قسمت مدیریت اسناد، وقتی روی پروفایل یک شخص کلیک میکنیم، صفحه سفید میشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/04/23

---

## CON-056 — تو درخواست قراردادها اگر شخص حقوقی باشد شناسه ملی نمایش داده نمیشود و نمیتوان قرارداد ساخت

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/24
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
تو درخواست قراردادها اگر شخص حقوقی باشد شناسه ملی نمایش داده نمیشود و نمیتوان قرارداد ساخت

---

## CON-057 — اگر قالبی طرفین داشته باشد ، در صفحه انتخاب طرفین (قرارداد دستی) هیچ اطلاعاتی را نمیتوان پر کرد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/24
- **Original Test Result:** Fail
- **Reviewer:** میلاد
- **Labels:** `bug, module:قراردادها, status:open`

### Description
اگر قالبی طرفین داشته باشد ، در صفحه انتخاب طرفین (قرارداد دستی) هیچ اطلاعاتی را نمیتوان پر کرد

---

## CON-058 — در انتخاب طرفین وقتی ذخیره میزنیم وارد مرحله بعد میشویم.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در انتخاب طرفین وقتی ذخیره میزنیم وارد مرحله بعد میشویم.

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-059 — مدیریت اسناد مدارک نمایش داده نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
مدیریت اسناد مدارک نمایش داده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-060 — در مدیریت اسناد شماره تلفن و کد ملی یکی میباشد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در مدیریت اسناد شماره تلفن و کد ملی یکی میباشد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-061 — در هنگام ساخت چرخه وقتی یک مرحله را پاک میکنیم دیگر نمیتوان ساخت چرخه را ادامه داد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در هنگام ساخت چرخه وقتی یک مرحله را پاک میکنیم دیگر نمیتوان ساخت چرخه را ادامه داد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-062 — چرخه پاک نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
چرخه پاک نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-063 — وضعیت قرارداد در کارتابل قراردادها درست نیست.یک مرحله جلوتر نمایش داده میشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وضعیت قرارداد در کارتابل قراردادها درست نیست.یک مرحله جلوتر نمایش داده میشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-064 — پیام (مرحله 4 قبلا تکمیل شده است) در صفحه تکمیل جزییات پس از زدن دکمه ذخیره برداشته شود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/26
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
پیام (مرحله 4 قبلا تکمیل شده است) در صفحه تکمیل جزییات پس از زدن دکمه ذخیره برداشته شود

---

## CON-065 — در صفحه انتخاب چرخه پس از چندین بار عوض کردن قالب…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/27
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در صفحه انتخاب چرخه پس از چندین بار عوض کردن قالب،بعد از زدن دکمه تایید و ادامه وارد مرحله بعد میشود و همچنین فیلدهای پویا محتوای قرارداد پر نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-066 — قرارداد امضا شده در قسمت مشاهده قرارداد وجود دارد اما دانلود نمیشود.. ارور 500 خطای داخلی سرور

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/27
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
قرارداد امضا شده در قسمت مشاهده قرارداد وجود دارد اما دانلود نمیشود.. ارور 500 خطای داخلی سرور

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-067 — وقتی یک چرخه را از قالب حذف میکنیم و بروز رسانی انجام میدهیم چرخه حذف نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/27
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی یک چرخه را از قالب حذف میکنیم و بروز رسانی انجام میدهیم چرخه حذف نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-068 — اگر چند الحاقیه بزنیم، تمامی انها برچسب version 1 میخورد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/27
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
اگر چند الحاقیه بزنیم، تمامی انها برچسب version 1 میخورد

### Fix / Verification
- **Verification Result:** fixed (pass)

هر قرارداد ظرفیت تنها یک الحاقیه را دارد بنابراین منطقی است.

---

## CON-069 — در محیط پروداکشن بروز رسانی قالب ارور (منبع مورد نظر یافت نشد) میدهد و نمیتوان قالب را به روز رسانی کرد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/04/31
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در محیط پروداکشن بروز رسانی قالب ارور (منبع مورد نظر یافت نشد) میدهد و نمیتوان قالب را به روز رسانی کرد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/05/28

---

## CON-070 — قرارداد نماینده ،جای ضامن اول و دوم برعکس میباشد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
قرارداد نماینده ،جای ضامن اول و دوم برعکس میباشد

### Fix / Verification
- **Verification Result:** fixed (pass)

---

## CON-071 — هنگام پاک کردن فیلد پویا، حتی اگر در جایی هم در حال استفاده نباشد پس از زدن دکمه حذف…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
هنگام پاک کردن فیلد پویا، حتی اگر در جایی هم در حال استفاده نباشد پس از زدن دکمه حذف،باید یکبار بروز رسانی انجام شود سپس فیلد پاک میشود

### Fix / Verification

به دلیل cache شدن دیتا این مشکل وجود دارد.

---

## CON-072 — در محیط پروداکشن وقتی بر روی ذخیره قالب کلیک میکنیم با این ارور روبرو میشویم (قالبی با عنوان 'قرارداد طرا…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در محیط پروداکشن وقتی بر روی ذخیره قالب کلیک میکنیم با این ارور روبرو میشویم
(قالبی با عنوان 'قرارداد طراحی و توسعه  نیوکور ' و نوع 'Corporate' قبلاً ثبت شده است. لطفاً عنوان یا نوع دیگری انتخاب کنید.)اما بعد از ان قالب ساخته میشود.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/05/24

---

## CON-073 — درخواست پودو در سامانه قراردادها نماینده نمایش داده میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/05
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
درخواست پودو در سامانه قراردادها نماینده نمایش داده میشود

---

## CON-074 — در محیط پروداکشن،طرفین قرارداد ثبت میشود اما پس از ذخیره و ادیت دوباره طرفین حذف میشوند

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/05
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در محیط پروداکشن،طرفین قرارداد ثبت میشود اما پس از ذخیره و ادیت دوباره طرفین حذف میشوند

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/05/28

---

## CON-075 — در محیط پروداکشن، فیلدهای پویا ساخته شده پس از ثبت قالب نمایش داده نمیشود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/07
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در محیط پروداکشن، فیلدهای پویا ساخته شده پس از ثبت قالب نمایش داده نمیشود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Verification Time:** 1405/05/28

---

## CON-076 — هنگام ساختن قرارداد دستی،طرف اول که در قالب انتخاب شده به صورت اتومات در قسمت انتخاب طرفین پر نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/20
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
هنگام ساختن قرارداد دستی،طرف اول که در قالب انتخاب شده به صورت اتومات در قسمت انتخاب طرفین پر نمیشود

---

## CON-077 — هنگام ساخت قالب، وقتی یک جدول درست میکنیم گزینه های مربوط به جدول شامل اضافه کردن ردیف و ستون و یا حذف کر…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/05/30
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
هنگام ساخت قالب، وقتی یک جدول درست میکنیم گزینه های مربوط به جدول شامل اضافه کردن ردیف و ستون و یا حذف کردن آنها وجود ندارد(محیط پروداکشن و dev)

---

## CON-078 — فیلد پویا تعرفه وجود ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/02
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
فیلد پویا تعرفه وجود ندارد

---

## CON-079 — در صفحه کارتابل قراردادها، طرف اول و طرف دوم، تیپاکس میباشد.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در صفحه کارتابل قراردادها، طرف اول و طرف دوم، تیپاکس میباشد.

---

## CON-080 — در صفحه مشاهده قرارداد و صفحه امضا قرارداد، طرفین قرارداد چندین بار تکرار می شود.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در صفحه مشاهده قرارداد و صفحه امضا قرارداد، طرفین قرارداد چندین بار تکرار می شود.

---

## CON-081 — صفحه جزییات قرارداد وقتی ذخیره را میزنیم ارور 504 می دهد اما مرحله تکمیل میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/03
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
صفحه جزییات قرارداد وقتی ذخیره را میزنیم ارور 504 می دهد اما مرحله تکمیل میشود

---

## CON-082 — وقتی ذخیره محتوا را میزنیم ارور 400 میدهد، اما پس از آن از طریق کارتابل قرارداد ها وارد آن میشویم وارد مر…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/04
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
وقتی ذخیره محتوا را میزنیم ارور 400 میدهد، اما پس از آن از طریق کارتابل قرارداد ها وارد آن میشویم وارد مرحله امضا شده و مرحله تکمیل جزییات را اتوماتیک رد میکند.

---

## CON-083 — در محیط پروداکشن(قالب کارپوینت)،طرفین قرارداد ثبت میشود اما پس از ذخیره و ادیت دوباره طرفین حذف میشوند و…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/09
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در محیط پروداکشن(قالب کارپوینت)،طرفین قرارداد ثبت میشود اما پس از ذخیره و ادیت دوباره طرفین حذف میشوند و همچنین فیلدهای پویا در سمت چپ صفحه تایپ ندارند

---

## CON-084 — در محیط پروداکشن، بروز رسانی قالب ارور 502 میدهد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/09
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در محیط پروداکشن، بروز رسانی قالب ارور 502 میدهد

---

## CON-085 — وقتی یک کاربر در بخش مدیریت کاربران میسازیم نمیتوان با آن کاربر وارد سامانه شد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی یک کاربر در بخش مدیریت کاربران میسازیم نمیتوان با آن کاربر وارد سامانه شد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/16

فیکس شد.

---

## CON-086 — بخش مدیریت کاربران(کاربران):کاربر ساخته شده به اخر لیست میرود

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
بخش مدیریت کاربران(کاربران):کاربر ساخته شده به اخر لیست میرود

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/22

مرتب شدن لیست بر اساس ویرایش/ایجاد کاربر ایجاد شد.

---

## CON-087 — پروفایل کاربر هیچ اکشنی ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
پروفایل کاربر هیچ اکشنی ندارد

---

## CON-088 — وقتی نام یک کاربر را ویرایش میکنیم،نام کاربر در قسمت پروفایل تغییری نمیکند

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
وقتی نام یک کاربر را ویرایش میکنیم،نام کاربر در قسمت پروفایل تغییری نمیکند

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/16

بعد از refresh شدن token تغییر اعمال می شود.

---

## CON-089 — صفحه جزییات قرارداد وقتی ذخیره را میزنیم ارور 504 می دهد اما مرحله تکمیل میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
صفحه جزییات قرارداد وقتی ذخیره را میزنیم ارور 504 می دهد اما مرحله تکمیل میشود

---

## CON-090 — مدیریت کاربران(کاربران)گزینه بروز رسانی اکشنی ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
مدیریت کاربران(کاربران)گزینه بروز رسانی اکشنی ندارد

---

## CON-091 — مدیریت کاربران(شرکت ها)شرکت درست شده حذف نمیشود…

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
مدیریت کاربران(شرکت ها)شرکت درست شده حذف نمیشود..ارور 400 خطا در حذف واحد: ORA-00904: "FALSE": invalid identifierhttps://docs.oracle.com/error-help/db/ora-00904/

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/22

خطای تبدیل bool به char, فیکس شد.

---

## CON-092 — بخش مدیریت کاربران(کاربران):نام کاربر ساخته شده ایمیل میباشد

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
بخش مدیریت کاربران(کاربران):نام کاربر ساخته شده ایمیل میباشد

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/16

فیکس شد.

---

## CON-093 — در قسمت مدیریت کاربران(سطح دسترسی): وقتی بخش حذف در قالب ها را انتخاب میکنیم…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در قسمت مدیریت کاربران(سطح دسترسی): وقتی بخش حذف در قالب ها را انتخاب میکنیم، کاربری که ان گروه دسترسی را به ان assign میکنیم، نمیتواند قالب را حذف کند

---

## CON-094 — سطح دسترسی قابلیت حذف ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
سطح دسترسی قابلیت حذف ندارد

---

## CON-095 — کاربران شرکت های مختلف، میتوانند کاربران دیگر شرکت ها را ببینند

- **Status:** Partially Fixed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:partially-fixed`

### Description
کاربران شرکت های مختلف، میتوانند کاربران دیگر شرکت ها را ببینند

### Fix / Verification
- **Verification Result:** partially fixed
- **Update:** 1405/06/19

فیلترهای اولیه برای کاربران شرکت ها اعمال شده, منابع قرارداد و اعلان ها باقی مانده اند.

---

## CON-096 — فرایند هشدار حذف نمیشود.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
فرایند هشدار حذف نمیشود.

---

## CON-097 — لاگین صفحه قراردادها و نمایندگان متفاوت میباشد.هم فونت هم رنگ

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
لاگین صفحه قراردادها و نمایندگان متفاوت میباشد.هم فونت هم رنگ

---

## CON-098 — مدیریت کاربران(کاربران) گزینه سرچ ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
مدیریت کاربران(کاربران) گزینه سرچ ندارد

---

## CON-099 — چرخه قراردادها سرچ ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
چرخه قراردادها سرچ ندارد

---

## CON-100 — وقتی از فیلد پویا یک قالب استفاده میکنیم وقالب را ذخیره میکنیم…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
وقتی از فیلد پویا یک قالب استفاده میکنیم وقالب را ذخیره میکنیم،پس از ان وقتی ادیت قالب را میزنیم فیلد پویا استفاده شده دوپلیکیت میشود

---

## CON-101 — گروه بندی قراردادها لیست ندارد.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
گروه بندی قراردادها لیست ندارد.

---

## CON-102 — تقویم کاری هنگام ذخیره افزودن یاداوری ارور خطا در ایجاد یاداوری میدهد.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
تقویم کاری هنگام ذخیره افزودن یاداوری ارور خطا در ایجاد یاداوری میدهد.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/21

API اشتباهی کال می شد.

---

## CON-103 — هنگام انعقاد قرارداد، پس از انتخاب قالب و کلیک بر روی دکمه تایید،خطای ارور سرور میدهد.ارور 500

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
هنگام انعقاد قرارداد، پس از انتخاب قالب و کلیک بر روی دکمه تایید،خطای ارور سرور میدهد.ارور 500

---

## CON-104 — ویرایش قرارداد اکشنی ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
ویرایش قرارداد اکشنی ندارد

---

## CON-105 — مدیریت اسناد فیلتر ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
مدیریت اسناد فیلتر ندارد

---

## CON-106 — کارتابل قراردادها فیلتر ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
کارتابل قراردادها فیلتر ندارد

---

## CON-107 — عدم حفظ Pagination پس از بازگشت در تمامی table ها

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
عدم حفظ Pagination پس از بازگشت در تمامی table ها

---

## CON-108 — صفحه منابع قرارداد، افراد حقیقی،ویرایش طرف قرارداد،ایمیل و سطح تحصیلات نمایش داده نمیشود.

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
صفحه منابع قرارداد، افراد حقیقی،ویرایش طرف قرارداد،ایمیل و سطح تحصیلات نمایش داده نمیشود.

---

## CON-109 — اولویت چرخه ها فرقی باهم ندارند.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
اولویت چرخه ها فرقی باهم ندارند.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/22

لیست چرخه ها بر اساس اولویت مرتب می شود.

---

## CON-110 — مدیریت کاربران، افزودن شرکت فقط ادمین کل باید ببیند

- **Status:** Partially Fixed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:partially-fixed`

### Description
مدیریت کاربران، افزودن شرکت فقط ادمین کل باید ببیند

### Fix / Verification
- **Verification Result:** partially fixed
- **Update:** 1405/06/18

از سمت بک اند فیکس شد.

---

## CON-111 — مدیریت کاربران،وقتی یک سطح دسترسی را تغییر میدهیم،پس از ثبت تغییری پیدا نمیکند…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
مدیریت کاربران،وقتی یک سطح دسترسی را تغییر میدهیم،پس از ثبت تغییری پیدا نمیکند.چندین بار باید تغییر داد تا تغییرات اعمال شود.

---

## CON-112 — گروه بندی قراردادها، حذف ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
گروه بندی قراردادها، حذف ندارد

---

## CON-113 — در قسمت اعلان ها، نوتیف درخواست نمایندگی که از سمت سامانه نمایندگان ارسال شده نمایش داده نمیشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در قسمت اعلان ها، نوتیف درخواست نمایندگی که از سمت سامانه نمایندگان ارسال شده نمایش داده نمیشود

---

## CON-114 — در قسمت notifications،دکمه بررسی و تایید اکشنی ندارد

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در قسمت notifications،دکمه بررسی و تایید اکشنی ندارد

---

## CON-115 — وقتی در مرحله تکمیل محتوا تایید را میزنیم ارور میدهد اما وقتی همان قرارداد را از کارتابل قراردادها وارد م…

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
وقتی در مرحله تکمیل محتوا تایید را میزنیم ارور میدهد اما وقتی همان قرارداد را از کارتابل قراردادها وارد میشویم، قرارداد وارد مرحله امضا شده است

---

## CON-116 — در صفحه قالب ها، هیچ قالبی لود نمیشود.

- **Status:** Closed
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:closed`

### Description
در صفحه قالب ها، هیچ قالبی لود نمیشود.

### Fix / Verification
- **Verification Result:** fixed (pass)
- **Update:** 1405/06/23

---

## CON-117 — در صفحه مشاهده قرارداد، طرفین قرارداد،ضامن اول و دوم هم نمایش داده میشود

- **Status:** Open
- **Priority:** unspecified
- **Module:** قراردادها
- **Detected Date:** 1405/06/11
- **Original Test Result:** Fail
- **Labels:** `bug, module:قراردادها, status:open`

### Description
در صفحه مشاهده قرارداد، طرفین قرارداد،ضامن اول و دوم هم نمایش داده میشود

---

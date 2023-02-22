## ۱ -گیت چیست و چه کاربردی دارد؟ 
گیت یک نوع سیستم کنترل ورژن (VCS) است که با آن می‌توانید تغییرات اعمال شده در فایل‌ها را ساده‌تر پیگیری کنید. مثلاً، اگر فایلی را ویرایش کنید، گیت می‌تواند دقیقاً به شما بگوید که چه چیزی تغییر کرده است، چه کسی آن را تغییر داده است و دلیلِ این تغییر چه بوده است.
گیت (Git) این امکان را برای برنامه‌نویس فراهم می‌کند که در مورد وضعیت سیستم توزیع متن باز اطلاع کسب کرده و تغییرات ایجاد شده را ردیابی کند.

## ۲ -دستور init git چه کاری انجام میدهد؟
دستور git init یک مخزن گیت جدید می‌سازد. اجرای git init یک زیر پوشه git. در پوشه کاری کنونی می‌سازد که حاوی همه فراداده‌های گیت لازم برای مخزن جدید است.

## ۳ -دستور status git چه کاربردی دارد؟
دستور Git Status برای نمایش وضعیت مخزن و ناحیه مرحله‌بندی استفاده می‌شود. با استفاده از این دستور، می‌توانید فایل‌های موجود در ناحیه مرحله‌بندی و فایل‌های ویرایش‌شده‌ و نیازمند به ثبت را مشاهده کنید.

## ۴ -دستور add git چه کاری انجام میدهد؟
دستور git add فایل‌های فعلی را به ناحیه نسخه‌بندی (Staging) اضافه می‌کند (قبل از ثبت تغییرات با Commit). هربار که فایلی را در پروژه خود اضافه یا به‌روز می‌کنید، برای ثبت تغییرات، باید به‌روز‌رسانی‌ها را به قسمت Staging ارسال کنید.

## ۵ -دستور commit git چه کاری انجام میدهد؟
سیستم های کنترل نسخه برای این ساخته شده اند که بیش از یک شخص بتواند بر روی همان پروژه کار کند. هر برنامه نویس کدها را دانلود می کند، بر روی آن کار می کند، ویژگی جدید یا تغییراتی را ایجاد می کنید که به این کار commit می گویند.

## ۶ -دستور log git چه کاربردی دارد؟
این دستور برای دیدن تاریخچه کامیت ها کاربرد دارد.

## ۷ -دستور branch git چه کاری انجام میدهد؟
زمانی که ما یه مخزن ایجاد میکنیم یک شاخه به عنوان شاخه اصلی ساخته می شود به نام master که نقش شاخه اصلی رو داره تمام کامیت ها روی اون قرار میگیرد. با اجرای این دستور شما میتونید شاخه فرعی خودتون رو بسازید و توسعه ویژگی جدید رو شروع کنید.

## ۸ -دستور add remote git چه کاری انجام میدهد و چه کاربردی دارد؟
با این دستور بین مخزن محلی خودمون و مخزن آنلاین ارتباط برقرار میکنیم.

## ۹ -دستور push git چه کاری انجام میدهد؟
دستور git push برای بارگذاری محتویات مخزن Local به مخزن remote استفاده می شود. با push کردن، شما commit های Local خود را به مخزن remote منتقل می کنید.

## ۱۰ -دستور pull git چه کاری انجام میدهد و برای چه استفاده میشود؟
از دستور git pull برای واکشی و دانلود محتوا از یک مخزن remote استفاده می شود. این دستور بلافاصله پس از دانلود از مخزن remote، مخزن محلی را برای مطابقت با محتوای دانلود شده به روزرسانی می کند.

## ۱۱ -دستور clone git چه کاری انجام میدهد و برای چه استفاده میشود؟
اگر پروژه‌ای قبلاً در مخزن مرکزی راه‌اندازی شده باشد، دستور Clone رایج‌ترین راه برای دریافت فایل‌های آن مخزن است. همانند git init، کلونینگ نیز معمولاً عملیاتی یک‌بار‌مصرف است. پس از کلون‌کردن یک نسخه، تمام عملیات‌های کنترل ورژن ازطریق مخزن محلی مدیریت می‌شوند.
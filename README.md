# Easy Chemistry — Dr/Ahmed Mahmoud

نسخة أولى مرتبطة بـSupabase Auth لتسجيل دخول الـAdmin.

## إعداد Admin
1. في Supabase افتح Authentication → Users.
2. أنشئ مستخدمًا جديدًا ببريد إلكتروني وكلمة مرور قوية.
3. استخدم نفس البيانات في `login.html`.

## مهم
المفتاح الموجود في `supabase-config.js` هو Publishable key ومصمم للاستخدام في تطبيقات الواجهة. لا تضع Secret/Service Role key في ملفات الموقع.

## المرحلة التالية
إضافة جداول الكورسات والمحاضرات والطلاب، تفعيل Row Level Security، ثم ربط لوحة الإدارة بإضافة/تعديل المحتوى وSupabase Storage للملفات.

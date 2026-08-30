# YAKOOT Independent v4

نسخة YAKOOT مربوطة بقاعدة Supabase الخاصة بالمشروع.

## التشغيل
1. افتح Supabase وشغّل ملف `supabase_schema.sql` كاملًا في SQL Editor.
2. من Authentication > Users أنشئ حساب الإدارة بالبريد وكلمة المرور.
3. ارفع ملفات المشروع على استضافة HTTPS (Netlify مناسب).
4. افتح `index.html` للمتجر و`admin.html` للإدارة.

تم وضع Project URL وPublishable Key في `config.js`. لا يوجد Service Role Key داخل المشروع.

## الوظائف
- تحميل المنتجات من Supabase.
- إنشاء الطلبات في `orders` وحفظ عناصرها في `order_items`.
- تسجيل دخول الإدارة عبر Supabase Auth.
- إضافة/حذف المنتجات وإدارة حالة الطلبات من لوحة الإدارة.

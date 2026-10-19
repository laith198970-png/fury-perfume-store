FURY PERFUME — دليل سريع
1) فك ضغط ZIP إلى مجلد واحد.
2) انسخ config.example.js وسمِّ النسخة config.js، ثم ضع Project URL وPublishable key من Supabase ورقم واتساب الدولي.
3) لا تستخدم Secret key أو service_role داخل ملفات الموقع.
4) في Supabase > SQL Editor شغّل محتوى supabase_schema.sql.
5) في Authentication > Users أنشئ حساباً لك وحساباً لأحمد، ثم أضف UUID لكل حساب إلى public.admin_users عبر الاستعلام المرفق بآخر ملف SQL. لكل واحد بريد وكلمة مرور مستقلة.
6) ارفع index.html وstyle.css وapp.js وconfig.js إلى نفس مجلد الاستضافة. استخدم استضافة HTTPS؛ فتح index.html مباشرة من مدير الملفات قد لا يعمل بسبب JavaScript modules.
7) لوحة الإدارة تتيح إضافة وتعديل وإخفاء وحذف العطور. الأحجام المدعومة 5 و10 و35 و60 و100 مل.
هذه ملفات الموقع وليست موقعاً منشوراً تلقائياً؛ يلزم إعداد Supabase والاستضافة.

# نشر محتوى وِرد

رابط الإنتاج ثابت داخل التطبيق: https://majd-alhafi.github.io/wird-content/ . لا يحتاج المستخدم إلى إدخال رابط أو مفتاح. المستودع الموجود هو https://github.com/majd-alhafi/wird-content .

لإدارة الكتب الحالية وإضافة كتاب أو إخفائه، اتبع LIBRARY_MANAGEMENT.md. الفهرس داخل content_site/manifest.json، والكتاب موزع على ملفات JSON تُحمّل عند الطلب وتُفحص ببصمات SHA256. بعد تعديل الملفات، راجعها ثم انقل الملفات المعدلة فقط إلى checkout المستودع الحالي، واعمل commit وpush عاديين، ثم انتظر نجاح Publish Wird content. لا تستخدم force-push ولا تنشر تسجيلات الأذان الخاصة أو APK أو بيانات المستخدم.

tool/publish_content.ps1 مخصص لإنشاء مستودع جديد فقط؛ يرفض المستودع الموجود لحمايته. لا تستعمله لإعادة إنشاء مستودعك الحالي. تحديثه يتم باستخدام Git المعتاد. تحقق من الفهرس المنشور بواسطة tool/verify_hosted_content.py.

الحقوق والمصادر موثقة في ASSET_CREDITS.md وCONTENT_POLICY.md وQURANPEDIA_TRANSLATIONS.md وLIBRARY_MANAGEMENT.md. ترخيص OpenITI هو CC BY-NC-SA 4.0، وشروط Quranpedia تخص بياناته مع بقاء حقوق المؤلفين والناشرين. لا يصح استنتاج ترخيص أي PDF من مجرد إمكانية تنزيله.

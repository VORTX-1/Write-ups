# إرشادات الإسهام

قواعد التسمية للملف
- الشكل الموصى به: YYYYMMDD-SECTION-title-author.md
  مثال: `20260816-crypto-caesar-ahmed.md`
- أو: `SECTION/title_author.md` مثل `Cryptography/caesar_ahmed.md`

خطوات الإضافة
1. عمل فرع جديد: `git checkout -b writeup/<short-title>-<your-name>`
2. إضافة الملف في المجلد المناسب مع ملء القالب.
3. عمل commit: `git add . && git commit -m "Add writeup: <title> (<section>)"`
4. رفع الفرع: `git push origin writeup/<short-title>-<your-name>`
5. افتح Pull Request وعلّق وصفياً: ما التمرين، مصدره (CTF/اسم المسابقة/لينك)، الوقت المستغرق، ووسوم مقترحة (difficulty, tags).

مراجعة المحتوى
- راجع واحد آخر (peer-review) للتأكد من:
  - الوضوح والتعليمية.
  - عدم نشر حلول كاملة لمسابقات ما زالت جارية (احترم قواعد المسابقة).
- استخدم labels: `review/needed`, `reviewed`, `ready-to-merge`.

قالب المراجعة السريعة
- هل الشرح واضح للمبتدئين؟ (نعم/لا)
- هل الأوامر قابلة للتشغيل كما هي؟ (نعم/لا)
- اقتراحات/تصحيحات:

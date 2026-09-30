# خطوات تركيب بروفايل Mayar على GitHub

الملفات: README.md وdark.svg وlight.svg، بالإضافة إلى github-snake/.github/workflows/snake.yml.

## 1) ارفعي تصميم البروفايل

1. سجلي الدخول إلى GitHub وافتحي المستودع العام الذي اسمه بالضبط mayarelaraby83-source.
2. إذا لم يكن موجودًا: اختاري New repository، اكتبي mayarelaraby83-source كاسم، اختاري Public، وفعّلي Add a README file ثم Create repository.
3. من صفحة المستودع، افتحي README.md واضغطي Edit this file.
4. افتحي README.md المرفق هنا، انسخي محتواه كله، والصقيه بدل النص الموجود.
5. اضغطي Commit changes لحفظه على الفرع main.
6. ارجعي للمستودع واضغطي Add file ثم Upload files.
7. ارفعي dark.svg وlight.svg إلى جذر المستودع، بجوار README.md، ثم اضغطي Commit changes.
8. افتحي صفحة حسابك وتحققي من ظهور البانر والأقسام. اختبري العرض في المظهرين الفاتح والداكن.

## 2) جهزي مستودع Snake

1. أنشئي مستودعًا عامًا جديدًا اسمه github-snake، من دون الحاجة لإضافة README.
2. افتحيه واختاري Add file ثم Create new file.
3. في خانة اسم الملف اكتبي المسار كاملًا: .github/workflows/snake.yml
4. افتحي الملف المرفق داخل مجلد github-snake/.github/workflows وانسخي محتواه كاملًا في محرر GitHub.
5. اضغطي Commit changes على الفرع main.
6. افتحي Settings ثم Actions ثم General.
7. انزلي إلى Workflow permissions، اختاري Read and write permissions، ثم Save.
8. افتحي تبويب Actions، اختاري Generate Contribution Snake، ثم Run workflow وشغليه على main.
9. بعد انتهاء التشغيل بنجاح، ارجعي إلى Code وتأكدي أن فرع output ظهر وفيه github-snake.svg وgithub-snake-dark.svg.
10. تحققي من الملفين:
    - https://raw.githubusercontent.com/mayarelaraby83-source/github-snake/output/github-snake.svg
    - https://raw.githubusercontent.com/mayarelaraby83-source/github-snake/output/github-snake-dark.svg

قسم Snake في README يشير إلى هذه المسارات. بعد إنشاء المستودع وتشغيل الإجراء ستظهر الصورة؛ لا تعدلي الروابط ما دام اسم المستودع واسم المستخدم كما هما.

## 3) راجعي صفحة الحساب

- من إعدادات GitHub حدّثي الاسم والنبذة وصورة الحساب وروابط التواصل التي تريدين عرضها.
- من صفحتك اختاري Customize pins وثبتي المشاريع التي تريدين إبرازها.
- تأكدي من أسماء المشاريع والوصف والروابط. لا تنشري البريد أو الموقع أو صورتك إلا إذا رغبتِ بذلك.

## الصورة الشخصية

البانر الحالي يستخدم رسمًا هندسيًا وأحرف ME بدل صورة، لأن الصور المرفقة كانت مرجعًا لشخص آخر. أرسلي صورتك الشخصية إذا أردتِ أن أضعها مكان الرمز في ملفي dark.svg وlight.svg قبل الرفع.

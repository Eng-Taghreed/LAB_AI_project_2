في هذا المشروع يتم تدريب النموذج على مجموعة من الصور ليقوم بتحميلها وتشفيرها  ورصد اسم كل صورة وتخزين هذه النتائج.

ثم بعد ذلك عند عرض اي صورة للنموذج يقوم بتحميل الصورة وتشفيرها ومقارنتها بالصور ونتائج التشفير المخزنة لديه سابقا ويقيس اقصر مسافة مابين تشفير الصورة الحالية وتشفيرات الصور المخزنة، فيكون أقر مسافة هي الصورة المطابقة فيظهر بعدها نتائج بأن الشخص المتواجد في الصورة هو الشخص الفلاني المطابق للصورة المخزنة. 

هذا المشروع مفيد جدا أن تم استخدامه كوسيلة تحضير في المدارس والمكاتب وكذلك كوسيلة أمنية في المطارات كما هو في مطار الملكة علياء في الاردن. 

تم استخدام مجموعة من المكاتب التي ساعدت في إنشاء المشروع وهي : 
opencv: مكتبة OpenCV تستخدم لمعالجة الصور والفيديو.
numpy: مكتبة تستخدم لمعالجة البيانات بشكل فعّال، وخاصة المصفوفات.
face_recognition: مكتبة لتسهيل عمليات التعرف على الوجوه.
os: مكتبة للتفاعل مع نظام الملفات (مثل قراءة قائمة الملفات في مجلد).
dlib:تحسين دقة التعرف على الوجوه وتحديد ملامح الوجه وتحسين سرعة الأداء وفاعليته.
Cmake: التي تحتاجها مكتبة dlibحتى تستطيع العمل

يحتوي الكود على مراحل مثل تحميل الصور ثم تشفيرها ثم تخزينها ثم استدعاءها عند الحاجة ومقارنتها بالصور المخزنة كما تم الشرح سابقا
ثم بعد ذلك يرسم الإطار على وجه الشخص ويكتب اسمه اسفل المربع
أيضا تم استخدام دالة التحويل بين نظامي RGB و BGR ما بين مكتبتي opencv و face-recognition.

نتائج المشروع مرفقة كصور وفيديو في ملف باسم results.
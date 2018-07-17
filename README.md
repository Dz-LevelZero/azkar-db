# azkar-db
 قاعدة بيانات مجانية، تحتوي على الأدعية والأذكار والرقية 

## الملفات
#### azkar-db
&#x202b; ملف قاعدة البيانات
ويستخدم قاعدة البيانات SQLite

&#x202b; يمكن قراءة وتعديل قاعدة البيانات باستخدام DB browser for SQLite، وهو برنامج مجاني يعمل على عدد من أنظمة التشغيل
http://sqlitebrowser.org/

#### azkar.json
&#x202b; ملف بصيغة json، يحتوي على نسخة من جدول الأذكار تم تصديره من قاعدة البيانات

يمكن استخدامه بدلا من قاعدة البيانات في مواقع الويب

#### azkar.csv
&#x202b; ملف بصيغة csv، يحتوي على نسخة من جدول الأذكار تم تصديره من قاعدة البيانات

يمكن القراءة والتعديل عليه بدلا من قاعدة البيانات، باستخدام جداول إكسل وغيرها من البرامج


## المسميات
قاعدة البيانات تحتوي على جدول واحد بإسم&#x202b;  azkar

الجدول يحتوي على خمسة أعمدة كما يلي&#x202b;:
* category : التصنيف
* zekr : الذكر أو الدعاء
* description : الوصف أو الشرح
* count : عدد التكرارات
* reference : المرجع للأحاديث والآيات


## تحت التطوير
* إضافة المرجع، عدد التكرارات، الشرح
* &#x202b; إستخدام الترميز utf-8 لجميع النصوص

## إضافة التعديلات
يفضل إجراء التعديلات على ملف قاعدة البيانات وليس الملفات الأخرى، لأن الملفات الأخرى يمكن تصديرها من قاعدة البيانات.

## للمساهمة والمساعدة
يمكن المساعدة فيما يلي&#x202b;:
* نشر وتوزيع قاعدة البيانات
* التبليغ عن الأخطاء
* إصلاح الأخطاء
* تحديث المعلومات المفقودة في قاعدة البيانات مثل المرجع للأحاديث والآيات

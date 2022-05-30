## Table of contents
- [Introduction](#Introduction)
- [Make first project](#Make-first-project)
- [Add files](#Add-files)
- [Make configuraion](#Make-configuration)
- [Make first commit](#Make-first-commit)
- [Push repository to github](#Push-repository-to-github)

## Introduction

المحتوي اللي هيتشرح علي 🅶🅸🆃 هيكون من كتاب pro git 
[لينك الكتاب](https://link.springer.com/book/10.1007/978-1-4842-0076-6 )


بالاضافة ال 🅳🅾🅲🆄🅼🅴🅽🆃🅰🆃🅸🅾🅽 
محتوي الكورس  هيبقي  شرح علي 🆈🅾🆄🆃🆄🅱🅴 + تطبيق عملي علي visual studio 
الكورس هيبقي لي أي واحد شغال في مجال software سواء كنت شغال

 🅲 , 🅲++ , 🅿🅷🅿 , 🅹🅰🆅🅰 ……🅴🆃🅲


  

ال git عامل زي الكاميرا اللي مثبتها قدام البيت بتراقب أي حركة في الشارع بحيث في أي وقت حصل حاجة تقدر ترجع للفيديو اللي سجلته الكاميرا في الوقت ده كذلك الأمر بالنسبة لل  git بيراقب أي ملفات أنت ضفتها أو عدلت عليها أو مسحتها وتقدر تشوف التعديل علي جزئية من الكود ال git هيوفر عليك وقت خرافي لو في مشكلة حصلت في الكود

أنا هستفيد ايه لما أتعلم ال 🅶🅸🆃 :
- هتقدر تدير ال 🆁🅾🅹🅴🅲🆃🅿 اللي أنت شغال عليه بكل سهولة
- هتعرف  الملفات اللي عدلت عليها بكل سهولة
- هتقدر تسترجع الملفات اللي حضرتك مسحتها بكل سهولة 
- ممكن تتراجع عن أي تعديل أنت عملته بأمر واحد فقط
- هتقدر تعمل بكل سهولة إصدارات من ال software اللي أنت شغال عليه
- أي مشكلة بتحصل تقدر تحلها بسرعة لان بيظهرلك الملفات اللي عدلت فيها فقط والجزئية اللي عدلت فيها في الملف
- لو أنت شغال في team هتقدر تعرف مين اللي كتب الكود وامتي وعدد الاسطر اللي كتابها والملفات اللي عدل عليها يعني مفيش حد هيتهم الثاني هو اللي كتب كود مش بتاعه
- كل واحد من ال team بيبقي ليه تاسك في ال project وبعد ما بينتهي منه بتعمل دمح في ال branch الرئيسية
- بمجرد ما تنتهي من ال task اللي أنت وأخدها بترفعه علي ال server سواء كان 
[Github](https://www.github.com/) أو [Gitlab](https://www.gitlab.com/)أو 
[Bitbucket](https://www.bitbucket.org/)

[رابط تحميل البرنامج](https://git-scm.com/download/win/)

## Make first project
إزاي نعمل أول 𝐩𝐫𝐨𝐣𝐞𝐜𝐭
ك 𝐠𝐢𝐭 𝐩𝐫𝐨𝐣𝐞𝐜𝐭 يبقي أول أمر هتتعلمه

```bash
git init
```

الامر git init بيعمل ايه - 
 علشان تبدأ المشروع كمشروع git  بس في الامر لازم أكون عامل انشاء للفولدر
 لو مش عامل إنشاء للفولدر هكتب اسم الفولدر بعد git init يعني الامر هيبقي بالشكل النهائي ده


```bash
git init FolderName
```

## Add files

هبدأ اعمل انشاء لملفات المشروع وبعد ما أكتب الكود هضيف الملفات لل git وعلشان اضيف الملفات هكتب اسم الملف  اللي هضيفه علي سبيل المثال

```bash
git add index.html
```

ممكن أضيف أكثر من ملف في نفس الامر

```bash
git add index.html search.html
```

علشان أعمل حفظ للملفات في ال 𝐠𝐢𝐭 لازم أمر اعمل 𝐜𝐨𝐦𝐦𝐢𝐭  للملفات اللي ضيفتها + أني لازم أكتب رسالة معبرة عن الملفات اللي ضفتها أو عدلت عليها علي سبيل مثال 𝐚𝐝𝐝 𝐬𝐮𝐦 𝐟𝐮𝐧𝐜𝐭𝐢𝐨𝐧 يعني الامر في نهاية هيبقي بالشكل ده

```bash
git commit –m "Write_Your_Message"
```

## Make configuration

لما تيجي تعمل commit هيظهرلك الرسالة ده

```bash
*** Please tell me who you are.
Run
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
to set your account's default identity.
Omit --global to set the identity only in this repository.
fatal: unable to auto-detect email address
```

معناها أنك لازم تعمل إعدادات لل git لازم تضيف الايميل واسم المستخدم اللي أنت هتستخدمهم 
وهنا هنقسم إعدادات ال 𝐠𝐢𝐭 للاعدادات عامة𝐠𝐥𝐨𝐛𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧  وإعدادات خاصة 𝐥𝐨𝐜𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 
ال global configuration بتطبق علي كل المشاريع اللي هتعملها بال  git 
```bash
git config --global user.email "you@example.com"

git config --global user.name "Your_UserName"
```

إمتي أستخدم ال local configuration لو أنت عايز تعمل الإعدادت علي المشروع الحالي فقط يعني مثال أنت عايز تدخل بالايميل واسم المستخدم اللي أنت شغال بيه في الشركة

```bash
git config  user.email "you@example.com"

git config  user.name "Your_UserName"
```

الاعدادات العامة بتبقي  إعدادت عامة علي كل المشاريع اللي هتعمل كمشاريع 𝐠𝐢𝐭   
والاعدادات الخاصة هتبقي علي المشروع اللي أنت شغال عليه

سؤال لان عندي 𝐠𝐥𝐨𝐛𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 ومعنديش 𝐥𝐨𝐜𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 هيبقي في الحالة ده ال  𝐠𝐥𝐨𝐛𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 هو اللي هيتنفد

طيب لو عندي global 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 وعندي ال 𝐥𝐨𝐜𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 اللي هيتنفذ في الحالة ده ال 𝐥𝐨𝐜𝐚𝐥 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 

## Make first commit
علشان أعمل حفظ للملفات في ال 𝐠𝐢𝐭 لازم أمر اعمل 𝐜𝐨𝐦𝐦𝐢𝐭  للملفات اللي ضيفتها + أني لازم أكتب رسالة معبرة عن الملفات اللي ضفتها أو عدلت عليها علي سبيل مثال 𝐚𝐝𝐝 𝐬𝐮𝐦 𝐟𝐮𝐧𝐜𝐭𝐢𝐨𝐧 يعني الامر في نهاية هيبقي بالشكل ده
```bash
git commit –m "add sum function"
```

هنلاحظ في الامر –𝐦 وده اختصار لل 𝐦𝐞𝐬𝐬𝐚𝐠𝐞 بدلا من كتابة الكلمة بالشكل الكامل ليها –𝐦𝐞𝐬𝐬𝐚𝐠𝐞
## Push repository to github
بعد ما عملت commit للملفات أنت محتاج ترفع 𝐫𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 اللي المشروع بتاعك علي موقع استضافة اللي بتدعم استضافة ال repositories المواقع ده زي github.com وgitlab.com  وbitbucket.org 
ايه الفرق بين الثالث 
-	علي 𝐠𝐢𝐭𝐡𝐮𝐛 المشروع بتاعك بيشوفه كل ال developers بيبقي 𝐩𝐮𝐛𝐥𝐢𝐜 𝐫𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 
وحاليا متاح 𝐩𝐫𝐢𝐯𝐚𝐭𝐞 𝐫𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 علي ال 𝐠𝐢𝐭𝐡𝐮𝐛 
- 	أما في ال gitlab وال bitbucket أنت بتحدد المشروع هيبقي public ولا private 
علشان اعمل push للمشروع علي 𝐠𝐢𝐭𝐡𝐮𝐛 لازم أنشئ repository جديدة علي ال 𝐠𝐢𝐭𝐡𝐮𝐛 وباخد رابط ال repository 
وببدأ أضيفه للمشروع اللي علي جهازي وعلشان أضيف الرابط بكتب الامر ده

```bash
git remote add origin url-link
```

علي سبيل المثال

```bash
git remote add origin https://github.com/userName/projectName.git
```


بعد ما عملت إضافة هبدأ أعمل 𝐩𝐮𝐬𝐡 ويبقي هكتب الامر ده 
```bash
git push origin master
```

طيب أنت هتسأل ايه هي ال 𝐨𝐫𝐢𝐠𝐢𝐧 ؟
هو الاسم المستعار للرابط بتاعك يعني لو أنت مش عامل إضافة للرابط كنت هتكتب الامر ده

```bash
git push https://github.com/userName/projectName.git master
```

إحنا عرفنا 𝐨𝐫𝐢𝐠𝐢𝐧 إيه هي ال 𝐦𝐚𝐬𝐭𝐞𝐫 ؟
ال 𝐦𝐚𝐬𝐭𝐞𝐫 هي اسم ال 𝐛𝐫𝐚𝐧𝐜𝐡 بتاعك يعني معني كده أنا هقدر أضيف أكتر من 𝐛𝐫𝐚𝐧𝐜𝐡 اه ينفع تضيف أكتر من 𝐛𝐫𝐚𝐧𝐜𝐡

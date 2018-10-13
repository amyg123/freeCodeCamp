---
title: Create an Export Fallback with export default
localeTitle: قم بإنشاء "تصدير تراجعي" باستخدام الإعداد الافتراضي للتصدير
---
## قم بإنشاء "تصدير تراجعي" باستخدام الإعداد الافتراضي للتصدير

ما هي القيمة الاحتياطية؟ إنه في الأساس افتراض أن الرمز سيعود إذا لم يتم تعيين أي شيء. على سبيل المثال ، تحتوي المتغيرات على القيمة الاحتياطية الافتراضية `undefined` . أن يقال ، تلميحا لهذا التحدي!

## تلميح 1:

ما عليك سوى إضافة `export default` إلى بداية الوظيفة.

## تنبيه المفسد - الحل إلى الأمام!

## حل:

 `"use strict"; 
 export default function subtract(x,y) {return x - y;} 
`
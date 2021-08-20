---
title: "Pytorch Vs Tensorflow 2021"
date: 2021-07-31
categories: ["مقالات"]
tags: ["Python", "Javascript", "TensorFlow", "Pytorch"]
cover:
    image: images/Pytorch_Vs_Tensorflow.png
    alt: "Pytorch_Vs_Tensorflow"
    caption: "Pytorch_Vs_Tensorflow"
---


## شو الفرق بين اخر نسخه من Tensorflow و Pytorch

المكتبتين تعتبران أكثر مكتبتين شهرة فى مجال تعليم الآلة: Tensorflow من تصميم شركة جوجل Google. وPytorch من تصميم فيس بوك Facebook سنقارن في هذا المقال بين أخر إصدارين منهما.

{{< ltr >}} ### Tensorflow 2.x: {{< /ltr >}}

هنالك الكثير من التعديلات بين Tensorflow 1 وبين Tensorflow 2.x

**📌أولاً إصدار Tensorflow.js🌐**

الي بتقدر من خلاله تبني موديل لصفحات الويب بدون الحاجة لاستخدام لغة البايثون🤩.
\
طبعاً من خلال Tensorflow.Js يمكنك أن تفعل أحد الموديل الي تم تطويرها باسخدام بايثون من خلال المتصفح باستخدام (Node)، أو إعادة تدريب موديل سابق، أو حتى بناء وتدريب موديل خاص باستخدام جافا سكريبت Javascript (من غير استخدم البايثون مثل المعتاد)

**📌ثانياً إصدار Tensorflow Lite🌀**

وهى مكتبة أخف للتعامل مع الموديل من خلال الهاتف 📲 أو الأجهزة المدمجة (embedded devices) مثل الأردوينو. من خلال TensorFlow Lite يمكن ببساطة تحويل الموديل الى (compressed flat buffer) وإعادة تحميله على الهاتف أو على أي جهاز مدمج آخر. تعتبر عملية التطوير الرئيسية هى التحول من 32bit الى 8bits والمناسب أكتر لأجهزة المدمجة بحيث يستخدم مساحة أقل.

**📌وأخيراً إصدار (Ternsorflow Extended (TFX 👨‍💻**

والي مكن مدير الإنتاج من تصميم خطة تطوير لموديل تعلم الآلة وساعد في حل التحديات المعروفة فى إنتاج السوفت وير مثل ال scalability وال maintainability وال modularity للموديل وكما ساعد فى تحديات تعليم الآلة مثل ال data validation and data management.🎯


{{< ltr >}} ### Pytorch 1.8: {{< /ltr >}}


**📍إصدار Pytorch mobile**

مثل tensorflow lite تم تطوير Pytorch mobile كإطار عمل يمكن من خلاله تتبع أو تحسين أو حتى حفظ النماذج فى كلا من الاندرويد وال iOS. وقد تم إصدار نسخه أوليه من Pytorch lite تقلل حجم التشغيل على أجهزة الهاتف.📲

**📍ثانيا إصدار pytorch profiler**

وهى أداة لاكتشاف أخطاء خوارزميات التعليم العميق ❌ وتصحيحها✅.

**📍إصدار Pytorch lightning**

على الرغم من أن Pytorch lightning لا يعتبر جزء من Pytorch 1.8، فقد تم إصدار Pytorch lightning لكي يسهل كتابة كود الشبكات العصبية (neural network). أي ببساطة من الممكن أعتباره Keras of Pytorch. السبب الذي يجعل Pytorch Lightning مهمه ل Pytorch هو أن Keras عملت دائما على تحسين Tensorflow مما جعل الخوارزميات أسهل وأقصر وهو الأمر الذي أجبر فيسبوك على القيام بنفس الخطوة🎯

[للمزيد من التفاصيل:](https://towardsdatascience.com/pytorch-vs-tensorflow-2021-d403504d7bc3)


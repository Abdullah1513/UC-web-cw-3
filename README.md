<p dir="rtl">
<h3><a href="https://github.com/kuwaitcodes/UC-web-cw-3">تمرين </a></h3></p>


<p dir="rtl">
اليوم راح نسوي هيكل لعبة X O بالـ Flexbox</p>
<h1></h1>
<p dir="rtl">
 <strong><a href="https://docs.google.com/document/d/1023yXN_P2S3_e7vzJ0kj4QXIqm7U-pkx1L-qUE5mMQA/edit">الجزء الاول</a></strong></p>


1. قم بعمل Fork
2. افتح الـrepo في github desktop
3. من برنامج github desktop اضغط على open in visual studio code
1. انشئ ملف بصيغة html وملف بصيغة css واربط بينهما باستخدام (link)
2. استخدم وسم h1 لتكتب جملة ترحيبية
` مثال: حياكم في لعبتي الجميلة`
3. في ملف الcss غير خصائص وسم h1 كالتالي:
    - نوع الخط = monospace `استخدم font-family`
    - اللون = orange
5. انشئ div (حاوية) وقم بإعطائه كلاس container وفي ملف الcss غير خصائص الكلاس كالتالي:
    - العرض = 500 بكسل (width)
6. انشئ div داخل (الحاوية) `container` وقم بإعطائه كلاس box وفي ملف الcss غير خصائص الكلاس كالتالي:
    - العرض = 150 بكسل (width)
    - الطول = 150 بكسل (height)
    - لون الخلفية = background-color) teal)
    - إزاحة هامشية = 1 بكسل (margin)
    - دوران الزوايا = 10 بكسل (border-radius)
    - تدرج الانتقالات = نص ثانيه لجميع التغيرات (transition) `transition -> all 0.5s`
    - حدود = 2 بكسل صلب ولون `border -> 2px solid darkkhaki` darkkhaki
7. في ملف الcss عند تمرير المؤشر على كلاس `on hover` box غير خصائص الكلاس:
    - لون الخلفية = background-color) turquoise)
8. انسخ وسم (div) الذي يحتوي على كلاس (box) 8 مرات اخرى `مجموعهم سوف يصبح 9 div's` 

<p dir="rtl">
<strong>بونص! ✨</strong></p>

- أضف ظلال بطريقة مناسبة `box shadow`

<h1></h1>

<p dir="rtl">
 <strong><a href="https://docs.google.com/document/d/1kbnHEY7YcWJmNOUaiURGab-6HFW-0dyDefd08m3XL8k/edit">الجزء الثاني</a></strong></p>

اكمل الخطوات في صفحة الcss

1. اضف هذه الخصائص إلى كلاس container `الذي قمت بإنشائه بالخطوة (6)`   :
    - طريقة العرض = فلكس `display -> flex`
    - محاذاة محور س = المنتصف `justify-content -> center`
    - محاذاة محور ص = المنتصف `align-items -> center`
    - فلكس راب = راب `flex-wrap -> wrap`

الان، لنجعل المكعبات تظهر في منتصف الصفحة</br>

2. قم بإضافة التغيرات التالية إلى الوسم الحاوي لجميع العناصر (body) :
    - طريقة العرض = فلكس `display -> flex`
    - اتجاه الحاوية = عمودي `flex-direction -> column`
    - محاذاة محور س = منتصف `align-items -> center`
    - محاذاة محور ص = منتصف `justify-content -> center`<br>
    - الطول = height) 100vh)
3. احفظ التغييرات وقم بعمل commit و push 
4. قم بتسليم التمرين على موقع <a href="https://lab.joincoded.com/dashboard/tasks">Coded Lab</a>



 <p dir="rtl">
<strong>بونص! ✨</strong></p>

- استخدم animation مع keyframes 😍


 <p dir="rtl">
"لا تترددون أنكم تسألون المدرسين 👌"
</p>

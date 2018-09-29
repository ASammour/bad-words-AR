# bad-words-AR

<div style = "direction:rtl;text-align:right;">
كود بسيط بالجافا سكريبت يعمل كفلتر لكشف النصوص التي تحتوي على ألفاظ نابية.


.هذا الكود يعتمد على قائمة يدوية للكلمات النابية، والألفاظ الخادشة المحتملة باللغة العربية

يُمكن استخدام هذا الكود بسهولة في المنتديات، أو المواقع الشخصية، أو المدونات التي تتيح نظام التعليقات لكل مقال.

A simple JavaScript code that works as a filter to detect text that contains profane words. This code is based on a manual list of bad dirty words in Arabic

This code can be easily used in forums, personal sites, or blogs that allow comments for each article.

```javascript
    $("form").submit (function (){
    	if (isDirty ($("input").val ()){
    		alert ("التعليق الذي قمت بإدخاله يحتوي ألفاظا نابية، الرجاء الالتزام بأدب النقاش");
    	}
    });
```

قبل ذلك قم بتضمين الملف داخل مشروعك كالآتي:

```javascript
    <!--استدعاء مكتبة الألفاظ النابية-->
    <script src="words.js"></script>
```

ملاحظة: الغرض الوحيد من ذكر هذه الكلمات النابية في الملف هو فقط لمحاولة منع التعليقات المسيئة، لذا يُرجى المعذرة.

</div>

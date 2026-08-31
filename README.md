# محاكيات نصيحة التفاعلية

محاكيات تعليمية بسيطة (HTML/Canvas بلا اعتماديات) تُستضاف عبر GitHub Pages
وتُضمَّن داخل دروس موقع الدورات (naseehamath.com) عبر `iframe`.

## المحاكيات

| المحاكاة | المسار | الوصف |
| --- | --- | --- |
| هل يمكن ضغط المادة؟ | `gas-compression/` | وعاء بمكبس: الغاز ينضغط لأن بين جسيماته فراغات كبيرة، والمادة الصلبة المتراصّة لا تنضغط |

## الاستخدام داخل درس

```html
<iframe src="https://thamer316.github.io/naseeha-simulations/gas-compression/"
        style="width:100%;max-width:680px;height:840px;border:0;display:block;margin:auto;"
        loading="lazy" title="محاكاة قابلية الانضغاط"></iframe>
```

## إضافة محاكاة جديدة

1. أنشئ مجلدًا جديدًا فيه `index.html` مستقل بذاته (بلا اعتماديات خارجية ما أمكن).
2. أضف بطاقة له في `index.html` بالجذر.
3. ادفع إلى `main` — تُنشر Pages تلقائيًا.

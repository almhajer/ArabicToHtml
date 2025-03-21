
<style>
    .command {
        background-color: #f0f8ff;
        color: #333;
        font-weight: bold;
        padding: 5px;
        border-radius: 5px;
        display: inline-block;
    }
</style>
### الوصف:

#### الأمر:
<span class='command'>صفحة</span>

#### الكود:
```html
<!DOCTYPE html>
<html lang='ar'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
 <title>${1:صفحة جديدة}</title>
</head>
<body>
 ${2}
</body>
</html>
```

### الوصف:

#### الأمر:
<span class='command'>عنوان الصفحة</span>

#### الكود:
```html
<title>${1:عنوان الصفحة}</title>
```

### الوصف:

#### الأمر:
<span class='command'>خصائص القيمة</span>

#### الكود:
```html
value="${1:قيمة افتراضية}"
```

### الوصف:

#### الأمر:
<span class='command'>خصائص الاسم</span>

#### الكود:
```html
name="${1:قيمة افتراضية}"
```

### الوصف:

#### الأمر:
<span class='command'>خصائص الفئة</span>

#### الكود:
```html
class="${1:قيمة افتراضية}"
```

### الوصف:

#### الأمر:
<span class='command'>خصائص المعرف</span>

#### الكود:
```html
id="${1:قيمة افتراضية}"
```

### الوصف:

#### الأمر:
<span class='command'>خصائص النمط</span>

#### الكود:
```html
style="${1:قيمة افتراضية}"
```

### الوصف:

#### الأمر:
<span class='command'>زر</span>

#### الكود:
```html
<button>${1:زر}</button
```

### الوصف:

#### الأمر:
<span class='command'>زر مع تنسيق</span>

#### الكود:
```html
<button name="${2:button}" class="${5:|button,key,press|}" id="button${3:1}" style="${4:background-color:red}">${1:زر}</button
```

### الوصف:

#### الأمر:
<span class='command'>زر ارسال</span>

#### الكود:
```html
<button>${1|فتح,اضغط,الغاء,اغلاق,جديد,تحويل|}</button
```

### الوصف:

#### الأمر:
<span class='command'>حقل نصي</span>

#### الكود:
```html
<input type="text" name="${1:inputName}" id="${2:inputId}" placeholder="${3:اكتب هنا}" />
```

### الوصف:

#### الأمر:
<span class='command'>حقل نصي مع خيارات</span>

#### الكود:
```html
<input type="text" ${1|value,name,class,id,style|}="${2}" />
```

### الوصف:

#### الأمر:
<span class='command'>رابط</span>

#### الكود:
```html
<a href="${1:https://www.example.com}" target="${2:_blank}">${3:رابط}</a>
```

### الوصف:

#### الأمر:
<span class='command'>صورة</span>

#### الكود:
```html
<img src="${1:https://www.example.com/image.jpg}" alt="${2:صورة}" />
```

### الوصف:

#### الأمر:
<span class='command'>جدول عدد العناصر 2</span>

#### الكود:
```html
<table>
    <thead>
        <tr>
            <th>${1:العنوان}</th>
            <th>${2:العنوان}</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>${3:القيمة}</td>
            <td>${4:القيمة}</td>
        </tr>
    </tbody>
</table>
```

### الوصف:

#### الأمر:
<span class='command'>صف جدول</span>

#### الكود:
```html
<tr>
    ${1:اضفة خلية البيانات}
</tr>
```

### الوصف:

#### الأمر:
<span class='command'>جدول</span>

#### الكود:
```html
<td>
    ${1:البيانات الأولى}
</td>
```

### الوصف:

#### الأمر:
<span class='command'>قائمة غير مرتبة</span>

#### الكود:
```html
<ul>
    <li>${1:العنصر}</li>
    <li>${2:العنصر}</li>
</ul>
```

### الوصف:

#### الأمر:
<span class='command'>لون احمر</span>

#### الكود:
```html
color: red;
```

### الوصف:

#### الأمر:
<span class='command'>لون أزرق</span>

#### الكود:
```html
color: blue;
```

### الوصف:

#### الأمر:
<span class='command'>لون أخضر</span>

#### الكود:
```html
color: green;
```

### الوصف:

#### الأمر:
<span class='command'>لون أصفر</span>

#### الكود:
```html
color: yellow;
```

### الوصف:

#### الأمر:
<span class='command'>لون أسود</span>

#### الكود:
```html
color: black;
```

### الوصف:

#### الأمر:
<span class='command'>لون أبيض</span>

#### الكود:
```html
color: white;
```

### الوصف:

#### الأمر:
<span class='command'>لون رمادي</span>

#### الكود:
```html
color: gray;
```

### الوصف:

#### الأمر:
<span class='command'>لون بنفسجي</span>

#### الكود:
```html
color: purple;
```

### الوصف:

#### الأمر:
<span class='command'>لون برتقالي</span>

#### الكود:
```html
color: orange;
```

### الوصف:

#### الأمر:
<span class='command'>لون وردي</span>

#### الكود:
```html
color: pink;
```

### الوصف:

#### الأمر:
<span class='command'>لون بني</span>

#### الكود:
```html
color: brown;
```

### الوصف:

#### الأمر:
<span class='command'>لون سماوي</span>

#### الكود:
```html
color: cyan;
```

### الوصف:

#### الأمر:
<span class='command'>لون أرجواني</span>

#### الكود:
```html
color: magenta;
```

### الوصف:

#### الأمر:
<span class='command'>لون ليموني</span>

#### الكود:
```html
color: lime;
```

### الوصف:

#### الأمر:
<span class='command'>لون ذهبي</span>

#### الكود:
```html
color: gold;
```

### الوصف:

#### الأمر:
<span class='command'>لون فضي</span>

#### الكود:
```html
color: silver;
```

### الوصف:

#### الأمر:
<span class='command'>لون كحلي</span>

#### الكود:
```html
color: navy;
```

### الوصف:

#### الأمر:
<span class='command'>لون زيتوني</span>

#### الكود:
```html
color: olive;
```

### الوصف:

#### الأمر:
<span class='command'>لون تركواز</span>

#### الكود:
```html
color: teal;
```

### الوصف:

#### الأمر:
<span class='command'>لون خمري</span>

#### الكود:
```html
color: maroon;
```

### الوصف:

#### الأمر:
<span class='command'>لون بيج</span>

#### الكود:
```html
color: beige;
```

### الوصف:

#### الأمر:
<span class='command'>حاوية</span>

#### الكود:
```html
<div style="width: ${1:200}px; height: ${2:100}px; background-color: ${3:lightgray};">
    ${4:محتوى القسم}
</div>
```

### الوصف:

#### الأمر:
<span class='command'>نص</span>

#### الكود:
```html
<span style="font-family: ${1:Arial}; font-size: ${2:16}px; font-weight: ${3:normal}; color: ${4:black};">
    ${5:نص هنا}
</span>
```

### الوصف:

#### الأمر:
<span class='command'>فقرة</span>

#### الكود:
```html
<p style="font-size: ${1:16}px; color: ${2:black}; text-align: ${3:left}; line-height: ${4:1.5};">
    ${5:نص الفقرة هنا}
</p>
```

### الوصف:

#### الأمر:
<span class='command'>فاصل</span>

#### الكود:
```html
<hr style="width: ${1:100%}; height: ${2:2}px; background-color: ${3:#000}; border: none; margin: ${4:10}px 0;">
```

### الوصف:

#### الأمر:
<span class='command'>حقل رقم سري</span>

#### الكود:
```html
<input type="password" name="${1:password}" id="${2:password}" placeholder="${3:أدخل كلمة المرور}" required>
```

### الوصف:

#### الأمر:
<span class='command'>فيديو</span>

#### الكود:
```html
<video width="${1:640}" height="${2:360}" controls>
    <source src="${3:video.mp4}" type="${4:video/mp4}">
    ${5:متصفحك لا يدعم تشغيل الفيديو.}
</video>
```

### الوصف:

#### الأمر:
<span class='command'>حقل نصي متعدد</span>

#### الكود:
```html
<textarea name="${1:textareaName}" id="${2:textareaId}" rows="${3:4}" cols="${4:50}" placeholder="${5:اكتب هنا}">${6}</textarea>
```

### الوصف:

#### الأمر:
<span class='command'>مقطع صوتي</span>

#### الكود:
```html
<audio controls>
    <source src="${1:audio.mp3}" type="${2:audio/mpeg}">
    ${3:متصفحك لا يدعم تشغيل الصوت.}
</audio>
```

### الوصف:

#### الأمر:
<span class='command'>نص عريض</span>

#### الكود:
```html
<b>${1:نص عريض هنا}</b>
```

### الوصف:

#### الأمر:
<span class='command'>اقتباس</span>

#### الكود:
```html
<blockquote style="font-size: ${1:16}px; color: ${2:gray}; border-left: ${3:4px solid #ccc}; padding: ${4:10px}; margin: ${5:10px 0};">
    ${6:نص الاقتباس هنا}
</blockquote>
```

### الوصف:

#### الأمر:
<span class='command'>نموذج</span>

#### الكود:
```html
<form action="${1:submit.php}" method="${2:post}" ${3:enctype="multipart/form-data"}>
    <label for="${4:inputId}">${5:اسم الحقل}</label>
    <input type="${6:text}" name="${7:inputName}" id="${4:inputId}" placeholder="${8:اكتب هنا}" />
    <button type="${9:submit}">${10:إرسال}</button>
</form>
```

### الوصف:

#### الأمر:
<span class='command'>عنوان</span>

#### الكود:
```html
<h1 style="font-size: ${1:32}px; color: ${2:black}; text-align: ${3:left};">
    ${4:عنوان هنا}
</h1>
```

### الوصف:

#### الأمر:
<span class='command'>رابط ملف التنسيق</span>

#### الكود:
```html
<link rel="${1:stylesheet}" href="${2:style.css}" type="${3:text/css}" />
```

### الوصف:

#### الأمر:
<span class='command'>جافا سكريبت</span>

#### الكود:
```html
<script type="${1|text/javascript,module|}">
    ${2:// اكتب كود JavaScript هنا}
</script>
```

### الوصف:

#### الأمر:
<span class='command'>قائمة منسدلة</span>

#### الكود:
```html
<select name="${1:selectName}" id="${2:selectId}">
    <option value="${3:option1Value}">${4:الخيار الأول}</option>
    <option value="${5:option2Value}">${6:الخيار الثاني}</option>
</select>
```

### الوصف:

#### الأمر:
<span class='command'>خيار</span>

#### الكود:
```html
<option value="${1:القيمة}">${2:النص}</option>
```

### الوصف:

#### الأمر:
<span class='command'>تنسيق</span>

#### الكود:
```html
<style>
    ${1:/* اكتب كود CSS هنا */}
</style>
```

### الوصف:

#### الأمر:
<span class='command'>رابط جافا سكريبت خارجي</span>

#### الكود:
```html
<script src="${1:script.js}" type="${2:text/javascript}"></script>
```

### الوصف:

#### الأمر:
<span class='command'>قائمة </span>

#### الكود:
```html
<menu>
    <li>${1:العنصر الأول}</li>
    <li>${2:العنصر الثاني}</li>
</menu>
```

### الوصف:

#### الأمر:
<span class='command'>عنصر قائمة</span>

#### الكود:
```html
<li>${1:العنصر}</li>
```

### الوصف:

#### الأمر:
<span class='command'>صور بحسب مقاس المحدد</span>

#### الكود:
```html
<picture>
    <source srcset="${1:example-large.jpg}" media="(min-width: ${2:800px})">
    <source srcset="${3:example-medium.jpg}" media="(min-width: ${4:400px})">
    <img src="${5:example-small.jpg}" alt="${6:وصف الصورة}">
</picture>
```

### الوصف:

#### الأمر:
<span class='command'>زر ادخال صورة</span>

#### الكود:
```html
<input type="file" id="${1:poster}" name="${2:poster}" accept="${3:image/png, image/jpeg}" />
```

### الوصف:

#### الأمر:
<span class='command'>زر ادخال ملف PDF</span>

#### الكود:
```html
<input type="file" id="${1:pdfFile}" name="${2:pdfFile}" accept="${3:application/pdf}" />
```


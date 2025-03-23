# دليل استخدام السنابيتات (Snippets Guide)

## الوصف
هذا الملف يحتوي على جميع السنابيتات المتوفرة في الإضافة، مع وصف لكل عنصر والكود الخاص به.

---

## قائمة السنابيتات

### 1. صفحة HTML جديدة
#### الأمر: `صفحة`
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

---

### 2. عنوان الصفحة
#### الأمر: `عنوان الصفحة`
```html
<title>${1:عنوان الصفحة}</title>
```

---

### 3. خصائص القيمة
#### الأمر: `خصائص القيمة`
```html
value="${1:قيمة افتراضية}"
```

---

### 4. خصائص الاسم
#### الأمر: `خصائص الاسم`
```html
name="${1:قيمة افتراضية}"
```

---

### 5. خصائص الفئة
#### الأمر: `خصائص الفئة`
```html
class="${1:قيمة افتراضية}"
```

---

### 6. خصائص المعرف
#### الأمر: `خصائص المعرف`
```html
id="${1:قيمة افتراضية}"
```

---

### 7. خصائص النمط
#### الأمر: `خصائص النمط`
```html
style="${1:قيمة افتراضية}"
```

---

### 8. زر
#### الأمر: `زر`
```html
<button>${1:زر}</button>
```

---

### 9. زر مع تنسيق
#### الأمر: `زر مع تنسيق`
```html
<button name="${2:button}" class="${5|button,key,press|}" id="button${3:1}" style="${4:background-color:red}">${1:زر}</button>
```

---

### 10. زر إرسال
#### الأمر: `زر ارسال`
```html
<button>${1|فتح,اضغط,الغاء,اغلاق,جديد,تحويل|}</button>
```

---

### 11. حقل نصي
#### الأمر: `حقل نصي`
```html
<input type="text" name="${1:inputName}" id="${2:inputId}" placeholder="${3:اكتب هنا}" />
```

---

### 12. حقل نصي مع خيارات
#### الأمر: `حقل نصي مع خيارات`
```html
<input type="text" ${1|value,name,class,id,style|}="${2}" />
```

---

### 13. رابط
#### الأمر: `رابط`
```html
<a href="${1:https://www.example.com}" target="${2:_blank}">${3:رابط}</a>
```

---

### 14. صورة
#### الأمر: `صورة`
```html
<img src="${1:https://www.example.com/image.jpg}" alt="${2:صورة}" />
```

---

### 15. جدول
#### الأمر: `جدول`
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

---

### 16. صف جدول
#### الأمر: `صف جدول`
```html
<tr>
    ${1:اضفة خلية البيانات}
</tr>
```

---

### 17. قائمة غير مرتبة
#### الأمر: `قائمة غير مرتبة`
```html
<ul>
    <li>${1:العنصر}</li>
    <li>${2:العنصر}</li>
</ul>
```

---

### 18. لون أحمر
#### الأمر: `لون احمر`
```css
color: red;
```

---

### 19. لون أزرق
#### الأمر: `لون أزرق`
```css
color: blue;
```

---

### 20. لون أخضر
#### الأمر: `لون أخضر`
```css
color: green;
```

---

### 21. لون أصفر
#### الأمر: `لون أصفر`
```css
color: yellow;
```

---

### 22. لون أسود
#### الأمر: `لون أسود`
```css
color: black;
```

---

### 23. لون أبيض
#### الأمر: `لون أبيض`
```css
color: white;
```

---

### 24. لون رمادي
#### الأمر: `لون رمادي`
```css
color: gray;
```

---

### 25. حاوية
#### الأمر: `حاوية`
```html
<div style="width: ${1:200}px; height: ${2:100}px; background-color: ${3:lightgray};">
    ${4:محتوى القسم}
</div>
```

---

### 26. نص
#### الأمر: `نص`
```html
<span style="font-family: ${1:Arial}; font-size: ${2:16}px; font-weight: ${3:normal}; color: ${4:black};">
    ${5:نص هنا}
</span>
```

---

### 27. فقرة
#### الأمر: `فقرة`
```html
<p style="font-size: ${1:16}px; color: ${2:black}; text-align: ${3:left}; line-height: ${4:1.5};">
    ${5:نص الفقرة هنا}
</p>
```

---

### 28. فاصل
#### الأمر: `فاصل`
```html
<hr style="width: ${1:100%}; height: ${2:2}px; background-color: ${3:#000}; border: none; margin: ${4:10}px 0;">
```

---

### 29. حقل رقم سري
#### الأمر: `حقل رقم سري`
```html
<input type="password" name="${1:password}" id="${2:password}" placeholder="${3:أدخل كلمة المرور}" required>
```

---

### 30. فيديو
#### الأمر: `فيديو`
```html
<video width="${1:640}" height="${2:360}" controls>
    <source src="${3:video.mp4}" type="${4:video/mp4}">
    ${5:متصفحك لا يدعم تشغيل الفيديو.}
</video>
```

---

### 31. حقل نصي متعدد
#### الأمر: `حقل نصي متعدد`
```html
<textarea name="${1:textareaName}" id="${2:textareaId}" rows="${3:4}" cols="${4:50}" placeholder="${5:اكتب هنا}">${6}</textarea>
```

---

### 32. مقطع صوتي
#### الأمر: `مقطع صوتي`
```html
<audio controls>
    <source src="${1:audio.mp3}" type="${2:audio/mpeg}">
    ${3:متصفحك لا يدعم تشغيل الصوت.}
</audio>
```

---

### 33. نص عريض
#### الأمر: `نص عريض`
```html
<b>${1:نص عريض هنا}</b>
```

---

### 34. اقتباس
#### الأمر: `اقتباس`
```html
<blockquote style="font-size: ${1:16}px; color: ${2:gray}; border-left: ${3:4px solid #ccc}; padding: ${4:10px}; margin: ${5:10px 0};">
    ${6:نص الاقتباس هنا}
</blockquote>
```

---

### 35. نموذج
#### الأمر: `نموذج`
```html
<form action="${1:submit.php}" method="${2:post}" ${3:enctype="multipart/form-data"}>
    <label for="${4:inputId}">${5:اسم الحقل}</label>
    <input type="${6:text}" name="${7:inputName}" id="${4:inputId}" placeholder="${8:اكتب هنا}" />
    <button type="${9:submit}">${10:إرسال}</button>
</form>
```

---

### 36. عنوان
#### الأمر: `عنوان`
```html
<h1 style="font-size: ${1:32}px; color: ${2:black}; text-align: ${3:left};">
    ${4:عنوان هنا}
</h1>
```

---

### 37. رابط ملف التنسيق
#### الأمر: `رابط ملف التنسيق`
```html
<link rel="${1:stylesheet}" href="${2:style.css}" type="${3:text/css}" />
```

---

### 38. جافا سكريبت
#### الأمر: `جافا سكريبت`
```html
<script type="${1|text/javascript,module|}">
    ${2:// اكتب كود JavaScript هنا}
</script>
```

---

### 39. قائمة منسدلة
#### الأمر: `قائمة منسدلة`
```html
<select name="${1:selectName}" id="${2:selectId}">
    <option value="${3:option1Value}">${4:الخيار الأول}</option>
    <option value="${5:option2Value}">${6:الخيار الثاني}</option>
</select>
```

---

### 40. خيار
#### الأمر: `خيار`
```html
<option value="${1:القيمة}">${2:النص}</option>
```

---

### 41. تنسيق
#### الأمر: `تنسيق`
```html
<style>
    ${1:/* اكتب كود CSS هنا */}
</style>
```

---

### 42. رابط جافا سكريبت خارجي
#### الأمر: `رابط جافا سكريبت خارجي`
```html
<script src="${1:script.js}" type="${2:text/javascript}"></script>
```

---

### 43. قائمة
#### الأمر: `قائمة`
```html
<menu>
    <li>${1:العنصر الأول}</li>
    <li>${2:العنصر الثاني}</li>
</menu>
```

---

### 44. عنصر قائمة
#### الأمر: `عنصر قائمة`
```html
<li>${1:العنصر}</li>
```

---

### 45. صور بحسب مقاس المحدد
#### الأمر: `صور بحسب مقاس المحدد`
```html
<picture>
    <source srcset="${1:example-large.jpg}" media="(min-width: ${2:800px})">
    <source srcset="${3:example-medium.jpg}" media="(min-width: ${4:400px})">
    <img src="${5:example-small.jpg}" alt="${6:وصف الصورة}">
</picture>
```

---

### 46. زر إدخال صورة
#### الأمر: `زر إدخال صورة`
```html
<input type="file" id="${1:poster}" name="${2:poster}" accept="${3:image/png, image/jpeg}" />
```

---

### 47. زر إدخال ملف PDF
#### الأمر: `زر إدخال ملف PDF`
```html
<input type="file" id="${1:pdfFile}" name="${2:pdfFile}" accept="${3:application/pdf}" />
```

---

### 48. قائمة تعريفات
#### الأمر: `قائمة تعريفات`
```html
<dl>
  <dt>${1:العنوان}</dt>
  <dd>${2:الوصف}</dd>
</dl>
```

---

### 49. نص مائل
#### الأمر: `نص مائل`
```html
<em>${1:نص مائل هنا}</em>
```

---

### 50. نص يتوسطه خط
#### الأمر: `نص يتوسطه خط`
```html
<del>${1:النص}</del>
```

---

### 51. نص مسطر
#### الأمر: `نص مسطر`
```html
<ins>${1:النص المضاف}</ins>
```

---

### 52. قالب نموذج شخصي
#### الأمر: `قالب نموذج شخصي`
```html
<form action="${1:/action_page.php}" method="${2:post}">
 <fieldset>
  <legend>${3:Personalia}:</legend>
  <label for="fname">${4:First name}:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">${5:Last name}:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">${6:Email}:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">${7:Birthday}:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="${8:Submit}">
 </fieldset>
</form>
```

---

### 53. حقل تاريخ
#### الأمر: `حقل تاريخ`
```html
<input type="date" id="${1:birthday}" name="${2:birthday}" />
```

---

### 54. قائمة شريط تنقل
#### الأمر: `قائمة شريط تنقل`
```html
<nav>
  <a href="${1:/html/}">${2:الرابط الأول}</a>
  <a href="${3:/css/}">${4:الرابط الثاني}</a>
</nav>
```

---

### 55. خريطة صورة
#### الأمر: `خريطة صورة`
```html
<img src="${1:workplace.jpg}" alt="${2:Workplace}" usemap="#${3:workmap}" width="${4:400}" height="${5:379}">
<map name="${3:workmap}">
  <area shape="rect" coords="${6:34,44,270,350}" alt="${7:Computer}" href="${8:computer.htm}">
  <area shape="rect" coords="${9:290,172,333,250}" alt="${10:Phone}" href="${11:phone.htm}">
  <area shape="circle" coords="${12:337,300,44}" alt="${13:Cup of coffee}" href="${14:coffee.htm}">
</map>
```

---

### 56. شريط نسبة التقدم
#### الأمر: `شريط نسبة التقدم`
```html
<label for="${1:file}">${2:وصف التقدم}:</label>
<progress id="${1:file}" value="${3:القيمة الحالية}" max="${4:القيمة القصوى}">${5:النسبة المئوية}</progress>
```

---

### 57. مقياس نسبة
#### الأمر: `مقياس نسبة`
```html
<meter id="${1:meterId}" value="${2:القيمة الحالية}" min="${3:القيمة الدنيا}" max="${4:القيمة القصوى}">${5:الوصف هنا}</meter>
```

---

## ملاحظات
شكرا جزيلا بالتوفيق
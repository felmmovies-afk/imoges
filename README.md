# 📸 ImageHost - تطبيق رفع الصور الفوري والحفاظ على الجودة الأصلية

> **ImageHost** هو تطبيق ويب حديث وسريع يتيح لك رفع الصور بجميع الصيغ والتنسيقات والحصول على رابط مباشر وفوري لمشاركتها دون أي فقدان للجودة أو ضغط للألوان.

---

## 🌟 المميزات الرئيسية

* **رفع فوري وبأقصى سرعة:** رفع مباشر وسريع للصور باستخدام استضافة Cloud Storage فائقة السرعة عبر Supabase[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span).
* **جودة أصلية 100%:** نضمن عدم ضغط الصور أو تعديل ألوانها أو تقليل دقتها كما تفعل منصات التواصل الاجتماعي (مثل واتساب وتليجرام وفيسبوك)[span_9](start_span)[span_9](end_span)[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span)[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span)[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span).
* **رابط مباشر وفوري:** الحصول على رابط مباشر بنقرة واحدة لتسهيل مشاركة الصورة على أي منصة[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span)[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span)[span_21](start_span)[span_21](end_span)[span_22](start_span)[span_22](end_span).
* **دعم كافة التنسيقات:** يغطي صيغ PNG, JPG, JPEG, WEBP, GIF, SVG, وغيرها[span_23](start_span)[span_23](end_span)[span_24](start_span)[span_24](end_span)[span_25](start_span)[span_25](end_span)[span_26](start_span)[span_26](end_span)[span_27](start_span)[span_27](end_span)[span_28](start_span)[span_28](end_span)[span_29](start_span)[span_29](end_span).
* **سجل رفع محلي:** حفظ الصور التي تم رفعها في ذاكرة المتصفح للوصول إليها وإعادة نسخ روابطها في أي وقت[span_30](start_span)[span_30](end_span)[span_31](start_span)[span_31](end_span)[span_32](start_span)[span_32](end_span)[span_33](start_span)[span_33](end_span)[span_34](start_span)[span_34](end_span)[span_35](start_span)[span_35](end_span)[span_36](start_span)[span_36](end_span).
* **أدوات مشاركة متقدمة:** توفير روابط صريحة (Direct Link) بالإضافة إلى كود HTML وكود Markdown لإدراج الصور في المواقع والمدونات بسهولة[span_37](start_span)[span_37](end_span)[span_38](start_span)[span_38](end_span)[span_39](start_span)[span_39](end_span)[span_40](start_span)[span_40](end_span)[span_41](start_span)[span_41](end_span)[span_42](start_span)[span_42](end_span)[span_43](start_span)[span_43](end_span).

---

## 🛠️ التقنيات المستخدمة

* **Front-End:** HTML5, CSS3 (Modern UI / Glassmorphism Design), JavaScript (ES6+).
* **Backend & Storage:** Supabase Storage (Public Bucket)[span_44](start_span)[span_44](end_span)[span_45](start_span)[span_45](end_span)[span_46](start_span)[span_46](end_span)[span_47](start_span)[span_47](end_span)[span_48](start_span)[span_48](end_span)[span_49](start_span)[span_49](end_span)[span_50](start_span)[span_50](end_span).
* **Storage Bucket Name:** `images`[span_51](start_span)[span_51](end_span)[span_52](start_span)[span_52](end_span).

---

## 🚀 كيفية الاستخدام

1. **الرفع:** قم بسحب وإفلات الصورة في المربع المخصص، أو انقر على **"اختر صورة من جهازك"**[span_53](start_span)[span_53](end_span)[span_54](start_span)[span_54](end_span)[span_55](start_span)[span_55](end_span)[span_56](start_span)[span_56](end_span)[span_57](start_span)[span_57](end_span)[span_58](start_span)[span_58](end_span)[span_59](start_span)[span_59](end_span).
2. **استخراج الرابط:** بمجرد اكتمال الرفع، سيظهر لك رابط الصورة المباشر فوراً[span_60](start_span)[span_60](end_span)[span_61](start_span)[span_61](end_span)[span_62](start_span)[span_62](end_span)[span_63](start_span)[span_63](end_span)[span_64](start_span)[span_64](end_span)[span_65](start_span)[span_65](end_span)[span_66](start_span)[span_66](end_span).
3. **النسخ والمشاركة:** اضغط على **"نسخ الرابط"** وشاركه عبر أي تطبيق دون القلق بشأن تغير الألوان أو انخفاض الجودة[span_67](start_span)[span_67](end_span)[span_68](start_span)[span_68](end_span)[span_69](start_span)[span_69](end_span)[span_70](start_span)[span_70](end_span)[span_71](start_span)[span_71](end_span)[span_72](start_span)[span_72](end_span)[span_73](start_span)[span_73](end_span).

---

## ⚙️ التثبيت والإعداد المحلّي

لتشغيل المشروع محلياً، قم بتعديل متغيرات البيئة الخاصة بـ Supabase في كود JavaScript:

```javascript
const SUPABASE_URL = "YOUR_SUPABASE_URL";
const SUPABASE_KEY = "YOUR_SUPABASE_ANON_KEY";
const BUCKET_NAME = "images";

# 📐 وثيقة المعمارية — مشروع اتصالApi لموقع vyce-ai

**المستودع:** `Dev-saged/Vyce-Ai`  
**تاريخ التوليد:** ١١ سبتمبر ٢٠٢٦  
**الإصدار:** v3.0.0  
**إجمالي الأسطر:** 2,028 سطر  
**نوع المشروع:** ويب — ملف HTML واحد (Offline-capable)  

---

## 🏗️ نظرة عامة على النظام

**Stack التقني:** HTML5/CSS3 · CSS Custom Properties  
**GitHub:** [Dev-saged/Vyce-Ai](https://github.com/Dev-saged/Vyce-Ai)  

## 📦 الوحدات والأقسام الرئيسية

- Auth
- Overlay
- App
- Sidebar
- Search Modal
- Templates Modal
- Code Runner Modal
- Diff Modal
- Settings Modal

## 📁 ملفات المشروع

| الملف | الأسطر | الدوال | المكونات | المسارات |
|---|---|---|---|---|
| `vyce-ai-v3-2.html` | ٢٬٠٢٨ | 4 | 0 | 0 |

## ⚙️ الدوال الرئيسية (4 دالة)

### `vyce-ai-v3-2.html`
- `setupMarked()`
- `checkUpdate()`
- `ar()`
- `setVH()`


## 💾 مخطط التخزين المحلي

- `_vk`
- `_last`

## ⚠️ القيود التقنية والمعمارية

- التخزين محلي فقط (localStorage) — حد ~5–10 MB
- يعمل بدون خادم في الوضع الأساسي
- التشفير: XOR cipher (حماية من الفضول، ليس تشفير قوي)
- كل الشبكة مُغلّفة بـ try/catch مع fallback للوضع الأوفلاين
- لا secrets في الكود — التوكنات مشفرة ومخزنة محلياً

---

*تم التوليد تلقائياً بواسطة Release Manager Pro v2.6.0 — ١١ سبتمبر ٢٠٢٦*

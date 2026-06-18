# مشعل بن محمد للعود — موقع الويب

## هيكل المشروع

```
mishal-oud/
├── index.html        ← الصفحة الرئيسية
├── style.css         ← جميع الأنماط
├── README.md         ← هذا الملف
└── images/
    └── hero.jpg      ← صورة العود الرئيسية (أضفها يدوياً)
```

## الصورة المطلوبة

أضف صورة عود فاخر باسم `hero.jpg` داخل مجلد `images/`.
- الأبعاد المثالية: **1800×1200px** على الأقل
- الصيغة: JPG أو WEBP
- الحجم: أقل من 500KB (استخدم [squoosh.app](https://squoosh.app) للضغط)

---

## النشر على GitHub + Vercel

### 1. رفع على GitHub

```bash
git init
git add .
git commit -m "first commit: mishal oud website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mishal-oud.git
git push -u origin main
```

### 2. النشر على Vercel

1. افتح [vercel.com](https://vercel.com) وسجل الدخول بحساب GitHub
2. اضغط **"Add New Project"**
3. اختر `mishal-oud` من قائمة repositories
4. اضغط **"Deploy"** — لا تحتاج أي إعدادات إضافية
5. سيعطيك Vercel رابط `https://` تلقائياً ✅

> **ملاحظة:** Vercel يدعم HTTPS تلقائياً بدون أي إعداد.

---

## تخصيص الموقع

| الملف | ما تغيره |
|-------|----------|
| `index.html` | النصوص، الأسعار، المنتجات، رقم الهاتف |
| `style.css` | الألوان، الخطوط، المسافات |
| `images/hero.jpg` | صورة الخلفية الرئيسية وصورة المنتج الأول |

---

© 2026 مشعل بن محمد للعود

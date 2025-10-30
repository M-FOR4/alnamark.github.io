# 📘 دليل النشر على GitHub Pages - خطوة بخطوة

## 🎯 الهدف: الحصول على رابط للموقع مثل `https://alnamark.github.io`

---

## الخطوة 1️⃣: إنشاء حساب على GitHub

1. **اذهب إلى الموقع:** https://github.com
2. **اضغط على "Sign Up"** (التسجيل) في الأعلى
3. **املأ البيانات التالية:**
   - البريد الإلكتروني الخاص بك
   - كلمة مرور قوية
   - **اسم المستخدم (Username)** - **مهم جداً!** ✨
     - هذا الاسم سيكون جزء من رابط موقعك
     - مثال: إذا اخترت `alnamark` سيصبح رابطك: **`https://alnamark.github.io`**
     - اختر اسم قصير وسهل التذكر
4. **أكمل التحقق** من الإيميل

---

## الخطوة 2️⃣: إنشاء مستودع (Repository) جديد

1. **بعد تسجيل الدخول**، اضغط على زر **"+"** في أعلى يمين الصفحة
2. **اختر "New repository"**
3. **املأ معلومات المستودع:**
   
   **Repository name (اسم المستودع):**
   ```
   اسم-المستخدم-الخاص-بك.github.io
   - اجعله Public
   - اضغط "Create repository"

3. **رفع الملفات**
   - اسحب جميع الملفات والمجلدات إلى المستودع
   - أو استخدم الأمر التالي في Terminal:

```bash
cd c:/Users/HP/Desktop/ALNAAS
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/alnaas-furniture.git
git push -u origin main
```

4. **تفعيل GitHub Pages**
   - اذهب إلى Settings في المستودع
   - اختر "Pages" من القائمة الجانبية
   - تحت "Source"، اختر branch: `main` و folder: `/ (root)`
   - اضغط Save

5. **الموقع جاهز!**
   - سيكون موقعك متاحاً على:
   - `https://YOUR-USERNAME.github.io/alnaas-furniture/`

---

### English Steps:

1. **Create GitHub Account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create New Repository**
   - Click "New" or "+" button
   - Repository name: `alnaas-furniture`
   - Make it Public
   - Click "Create repository"

3. **Upload Files**
   - Drag and drop all files and folders
   - Or use command line:

```bash
cd c:/Users/HP/Desktop/ALNAAS
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/alnaas-furniture.git
git push -u origin main
```

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Select "Pages" from sidebar
   - Under "Source", choose branch: `main` and folder: `/ (root)`
   - Click Save

5. **Your Site is Live!**
   - Your website will be available at:
   - `https://YOUR-USERNAME.github.io/alnaas-furniture/`

---

## 🔗 بدائل أخرى للنشر - Other Hosting Alternatives

### 1. Netlify (سهل جداً - Very Easy)
- اذهب إلى https://www.netlify.com
- اسحب مجلد المشروع بالكامل
- الموقع جاهز فوراً!

### 2. Vercel
- https://vercel.com
- قم بربط حساب GitHub
- استورد المستودع

### 3. Cloudflare Pages
- https://pages.cloudflare.com
- ربط GitHub repository
- نشر تلقائي

---

## ⚙️ معلومات تقنية مهمة - Important Technical Info

### الملفات المطلوبة للنشر:
- ✅ index.html
- ✅ css/style.css
- ✅ js/script.js
- ✅ images/ (folder)

### لا حاجة لتحميل:
- ❌ .gitignore (ملف GitHub فقط)
- ❌ README.md (اختياري)
- ❌ DEPLOYMENT.md (اختياري)

---

## 🧪 اختبار محلي - Local Testing

لاختبار الموقع محلياً قبل النشر:

### الطريقة 1: Python
```bash
cd c:/Users/HP/Desktop/ALNAAS
python -m http.server 8000
```
ثم افتح: http://localhost:8000

### الطريقة 2: VS Code Extension
- ثبت "Live Server" extension
- انقر بالزر الأيمن على index.html
- اختر "Open with Live Server"

### الطريقة 3: Node.js
```bash
npx http-server
```

---

## 📞 بيانات الاتصال الحالية - Current Contact Info

تذكر تحديث بيانات الاتصال في `index.html`:

```html
<!-- Current Contact Information -->
Phone: +218 91 234 5678
Email: info@alnaas.com
Address: طرابلس – شارع الجرابة
```

---

## ✅ قائمة التحقق قبل النشر - Pre-Deployment Checklist

- [ ] تحديث رقم الهاتف الصحيح
- [ ] تحديث البريد الإلكتروني الصحيح
- [ ] تحديث العنوان إذا لزم الأمر
- [ ] إضافة صور مخصصة (اختياري)
- [ ] اختبار الموقع محلياً
- [ ] التحقق من عمل نموذج طلب السعر
- [ ] اختبار على الموبايل

---

**بالتوفيق! - Good Luck!**

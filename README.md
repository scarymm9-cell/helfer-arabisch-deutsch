# Helfer Arabisch Deutsch

تطبيق React/Vite جاهز للرفع على Netlify. الفكرة: تطبيق عربي-ألماني يساعد المهاجرين في ألمانيا على فهم الرسائل الرسمية، كتابة الردود، وتجهيز الكلام للطبيب والصيدلية.

## التشغيل على الكمبيوتر

1. فك ضغط الملف.
2. افتح Terminal داخل مجلد المشروع.
3. نفذ الأوامر:

```bash
npm install
npm run dev
```

ثم افتح الرابط الذي يظهر لك، غالبًا:

```bash
http://localhost:5173
```

## الرفع على Netlify

### الطريقة الأسهل

1. ادخل إلى Netlify.
2. اختر: Add new site.
3. اختر: Deploy manually.
4. اسحب مجلد المشروع أو اربطه مع GitHub.

### عند الربط مع GitHub

Netlify سيقرأ الملف `netlify.toml` تلقائيًا:

- Build command: `npm run build`
- Publish directory: `dist`

## ملاحظات مهمة

هذه نسخة واجهة Frontend فقط. الأزرار لا تتصل حاليًا بذكاء اصطناعي أو OCR. يمكن لاحقًا إضافة:

- OpenAI API لتحليل الرسائل وكتابة الردود.
- OCR لقراءة صور الرسائل.
- Firebase أو Supabase لتسجيل الدخول وحفظ الملفات.
- PWA لتحويله إلى تطبيق يشبه تطبيق الهاتف.

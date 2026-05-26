# Empire Bank Upgrade

لعبة إدارة الأموال والأعمال التجارية - Version 2.0.0

## المتطلبات
- Node.js 18+
- npm

## التثبيت

```bash
npm install
```

## التشغيل المحلي

```bash
npm start
```

ثم افتح المتصفح على `http://localhost:3000`

## النشر على Render

1. انسخ رابط المستودع
2. اذهب إلى [Render.com](https://render.com)
3. اختر "New" > "Web Service"
4. اختر Repository
5. استخدم البيانات التالية:
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`

## الميزات
- ✅ تسجيل الدخول والحسابات الشخصية
- ✅ إدارة الأموال والأرصدة
- ✅ نظام القروض
- ✅ استلام الرواتب
- ✅ اتصال فوري بين جميع اللاعبين

## الملفات
```
├── package.json       # إعدادات المشروع
├── server.js         # خادم Express و Socket.IO
├── README.md         # هذا الملف
└── public/
    ├── index.html    # واجهة اللعبة
    └── style.css     # أنماط التصميم
```

## التطوير
جميع الملفات جاهزة للنشر على Render بدون أخطاء! 🚀

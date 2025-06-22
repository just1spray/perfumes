# Kings Castle Perfume 👑

تطبيق Next.js متقدم لإدارة العطور والدورات التدريبية مع الذكاء الاصطناعي

## المميزات الرئيسية

- 🎯 إدارة شاملة للعطور المركبة والزيوت العطرية
- 📚 نظام دورات تدريبية تفاعلي
- 🤖 مساعد ذكي مدعوم بـ Google Genkit
- 🔥 قاعدة بيانات Firebase Firestore
- 📱 تصميم متجاوب لجميع الأجهزة
- 🎨 واجهة مستخدم حديثة مع Tailwind CSS
- 🔐 نظام مصادقة آمن

## التقنيات المستخدمة

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Radix UI
- **Backend**: Firebase (Firestore, Auth, Storage)
- **AI**: Google Genkit
- **State Management**: React Hooks

## متطلبات التشغيل

- Node.js 18+ 
- npm أو yarn
- حساب Firebase
- مفتاح Google AI API

## التثبيت والتشغيل

1. **استنساخ المشروع**
```bash
git clone <repository-url>
cd kings-castle-perfume
```

2. **تثبيت التبعيات**
```bash
npm install
```

3. **إعداد متغيرات البيئة**
```bash
cp .env.local.example .env.local
```
قم بتحديث القيم في `.env.local` بمعلومات Firebase وGoogle AI الخاصة بك

4. **تشغيل التطبيق**
```bash
npm run dev
```

5. **فتح التطبيق**
افتح [http://localhost:3000](http://localhost:3000) في المتصفح

## هيكل المشروع

```
src/
├── app/                    # صفحات التطبيق (App Router)
│   ├── (auth)/            # مجموعة صفحات المصادقة
│   ├── (dashboard)/       # مجموعة صفحات لوحة التحكم
│   ├── (public)/          # مجموعة الصفحات العامة
│   └── api/               # API Routes
├── components/            # مكونات واجهة المستخدم
│   ├── ui/               # مكونات أساسية
│   ├── forms/            # نماذج
│   ├── layout/           # مكونات التخطيط
│   └── features/         # مكونات الميزات
├── firebase/             # إعداد Firebase
├── genkit/              # إعداد Genkit AI
├── hooks/               # React Hooks مخصصة
├── lib/                 # مكتبات مساعدة
└── types/               # تعريفات TypeScript
```

## الميزات المتاحة

### إدارة العطور
- عرض كتالوج العطور المركبة
- إدارة الزيوت العطرية
- نظام تقييم وتعليقات
- بحث وفلترة متقدمة

### الدورات التدريبية
- دورات تعلم صناعة العطور
- محتوى تفاعلي ومرئي
- تتبع التقدم
- شهادات إتمام

### المساعد الذكي
- استشارات شخصية للعطور
- توصيات مخصصة
- دعم فني ذكي

## المساهمة

1. Fork المشروع
2. إنشاء فرع للميزة الجديدة (`git checkout -b feature/AmazingFeature`)
3. Commit التغييرات (`git commit -m 'Add some AmazingFeature'`)
4. Push للفرع (`git push origin feature/AmazingFeature`)
5. فتح Pull Request

## الترخيص

هذا المشروع مرخص تحت رخصة MIT - راجع ملف [LICENSE](LICENSE) للتفاصيل.

## الدعم

للحصول على الدعم، يرجى فتح issue في GitHub أو التواصل معنا عبر البريد الإلكتروني.

---

**تم تطويره بـ ❤️ لمجتمع صناعة العطور**
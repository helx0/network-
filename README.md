# 🌍 Network Visualization Platform

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

منصة تفاعلية متقدمة لتصور وتحليل الشبكات مع إمكانيات عرض بصرية متطورة وتفاعلات سلسة.

## ✨ الميزات الرئيسية

- 🌐 **تصور شبكات متقدم** مع رسوم توضيحية فعالة
- 🔍 **تحليل الاتصالات** وعرض الإحصائيات التفصيلية
- 📈 **مراقبة الأداء** في الوقت الفعلي
- 🎨 **واجهة مستخدم احترافية** وحديثة
- 📱 **تصميم متجاوب** (Responsive Design)
- ⚡ **أداء عالي** وتحميل فوري

## 🚀 عرض مباشر

[�� اضغط هنا لرؤية المشروع](https://network-mu-three.vercel.app)

## 🛠️ التكنولوجيا المستخدمة

- **HTML5** - الهيكل الأساسي
- **CSS3** - التصميم المتقدم والرسوم المتحركة
- **JavaScript (ES6+)** - المنطق والتفاعلات
- **Canvas API** - رسم الشبكات
- **Web API** - معالجة البيانات

## 💻 البدء السريع

### المتطلبات
- متصفح حديث (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+)
- اتصال إنترنت

### التثبيت المحلي

```bash
# استنساخ المستودع
git clone https://github.com/helx0/network-.git
cd network-

# تشغيل خادم محلي (اختياري)
python3 -m http.server 8000

# افتح المتصفح على http://localhost:8000
```

## 📖 الاستخدام

### الطريقة الأولى: التطبيق المباشر
1. افتح ملف `index (6).html` في متصفحك
2. شاهد الشبكة تتشكل وتتفاعل
3. تفاعل مع العناصر بالماوس

### الطريقة الثانية: الخادم المحلي
```bash
# استخدم أي خادم ويب محلي
http-server
# أو
live-server
```

## 🎯 الميزات الرئيسية

### 1. تصور الشبكات
- عرض العقد (Nodes) والاتصالات (Edges)
- حركة سلسة وطبيعية
- رسوم متحركة ديناميكية

### 2. التفاعل المستخدم
- تحريك العقد بالماوس
- تكبير وتصغير (Zoom)
- عرض المعلومات عند الماوس (Hover)

### 3. التحليل
- عرض إحصائيات الشبكة
- حساب الاتصالات
- تتبع الأداء

## 📊 البيانات

الشبكة تدعم تنسيقات البيانات التالية:

```json
{
  "nodes": [
    { "id": 1, "label": "Node 1", "color": "#FF6B6B" },
    { "id": 2, "label": "Node 2", "color": "#4ECDC4" }
  ],
  "edges": [
    { "source": 1, "target": 2, "weight": 5 }
  ]
}
```

## 🏗️ البنية

```
network-/
├── index (6).html      # الملف الرئيسي
├── assets/             # الموارد (الصور والخطوط)
├── css/                # ملفات التنسيق
├── js/                 # ملفات JavaScript
└── README.md          # هذا الملف
```

## 🔧 الإعدادات

يمكن تخصيص الشبكة من خلال:

```javascript
const config = {
  nodeSize: 20,
  linkStrength: 0.5,
  chargeStrength: -300,
  color: {
    node: '#3498db',
    link: '#95a5a6'
  }
};
```

## 🛠️ التطوير

### متطلبات التطوير
- Node.js 14+
- npm أو yarn

### خطوات التطوير

```bash
# تثبيت المتطلبات
npm install

# تطوير محلي مع Live Reload
npm run dev

# بناء الإصدار الإنتاجية
npm run build
```

## 🚀 الميزات المستقبلية

- [ ] دعم تنسيقات بيانات متعددة
- [ ] تصدير الرسوم البيانية (PNG, SVG)
- [ ] تحليل متقدم للشبكات
- [ ] دعم البيانات الضخمة (Big Data)
- [ ] تطبيق الهاتف المحمول

## 🤝 المساهمة

نرحب بمساهماتك! يرجى:

1. عمل Fork للمستودع
2. إنشاء فرع (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. فتح Pull Request

## 📝 الترخيص

MIT License - استخدم بحرية في مشاريعك

## 📧 التواصل

- 📨 البريد الإلكتروني: [your-email@example.com]
- 🐦 تويتر: [@your-twitter]
- 💼 LinkedIn: [your-linkedin-profile]

---

**تم تطويره بـ ❤️ من قبل فريق التطوير**

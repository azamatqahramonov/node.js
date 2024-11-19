## Texnologiyalar

- **HTML**: Veb sahifalar tuzish uchun asosiy til.
- **CSS**: Sahifa dizaynini yaratish uchun.
- **JavaScript**: Interaktiv elementlar va logikani yaratish uchun.
- **React**: Foydalanuvchi interfeysi yaratish uchun JavaScript kutubxonasi.
- **NPM**: Paket menejeri, kutubxonalar va modullarni boshqarish uchun.
- **Node.js**: JavaScriptni serverda ishlatish uchun platforma.
- **SPA (Single Page Application)**: Foydalanuvchi sahifalar o'rtasida qayta yuklanmasdan navigatsiya qiladi.
- **Tailwind CSS**: Dizaynni tez va oson yaratish uchun utility-first CSS framework.

## NPM (Node Package Manager)

NPM — bu Node.js bilan birga keladigan paket menejeri bo'lib, u JavaScript kutubxonalari va dasturiy ta'minotlarni boshqarishga yordam beradi.

### NPM'ni o'rnatish:

Node.js o'rnatilganda avtomatik ravishda o'rnatiladi.

### NPM buyruqlari:

- `npm init` — yangi Node.js loyihasini yaratadi.
- `npm install <package>` — kutubxona yoki paketni o'rnatadi.
- `npm uninstall <package>` — paketni o'chiradi.
- `npm start` — loyiha ishga tushadi (odatiy start skripti).
- `npm run <script>` — ma'lum bir skriptni ishga tushiradi.

**Package.json**: NPM orqali o'rnatilgan paketlar va ularning versiyalari haqida ma'lumot saqlanadi.

## Node.js

Node.js — bu JavaScriptni server tomonida ishlatish imkonini beradigan platforma.

### Asinxron JavaScript:

Node.js asinxron va event-driven (voqea asosida ishlash) modelga ega bo'lib, bu uni yuqori darajadagi samaradorlikka erishish uchun mos qiladi.

### Modul tizimi:

- `require()` — modullarni ulash uchun ishlatiladi.
- **Core modullar**: Node.js o'zida bir nechta modulni taklif etadi (masalan, `fs` fayl tizimi uchun, `http` server yaratish uchun).

## SPA (Single Page Application)

SPA — bu faqat bitta HTML sahifadan iborat bo'lib, foydalanuvchi tomonidan sahifalar o'zgartirilganda, butunlay yangi sahifa yuklanmasdan, faqat kerakli qismlar yangilanadi.

### Xususiyatlari:

- Foydalanuvchi bilan o'zaro aloqada bo'lganda sahifa qayta yuklanmaydi.
- REST API yoki GraphQL orqali server bilan muloqot qiladi.
- JavaScript frameworklari (masalan, React, Vue, Angular) bilan yaratiladi.

### Foydalari:

- Tezkor va interaktiv tajriba.
- Foydalanuvchi uchun qulay.

### Qiyinchiliklari:

- SEO (Search Engine Optimization) uchun muammolar, lekin serverda ishlovchi render (SSR) texnologiyalar yordamida bu muammoni hal qilish mumkin.

## React

React — bu Facebook tomonidan ishlab chiqilgan JavaScript kutubxonasi bo'lib, u interaktiv UI yaratish uchun ishlatiladi.

### Xususiyatlari:

- **Component-based architecture**: UI komponentlarga ajratilgan.
- **Virtual DOM**: React DOMni o'zgartirishda samaradorlikni oshirish uchun virtual DOM ishlatadi.
- **JSX**: JavaScript va HTML birlashtirilgan sintaksis.
- **Unidirectional data flow**: Ma'lumotlar faqat bitta yo'nalishda oqadi (ota komponentdan bola komponentga).

### React bilan ishlash:

- **Hooks**: React 16.8 versiyasidan boshlab, `useState`, `useEffect` kabi hook'lar orqali funksiya komponentlarida holat va yon ta'sirlarni boshqarish imkoniyati yaratildi.
- **State**: Komponentda o'zgaruvchi holatni saqlash uchun ishlatiladi.
- **Props**: Komponentlar o'rtasida ma'lumot uzatish uchun ishlatiladi.

### React uchun umumiy struktura:

- **src**: barcha JavaScript fayllari va komponentlar.
- **public**: umumiy resurslar (index.html va rasm fayllari).
- **App.js**: asosiy komponent, odatda bu yerda boshqa komponentlar joylashadi.
- **index.js**: React komponentlarini DOMga qo'yish uchun ishlatiladi (ReactDOM.render()).

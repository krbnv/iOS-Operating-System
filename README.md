# iOS-Operating-System
# iOS

iOS — bu mobil operatsion tizim bo‘lib, u Apple kompaniyasi tomonidan AQSH, Kaliforniyada tashkil topgan.

2007-yil 9-yanvar — Steve Jobs birinchi iPhone bilan taqdim qilgan.

2007-yil 29-iyun — birinchi iPhone sotuvga chiqqan.

2010-yildan boshlab nomi iOS deb o‘zgartirilgan.

Scott Forstall — iPhone’ning dasturiy tizimini va iOS tizimini yaratgan jamoa rahbari.

iOS — bu Apple yaratgan mobil operatsion tizim va u asosan iPhone qurilmalarida ishlaydi.

## iOS asosiy qatlamlari

iOS asosiy 4 ta qatlamga ega, tepadan pastga:

1. **Cocoa Touch** — eng yuqori qatlam. Foydalanuvchi ko‘radigan ilovalar, tugmalar, ekran, touch, notification kabi narsalar shu qatlamda ishlaydi.
2. **Media** — rasm, video, audio, animatsiya va grafika bilan ishlaydi.
3. **Core Services** — internet, fayllar, ma’lumotlar bazasi, joylashuv, tizim xizmatlari kabi asosiy imkoniyatlarni beradi.
4. **Core OS** — eng pastki qatlam va xotira, protsessor, xavfsizlik, driverlar va hardware bilan ishlaydi.

# Cocoa Touch

Cocoa Touch — bu ekrandagi tugmalar, oynalar, bosish, surish, notification va ilova interfeysini boshqaradigan qatlam.

Cocoa Touch — foydalanuvchi bilan ilova orasidagi interfeys va touch harakatlarini boshqaruvchi iOS qatlami.

## Misol

iPhone’da Telegramni ochdik:

* tugmani bosish;
* ekranni surish;
* klaviaturani ochish;
* boshqa sahifalarga o‘tish.

Shu kabi foydalanuvchi bilan bog‘liq amallarni Cocoa Touch bajaradi.

**Tugmani bosamiz → tizim harakatni tushunadi → amal bajariladi.**

## UIKit

Cocoa Touch ichida frameworklardan biri **UIKit** mavjud.

UIKit:

* button;
* text;
* rasm;
* menyu;
* oynalar;
* touch harakatlari

kabi narsalarni yaratadi.

**Kirishni bosish → Cocoa Touch / UIKit → ilova kodi → kerakli amal**

UIKit bizga tayyor kod va komponentlar beradi. Masalan, tugmani bosishni birinchi aniqlaydi va ilovadagi tegishli kodni ishga tushirishga yordam beradi.

# Media

Media — telefonning ko‘rish va eshitish bilan bog‘liq ishlarni bajaradigan qatlam.

Media — iOS’da rasm, video, audio, grafika va animatsiyalarni ishlatish uchun kerak.

## Misol

Telegramda video ochdik.

**Telegram → Media → video qayta ishlanadi → ekranda ko‘rinadi va ovoz keladi**

Media qatlami bajaradi:

* rasm ko‘rsatish;
* video ochish;
* musiqa va ovoz chiqarish;
* animatsiya yaratish;
* 2D/3D grafika chizish;
* kamera va videodan kelgan media ma’lumotlarini qayta ishlash.

## Texnologiyalar

**AVFoundation** — audio va video bilan ishlash.

**Core Animation** — ekrandagi obyektlarni harakatlantirish va animatsiya qilish.

**Core Graphics** — 2D grafika chizish uchun.

**Metal** — kuchli 2D/3D grafika va GPU bilan tez ishlash, o‘yinlar uchun.

# Core Services

Core Services — iOS’dagi asosiy tizim xizmatlarini beradigan qatlam.

Core Services — ilovaning kundalik ishlari uchun kerak bo‘ladigan tayyor xizmatlar.

## Misol

Telegramdan joylashuv ulashish:

**Telegram → Core Services → Location xizmati → natija ilovaga qaytadi**

Core Services yordam beradi:

* internetga ulanish;
* fayl saqlash;
* vaqt va sana bilan ishlash;
* joylashuvni bilish;
* ma’lumotlar bazasidan foydalanish;
* kontaktlar yoki boshqa tizim ma’lumotlari bilan ishlash.

# Core OS

Core OS — bu telefonning ichki ishlarini boshqaradi.

Core OS — iOS’ning pastki qatlami. Protsessor, xotira, xavfsizlik, tarmoq va hardware bilan bog‘liq asosiy ishlarni boshqaradi.

## Misol

Telegram kamerasidan foydalanmoqchi bo‘lsak, yuqori qatlamlardan kelgan so‘rov Core OS’ga keladi va u kerakli driver/hardware bilan ishlashga yordam beradi.

Core OS quyidagilar bilan ishlaydi:

* CPU;
* RAM;
* fayl tizimi;
* Wi-Fi;
* Bluetooth;
* batareya va energiya boshqaruvi;
* tarmoq.

## XNU Kernel

Core OS’ning asosiy yadrosi — **XNU Kernel**.

XNU Kernel — protsessorlar, RAM, driverlar, jarayonlar va hardware resurslarini boshqaradi.

Masalan, kameraga kirganda kerakli driver va qurilma resurslarini boshqarishga yordam beradi.

## Core OS ishlashidan misol

* Ilova: kamerani och.
* AVFoundation: kamera bilan ishlash xizmatini beradi.
* Core OS: driverlar orqali kameraga murojaat qiladi.
* Hardware kamera: ishga tushadi.
* Natija yuqoriga qaytib, ilovada kamera tasviri ko‘rinadi.

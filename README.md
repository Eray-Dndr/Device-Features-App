# Device Features App

Device Features App, React Native ve Expo kullanarak geliştirdiğim bir mobil uygulamadır. Uygulama, cihazın kamera ve konum özelliklerini kullanarak temel donanım erişimlerini göstermektedir. React Navigation ile ekranlar arasında geçiş yapılabilir.

## Özellikler

* Kamera erişimi
* Fotoğraf çekme
* Cihaz konumunu alma
* Konum izinlerini yönetme
* Sayfalar arası navigasyon
* Mobil cihaz donanımlarını kullanma

## Kullanılan Teknolojiler

* React Native
* Expo
* React Navigation
* Expo Camera
* Expo Location
* JavaScript

## Proje Yapısı

```text
device-features-app
│
├── screens/
│   ├── HomeScreen.js
│   ├── CameraScreen.js
│   └── LocationScreen.js
│
├── assets/
├── App.js
├── index.js
├── package.json
└── app.json
```

## Kurulum

Projeyi klonladıktan sonra aşağıdaki komutları çalıştırabilirsiniz.

```bash
npm install
npx expo start
```

Uygulamayı Expo Go veya Android Emulator üzerinden çalıştırabilirsiniz.

> **Not:** Kamera ve konum özelliklerini test edebilmek için fiziksel bir Android cihaz kullanılması önerilir.

## Kullandığım Yapılar

* React Functional Components
* React Navigation (Native Stack)
* Expo Camera
* Expo Location
* İzin (Permissions) yönetimi
* React Native Components
* Cihaz donanımlarına erişim

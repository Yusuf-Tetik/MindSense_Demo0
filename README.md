# 🧠✨ MindSense - Çocuklar İçin AI Destekli Eğitim Platformu

> **Öğrenmenin Geleceği** - Çocuklara özel tasarlanmış, yapay zeka destekli eğitim web uygulaması

## 📋 Proje Hakkında

MindSense, çocuklara yapay zeka destekli eğitim sunmayı hedefleyen modern bir web uygulamasıdır. Bu proje, çocuk dostu arayüz tasarımı ile eğlenceli ve güvenli bir öğrenme ortamı sağlamak amacıyla geliştirilmiştir.

### 🎯 Hedef Kitle
- **Öğrenciler**: 2. sınıf - 8. sınıf arası çocuklar
- **Öğretmenler**: Eğitim profesyonelleri

## ✨ Özellikler

### 🔐 Kimlik Doğrulama Sistemi
- **Login (Giriş) Sayfası**
  - E-mail ve şifre ile giriş
  - Form validasyonu ve hata mesajları
  - Demo hesap desteği
  - Şifre görünürlük kontrolü

- **Register (Kayıt) Sayfası**
  - Kişisel bilgiler (Ad, Soyad, E-mail, Şifre)
  - Doğum tarihi seçimi (takvim widget'ı)
  - Kullanıcı rolü seçimi (Öğrenci/Öğretmen)
  - Koşullu sınıf seçimi (sadece öğrenciler için)
  - Kapsamlı form validasyonu

### 🎨 Çocuk Dostu Tasarım
- Renkli ve eğlenceli arayüz
- Animasyonlu logo ve dekoratif elementler
- Büyük, kolay kullanılabilir butonlar
- İkonlar ve emojiler ile zenginleştirilmiş içerik
- Gradient renkler ve yumuşak gölgeler

### 📱 Responsive Tasarım
- Mobil cihazlarda optimize edilmiş görünüm
- Tablet ve masaüstü uyumluluğu
- Dokunmatik ekran dostu etkileşimler

### ♿ Erişilebilirlik
- High contrast mode desteği
- Reduced motion desteği
- Klavye navigasyonu
- Screen reader uyumluluğu
- ARIA etiketleri

## 🛠️ Teknoloji Stack

- **Frontend Framework**: React 18.2.0
- **Build Tool**: Vite 4.4.5
- **Routing**: React Router DOM 6.15.0
- **Form Management**: React Hook Form 7.45.4
- **Icons**: React Icons 4.10.1
- **Styling**: CSS3 (Custom CSS Variables)
- **Typography**: Google Fonts (Nunito)

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler
- Node.js (v16 veya üzeri)
- npm veya yarn

### Adımlar

1. **Projeyi klonlayın**
   ```bash
   git clone <repository-url>
   cd mind-sense
   ```

2. **Bağımlılıkları yükleyin**
   ```bash
   npm install
   ```

3. **Geliştirme sunucusunu başlatın**
   ```bash
   npm run dev
   ```

4. **Uygulamayı açın**
   - Tarayıcınızda `http://localhost:3000` adresine gidin

### Demo Giriş Bilgileri
```
E-mail: demo@mindsense.com
Şifre: demo123
```

## 📁 Proje Yapısı

```
Mind_Sense/
├── public/                 # Statik dosyalar
├── src/
│   ├── components/         # React bileşenleri
│   │   ├── Login/         # Login sayfası
│   │   ├── Register/      # Register sayfası
│   │   └── shared/        # Paylaşılan bileşenler
│   │       ├── Button/    # Buton bileşeni
│   │       ├── Input/     # Input bileşeni
│   │       ├── Select/    # Dropdown bileşeni
│   │       └── Logo/      # Logo bileşeni
│   ├── App.jsx           # Ana uygulama bileşeni
│   ├── App.css          # Ana uygulama stilleri
│   ├── index.css        # Global stiller
│   └── main.jsx         # Uygulama giriş noktası
├── package.json         # Proje bağımlılıkları
├── vite.config.js      # Vite konfigürasyonu
└── README.md           # Proje dokümantasyonu
```

## 🎨 Tasarım Sistemi

### Renk Paleti
- **Primary Blue**: #4A90E2
- **Primary Green**: #7ED321  
- **Primary Orange**: #F5A623
- **Primary Purple**: #9013FE
- **Primary Pink**: #F06292

### Tipografi
- **Font Family**: Nunito (Google Fonts)
- **Font Weights**: 300, 400, 600, 700, 800

### Animasyonlar
- Sayfa geçiş animasyonları
- Hover efektleri
- Loading durumları
- Form validasyon geribildirimleri

## 🔧 Geliştirme Komutları

```bash
# Geliştirme sunucusu
npm run dev

# Production build
npm run build

# Build önizleme
npm run preview

# Kod kalitesi kontrolü
npm run lint
```

## 📝 Form Validasyonu

### Login Formu
- E-mail format kontrolü
- Şifre minimum uzunluk kontrolü
- Gerçek zamanlı validasyon

### Register Formu
- İsim/soyisim: sadece harf karakterleri
- E-mail: format doğrulama
- Şifre: en az 8 karakter, büyük harf, küçük harf, rakam
- Doğum tarihi: yaş sınırları (6-100)
- Rol seçimi: zorunlu alan
- Sınıf seçimi: öğrenci rolü için zorunlu

## 🚧 Gelecek Özellikler

- Dashboard sayfası
- Ders modülleri
- AI destekli öğrenme araçları
- İlerleme takibi
- Gamification elementleri
- Çoklu dil desteği

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 👥 Ekip

- **UI/UX Designer**: Çocuk dostu arayüz tasarımı
- **Frontend Developer**: React geliştirme
- **Backend Developer**: API entegrasyonu (yakında)

## 📞 İletişim

Sorularınız için lütfen issue oluşturun veya bizimle iletişime geçin.

---

**MindSense** ile çocukların öğrenme yolculuğunu daha eğlenceli ve etkili hale getiriyoruz! 🌟 
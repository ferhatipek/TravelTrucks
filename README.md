# 🚐 TravelTrucks - Karavan Kiralama Servisi

Geniş araç yelpazesi ve kullanışlı filtreleme sistemi ile kamp araçlarını arayıp kiralayabileceğiniz modern bir web uygulaması.

---

## 🚀 Özellikler

- **Ana Sayfa** 
- **Karavan Kataloğu** – Konum, araç tipi ve ekipmana göre filtreleme
- **Detay Sayfası** – Etkileşimli fotoğraf galerisi (ışık kutusu), yorumlar ve rezervasyon formu
- **Gelişmiş Filtreleme Sistemi** – Çoklu kriter seçimi ile arama
- **Favoriler Listesi** – localStorage kullanımı ile kalıcı favoriler
- **"Daha Fazla Yükle" Özelliği** – Kademeli olarak karavan kartlarının yüklenmesi
- **Mobil Uyumlu Tasarım** – Masaüstü, tablet ve mobil cihazlara duyarlı
- **Toast Bildirimleri** – Başarılı rezervasyon sonrası bilgilendirme

---

## 🛠 Teknolojiler

- **React** – Modern UI bileşenleri ve hook kullanımı
- **Redux Toolkit** – Modern durum yönetim çözümü
- **React Router v6** – Nested routes destekli yönlendirme
- **Axios** – API istekleri için HTTP istemcisi
- **CSS Modules** – Bileşen bazlı stil yönetimi
- **React Toastify** – Bildirim sistemi
- **Vite** – Hızlı geliştirme ortamı
- **PropTypes** – Bileşen doğrulama

---

## 📦 Kurulum ve Başlatma

### Adım Adım Kurulum

1. **Projeyi klonlayın:**

   ```bash
   git clone https://github.com/ferhatipek/TravelTrucks.git
   cd traveltrucks
   npm install
   npm run dev

## 🎯 Uygulama Özellikleri
**Durum Yönetimi (Redux Toolkit)
Projede 3 ana slice kullanılır:**

**campers** – Karavan listesi, seçilen karavan, yüklenme durumu

**filters** – Aktif arama filtreleri (konum, araç tipi, ekipman)

**favorites** – Favorilere eklenen karavan ID’leri (localStorage ile saklanır)

## API Entegrasyonu
Tüm API istekleri src/services/api.js içinde yönetilir

Axios kullanılır

Hata yönetimi ve yüklenme durumları uygulanır

Filtreleme ve sayfalama desteklenir

## Bileşen Mimarisi
Her bileşen kendi klasöründe: .jsx ve .module.css dosyalarıyla

Fonksiyonel bileşenler ve React hook’ları kullanılır

PropTypes ile parametre kontrolü sağlanır

DRY prensibine uygun kod yapısı

## Yönlendirme
React Router v6 ile route yönetimi

Nested route ve lazy load destekli yapı

404 sayfası için yönlendirme

SPA desteği için vercel.json yapılandırması

## 🌐 API Bilgileri
**Base URL**:
https://66b1f8e71ca8ad33d4f5f63e.mockapi.io

**GET /campers** – Tüm karavanları getirir

**GET /campers/:id** – Seçilen karavanın detaylarını getirir

**Filtreleme (Frontend’de uygulanır)**

**Konum:** Büyük/küçük harf duyarsız

**Araç Tipi**: panelTruck, fullyIntegrated, alcove

**Ekipman**: Klima, otomatik vites, mutfak, TV, banyo vb.

## Deployment
**Vercel Link:** https://travel-trucks-iyag-git-main-ferhats-projects-d86a054e.vercel.app/
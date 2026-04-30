# Moka Coffee & Croissant — Sadakat Sistemi

## Deploy (Vercel)

1. [vercel.com](https://vercel.com) → **Add New Project**
2. **"Import Git Repository"** yerine **"Deploy from CLI or drag & drop"** seç
3. Bu `moka-loyalty` klasörünü sürükle bırak
4. Deploy tamamlanınca sana bir URL verir: `moka-loyalty-xxx.vercel.app`
5. Bu URL artık QR kodunda yerleşik — müşteriler tarayınca direkt Müşteri ekranı açılır

## Supabase Bağlantısı
- Proje URL ve key `index.html` içinde gömülü
- Tablolar: `loyalty` (müşteriler), `meta` (toplam ödül sayısı)

## Kullanım
- **Kafe Paneli**: QR'ı yazdır, istatistikleri gör
- **Müşteri**: QR tara → numara gir → puan kazan
- 6 kahvede 7. bedava

## Klasör Yapısı
```
moka-loyalty/
├── public/
│   ├── index.html        ← Tüm uygulama
│   └── logos/
│       ├── logo-dark.png ← Beyaz logo (koyu arka plan için)
│       └── logo-light.png
└── vercel.json           ← Vercel config
```

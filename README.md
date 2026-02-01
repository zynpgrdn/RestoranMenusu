# 🍽️ Restoran Menü Yönetimi

Restoranların kendi menülerini kolaylıkla oluşturup düzenleyebildiği ve müşterilerine **QR Kod** aracılığıyla dijital olarak sunabildiği bir web uygulamasıdır.

---

## 📋 Özellikler

- **Menü Oluşturma & Düzenleme** — Yemek kategorileri ve ürünleri kolayca ekleyip düzenleyebilirsiniz.

- **Kullanıcı Dostu Arayüz** — Streamlit tabanlı sade ve etkileşimli bir tasarım ile hızlı işlem yapılabilir.

---

## 🚀 Kurulum & Çalıştırma

### Gereksinimler

- Python 3.11+
- `pip` paket yöneticisi

### Adımlar

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/aribilgiogr/restoran-menu-yonetimi.git
   cd restoran-menu-yonetimi
   ```

2. **Gerekli paketleri yükleyin:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Uygulamayı başlatın:**
   ```bash
   streamlit run app.py
   ```

Uygulama başlatıldığında tarayıcınızda otomatik olarak açılacaktır.

---

## 📂 Proje Yapısı

```
restoran-menu-yonetimi/
├── app.py                  # Ana uygulama dosyası
├── requirements.txt        # Gerekli Python paketleri
├── src/
│   ├── database/           # Veritabanı bağlantısı ve sorgu işlemleri
│   └── views/              # Streamlit sayfa ve arayüz komponentleri
└── README.md               # Bu dosya
```

---

## 💡 Kullanım

1. Uygulamayı açtıktan sonra menü kategorileri ve ürünleri ekleyin.

2. Müşteriler kodu tarayarak menüye erişebilir.
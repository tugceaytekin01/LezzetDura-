# LezzetDurağı-
# LezzetDuragi

---

# 🍽️ Lezzet Durağı

**Lezzet Durağı**, sade bir HTML, CSS ve JavaScript yapısı kullanılarak hazırlanmış bir restoran tanıtım web sitesidir.
Ziyaretçiler menüyü inceleyebilir, yorum bırakabilir ve iletişim formu aracılığıyla restoranla iletişime geçebilir.

---

## 📁 Proje Yapısı

```
Lezzet-Duragi/
│
├── index.html           # Ana sayfa
├── menu.html            # Menü sayfası
├── bizeulasin.html      # İletişim sayfası (Bize Ulaşın)
├── yorum.html           # Yorumlar sayfası
├── style.css            # Tüm sayfalarda ortak kullanılan stil dosyası
└── Resimler/            # Görsellerin bulunduğu klasör
    ├── ızgara.jpg
    ├── pizza.jpg
    ├── kebap.jpg
    ├── kola.jpg
    ├── trileçe.jpg
    └── ... (diğer resimler)
```

---

## 🌐 Sayfa Açıklamaları

### 🏠 `index.html`

* Ziyaretçiyi karşılayan **ana sayfa**dır.
* Restoranın kısa tanıtımı yapılır.
* Menüye geçiş için bir **“Menü” butonu** bulunur.
* Navbar’dan **Adresimiz**, **Bize Ulaşın** ve **Yorumlar** sayfalarına ulaşılabilir.

---

### 🍔 `menu.html`

* Restoranın **yemek**, **içecek** ve **tatlı** çeşitlerini görüntüler.
* Grid (ızgara) düzeniyle tasarlanmış kart yapısı sayesinde her ürün görsel olarak sergilenir.
* Adres bilgisi için küçük bir **JavaScript uyarı kutusu (alert)** içerir.

---

### 📩 `bizeulasin.html`

* Kullanıcıların restoranla iletişime geçebileceği bir **form** içerir.
* Backend bağlantısı olmadan, **mailto:** yöntemiyle e-posta gönderimi yapar.
* Ad, e-posta ve mesaj alanları bulunur.
* Gönderim sonrası varsayılan e-posta istemcisi açılır.

---

### 💬 `yorum.html`

* Ziyaretçilerin görüşlerini paylaşabileceği bir sayfadır.
* **LocalStorage** kullanılarak yorumlar tarayıcıda saklanır, sayfa yenilense bile kaybolmaz.
* Kullanıcılar anonim olarak veya isim girerek yorum ekleyebilir.
* Gönderilen yorumlar ekranda listelenir.

---

## 🎨 Stil (CSS)

* **style.css** dosyası tüm sayfalarda ortak olarak kullanılır.
* Renk paleti krem ve kahverengi tonlarında tutulmuştur (zarif ve doğal görünüm).
* Flexbox ve CSS Grid ile **responsive (mobil uyumlu)** bir yapı oluşturulmuştur.
* Hover geçişlerinde yumuşak **animasyonlar** kullanılmıştır.
* Sayfalar arası tutarlı tipografi: `'Poppins', sans-serif`

---

## ⚙️ Kullanılan Teknolojiler

| Teknoloji                | Açıklama                                          |
| ------------------------ | ------------------------------------------------- |
| **HTML5**                | Sayfa yapısı ve içerik düzeni                     |
| **CSS3**                 | Görsel tasarım ve responsive yapı                 |
| **JavaScript (Vanilla)** | Etkileşimli öğeler (adres bildirimi, yorum kaydı) |
| **LocalStorage**         | Tarayıcıda kalıcı yorum saklama sistemi           |

---

## 🚀 Çalıştırma

Projeyi yerel ortamda görüntülemek için:

1. Bu projeyi bilgisayarına indir:

   ```bash
   git clone https://github.com/kullaniciadi/lezzet-duragi.git
   ```
2. Klasöre gir:

   ```bash
   cd lezzet-duragi
   ```
3. `index.html` dosyasını bir tarayıcıda aç:

   ```bash
   start index.html
   ```

   veya

   ```bash
   open index.html
   ```

---



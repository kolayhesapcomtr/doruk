# Çivril Doruk Tarım - Kurumsal Web Sitesi

Modern ve responsive kurumsal web sitesi. HTML, CSS ve JavaScript ile geliştirilmiştir.

## Proje Hakkında

Çivril Doruk Tarım için tasarlanmış kurumsal tanıtım web sitesi. Ayçekirdeği ve kabak çekirdeği üretimi ve işleme hizmetlerini tanıtmak amacıyla oluşturulmuştur.

## Özellikler

- ✅ Modern ve profesyonel tasarım
- ✅ Tamamen responsive (mobil uyumlu)
- ✅ Hızlı yükleme süresi
- ✅ SEO uyumlu yapı
- ✅ Kolay güncellenebilir içerik
- ✅ İletişim formu
- ✅ Google Maps entegrasyonu
- ✅ Sosyal medya bağlantıları
- ✅ Animasyonlar ve geçişler

## Sayfalar

1. **Ana Sayfa** (index.html) - Genel tanıtım ve öne çıkan özellikler
2. **Kurumsal** (kurumsal.html) - Hakkımızda, vizyon, misyon ve değerler
3. **Ürünler** (urunler.html) - Siyah ayçekirdeği, beyaz ayçekirdeği, kabak çekirdeği
4. **Hizmetler** (hizmetler.html) - Eleme, sınıflandırma, renk ayırma, paketleme, depolama
5. **İletişim** (iletisim.html) - İletişim formu, adres, harita

## Proje Yapısı

```
doruk-tarim-website/
├── index.html              # Ana sayfa
├── kurumsal.html          # Kurumsal sayfa
├── urunler.html           # Ürünler sayfa
├── hizmetler.html         # Hizmetler sayfa
├── iletisim.html          # İletişim sayfa
├── css/
│   └── style.css          # Ana stil dosyası
├── js/
│   └── main.js            # JavaScript fonksiyonları
├── images/                # Görsel dosyaları (opsiyonel)
└── README.md              # Bu dosya
```

## Kurulum ve Kullanım

### 1. Dosyaları İndirin

Projeyi bilgisayarınıza indirin veya klonlayın.

### 2. Tarayıcıda Açın

`index.html` dosyasını herhangi bir modern tarayıcıda açın:
- Chrome
- Firefox
- Safari
- Edge

### 3. Yerel Sunucu (Opsiyonel)

Daha iyi bir geliştirme deneyimi için yerel sunucu kullanabilirsiniz:

**Python ile:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Node.js ile:**
```bash
npx http-server
```

**VS Code Live Server ile:**
- VS Code'da Live Server eklentisini yükleyin
- index.html'e sağ tıklayın
- "Open with Live Server" seçeneğini seçin

## Özelleştirme

### Renkleri Değiştirme

`css/style.css` dosyasındaki `:root` bölümünde renk değişkenlerini düzenleyin:

```css
:root {
    --primary-green: #2d5016;
    --secondary-green: #4a7c28;
    --light-green: #8bc34a;
    --accent-gold: #d4af37;
    /* ... */
}
```

### İletişim Bilgilerini Güncelleme

Tüm HTML dosyalarında şu bilgileri kendi bilgilerinizle değiştirin:
- Telefon numaraları
- E-posta adresleri
- Adres bilgileri
- Sosyal medya linkleri

### Logo Ekleme

Header kısmındaki emoji logosunu gerçek logo görselinizle değiştirin:

```html
<!-- Mevcut -->
<div class="logo-icon">🌻</div>

<!-- Değiştirilmiş -->
<img src="images/logo.png" alt="Doruk Tarım Logo" style="width: 60px;">
```

### Harita Konumunu Güncelleme

`iletisim.html` dosyasındaki Google Maps iframe'ini kendi konumunuzla değiştirin:
1. Google Maps'te konumunuzu bulun
2. "Paylaş" > "Haritayı göm" seçeneğini seçin
3. Iframe kodunu kopyalayın ve mevcut iframe ile değiştirin

### Görseller Ekleme

`images/` klasörüne görseller ekleyip HTML dosyalarında kullanabilirsiniz:

```html
<img src="images/urun-gorseli.jpg" alt="Ürün Açıklaması">
```

## İletişim Formu Entegrasyonu

Mevcut form statik bir gösterimdir. Gerçek form işlevselliği için:

### FormSubmit kullanarak:
```html
<form action="https://formsubmit.co/your@email.com" method="POST">
    <!-- Form alanları -->
</form>
```

### Formspree kullanarak:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- Form alanları -->
</form>
```

### PHP Backend (kendi sunucunuzda):
`js/main.js` dosyasındaki `handleSubmit` fonksiyonunu PHP ile entegre edin.

## Hosting ve Yayınlama

Siteyi yayınlamak için ücretsiz veya ücretli hosting hizmetleri kullanabilirsiniz:

### Ücretsiz Seçenekler:
- **GitHub Pages**: Kod repository'sini GitHub'a yükleyip GitHub Pages ile yayınlayın
- **Netlify**: Drag & drop ile kolay yayınlama
- **Vercel**: Git entegrasyonu ile otomatik deploy
- **Firebase Hosting**: Google'ın ücretsiz hosting hizmeti

### Ücretli Hosting:
- Türk hosting firmaları (Natro, Turhost, vb.)
- Uluslararası firmalar (Hostinger, SiteGround, vb.)

## Tarayıcı Uyumluluğu

- ✅ Chrome (Son 2 versiyon)
- ✅ Firefox (Son 2 versiyon)
- ✅ Safari (Son 2 versiyon)
- ✅ Edge (Son 2 versiyon)
- ✅ Mobil tarayıcılar

## Performans İpuçları

1. **Görselleri optimize edin**: JPEG/PNG dosyalarını sıkıştırın
2. **CDN kullanın**: Font Awesome gibi kütüphaneler için CDN kullanın
3. **Önbellekleme**: Hosting ayarlarında önbellekleme (caching) aktif edin
4. **Minify**: CSS ve JS dosyalarını minify edin (production için)

## Güncelleme ve Bakım

### İçerik Güncellemeleri
- HTML dosyalarını text editör ile düzenleyebilirsiniz
- Ürün, hizmet veya firma bilgilerini güncel tutun

### Teknik Güncellemeler
- Font Awesome ve diğer CDN bağlantılarını düzenli kontrol edin
- Tarayıcı uyumluluğunu test edin

## Lisans

Bu proje Çivril Doruk Tarım için özel olarak geliştirilmiştir.

## Destek

Teknik destek veya özelleştirme talepleriniz için:
- E-posta: info@doruktarim.com
- Telefon: +90 (258) 712 34 56

---

**Son Güncelleme:** 2025
**Geliştirici:** Claude
**Versiyon:** 1.0

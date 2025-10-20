

---

````markdown
# 🧠 XSS Scanner & Exploitation Tool


---

## 🇹🇷 Proje Hakkında

Bu Python script’i, web uygulamalarındaki **Cross-Site Scripting (XSS)** zafiyetlerini tespit etmek ve doğrulamak için geliştirilmiştir.  
Geniş XSS payload listeleriyle hedef URL’deki giriş noktalarına enjeksiyon denemeleri yaparak potansiyel açıkları bulur.  
Ayrıca **WAF bypass teknikleri**, **otomatik payload testleri** ve **renkli terminal çıktısı** desteği içerir.

---

## 🎯 Amaç ve Hedef Kitle

**Amaç:**  
Farklı XSS türlerini (Reflected, Stored, DOM-Based) otomatik olarak tespit etmek.

**Hedef Kitle:**
- 🧑‍💻 Güvenlik Araştırmacıları: Farklı XSS payload’larını test etmek için  
- 🧠 Pentesterlar: WAF’leri aşmak ve koruma testleri yapmak için  
- 👨‍💻 Geliştiriciler: Uygulama güvenliğini test etmek için

---

## ⚙️ Özellikler

✅ Kapsamlı XSS payload listeleri  
✅ WAF atlatma testleri  
✅ HTTP başlık bilgisi toplama  
✅ Basit sömürü denemeleri (ör. cookie steal test)  
✅ Renkli terminal çıktısı (Colorama)  
✅ Modüler tasarım (get_domain_info, scan_xss, exploit_xss, waf_bypass)  
✅ CAPTCHA çözme yer tutucusu (ileride entegrasyon için)

---

## 🧩 Gereklilikler

Aşağıdaki Python modüllerini kurmalısınız:

```bash
pip install requests colorama beautifulsoup4
````

---

## 🚀 Kurulum ve Kullanım

### 🔧 1. Script’i klonla veya indir:

```bash
git clone https://github.com/0batexe1/xss-scanner.git
cd xss-scanner
```

### ▶️ 2. Çalıştır:

```bash
python xss_scanner.py
```

Script çalıştığında hedef URL’yi girmeniz istenir:

```
Enter the target URL: https://example.com/search
```

---

## 📊 Çıktı ve Değerlendirme

* ✅ `XSS found with payload: [payload]` → Payload yanıt içinde yansıtıldı
* 🍪 `Cookie stealing successful!` → Basit exploit başarılı
* ⚠️ Hatalı pozitif olabilir, her bulguyu manuel doğrulayın

---

## ⚠️ Etik ve Yasal Uyarı

> ❗ Bu araç **sadece izin alınmış sistemlerde** kullanılmalıdır.
> İzinsiz tarama veya exploit girişimleri yasa dışıdır.
> Geliştirici bu aracın kötüye kullanımından sorumlu değildir.

---

## 🧠 Geliştirme Önerileri

* 🔍 **DOM XSS tespiti** (Selenium / Playwright ile)
* 💡 **Parametre keşfi** (form alanları, JSON gövdeleri)
* 🧾 **HTML/JSON raporlama**
* 🌐 **Proxy desteği (Burp, ZAP)**
* 🧩 **Zafiyet türü sınıflandırması**
* 🤖 **CAPTCHA çözüm entegrasyonu (2Captcha, OCR)**
* 🕒 **Rate limiting / delay sistemi**

---

## 🤝 Katkıda Bulunma

Yeni payload’lar eklemek, hataları düzeltmek veya yeni özellikler önermek istersen:

1. Bu repoyu forkla
2. Değişikliklerini yap
3. Pull request gönder 🎉

---

## 📜 Lisans

Bu proje **MIT Lisansı** altındadır.
Detaylar için `LICENSE` dosyasına bakabilirsiniz.

---

## 📬 İletişim

GitHub: [@0batexe1](https://github.com/0batexe1)

---



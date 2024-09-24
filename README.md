# 0bat.exe1 - XSS Vulnerability Scanner and Exploitation Tool

## Introduction
`0bat.exe1` is an advanced Cross-Site Scripting (XSS) vulnerability scanner and exploitation tool designed to help security researchers identify and exploit XSS vulnerabilities on a target website. This tool is written in Python and is intended for educational and ethical purposes only.

### Features
- **Domain Information Gathering:** Collects HTTP headers and other useful information from the target domain.
- **Comprehensive XSS Payload Testing:** Includes a large variety of XSS payloads, including basic, polymorphic, encoded, and obfuscated variants.
- **WAF Bypass Techniques:** Implements payloads designed to bypass Web Application Firewalls (WAFs).
- **Exploitation Capabilities:** Can exploit discovered XSS vulnerabilities by stealing cookies and manipulating the DOM.
- **Customizable Payloads:** Easily extendable to include additional payloads and techniques.

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/0bat.exe1.git
   cd 0bat.exe1

    Install the Required Python Libraries Ensure you have Python 3 installed. You can install the required libraries using:

    bash

    pip install -r requirements.txt

Requirements

    Python 3.x
    Required Libraries: The tool requires several Python libraries including requests, BeautifulSoup, and colorama. These can be installed via pip:

    bash

    pip install requests beautifulsoup4 colorama

Usage

    Run the Tool Execute the Python script to start the tool:

    bash

    python3 xss.py

    Enter the Target URL When prompted, enter the URL of the target domain you wish to scan for XSS vulnerabilities.

    Scan and Exploit The tool will automatically gather domain information, scan for XSS vulnerabilities using the provided payloads, attempt to bypass any WAFs, and exploit any discovered vulnerabilities.

Example Output

plaintext

    ______________
    | 0bat.exe1 |
    ---------------

Enter the target URL: http://example.com
Gathering information about the domain...
Headers:
 {'Date': 'Tue, 24 Sep 2024 07:02:31 GMT', 'Content-Type': 'text/html; charset=UTF-8', ...}

Scanning http://example.com for XSS vulnerabilities...
Testing with payload: <script>alert('XSS')</script>
...
XSS found with payload: %3Cscript%3Ealert('XSS')%3C%2Fscript%3E
Exploiting the XSS vulnerability...
Cookie stealing successful!
Attempting WAF bypass techniques...
Bypass successful with payload: %3Cscript%3Ealert(1)%3C%2Fscript%3E

Disclaimer

This tool is intended for educational and ethical testing purposes only. Unauthorized use of this tool against websites without permission is illegal and unethical. Always obtain proper authorization before testing any system.
Contributing

Contributions to enhance the tool, such as adding new payloads or improving the WAF bypass techniques, are welcome. Feel free to fork the repository and submit pull requests.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

This tool was inspired by various open-source security tools and resources, including OWASP, PayloadAllTheThings, and others. Special thanks to the security community for their contributions.




### Additional Notes:
- Replace `yourusername` in the clone URL with your actual GitHub username if you plan to host it on GitHub.
- Ensure you include a `LICENSE` file in your repository if you choose to use the MIT License or another open-source license.
- The `requirements.txt` file should include the necessary Python libraries (`requests`, `BeautifulSoup4`, `colorama`). If you don't have this file, you can create it by listing these dependencies.

Şunu dedin:
aynısını türkçe olarak da oluştur
ChatGPT:
ChatGPT
README.md (Türkçe)



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 0bat.exe1 - XSS Zafiyeti Tarayıcı ve Sömürü Aracı

## Giriş
`0bat.exe1`, bir hedef web sitesinde Cross-Site Scripting (XSS) zafiyetlerini tespit etmek ve sömürmek için geliştirilmiş ileri düzey bir tarayıcı ve sömürü aracıdır. Bu araç, Python ile yazılmış olup yalnızca eğitimsel ve etik amaçlarla kullanılmak üzere tasarlanmıştır.

### Özellikler
- **Alan Bilgisi Toplama:** Hedef domain'den HTTP başlıkları ve diğer yararlı bilgileri toplar.
- **Kapsamlı XSS Payload Testi:** Temel, polimorfik, kodlanmış ve obfuscated (gizlenmiş) varyantlar dahil olmak üzere geniş bir XSS payload yelpazesi içerir.
- **WAF Atlatma Teknikleri:** Web Uygulama Güvenlik Duvarlarını (WAF) atlatmak için tasarlanmış payload'ları uygular.
- **Sömürü Yeteneği:** Tespit edilen XSS zafiyetlerini çerez çalma ve DOM manipülasyonu gibi yöntemlerle sömürebilir.
- **Özelleştirilebilir Payload'lar:** Ek payload'lar ve teknikler eklemek kolaydır.

### Kurulum

1. **Depoyu Klonlayın**
   ```bash
   git clone https://github.com/kullaniciadi/0bat.exe1.git
   cd 0bat.exe1

    Gerekli Python Kütüphanelerini Yükleyin Python 3 kurulu olduğundan emin olun. Gerekli kütüphaneleri şu komutla yükleyebilirsiniz:

    bash

    pip install -r requirements.txt

Gereksinimler

    Python 3.x
    Gerekli Kütüphaneler: Araç, requests, BeautifulSoup, ve colorama gibi birkaç Python kütüphanesine ihtiyaç duyar. Bu kütüphaneleri pip ile yükleyebilirsiniz:

    bash

    pip install requests beautifulsoup4 colorama

Kullanım

    Aracı Çalıştırın Python script'ini çalıştırarak aracı başlatın:

    bash

    python3 xss.py

    Hedef URL'yi Girin İstendiğinde, XSS zafiyetlerini taramak istediğiniz hedef domain URL'sini girin.

    Tarama ve Sömürü Araç, otomatik olarak domain bilgisini toplar, sağlanan payload'lar ile XSS zafiyetlerini tarar, WAF atlatma tekniklerini dener ve bulunan zafiyetleri sömürür.

Örnek Çıktı

plaintext

    ______________
    | 0bat.exe1 |
    ---------------

Enter the target URL: http://ornek.com
Alan hakkında bilgi toplanıyor...
Başlıklar:
 {'Date': 'Tue, 24 Sep 2024 07:02:31 GMT', 'Content-Type': 'text/html; charset=UTF-8', ...}

http://ornek.com üzerinde XSS zafiyetleri taranıyor...
Payload ile test ediliyor: <script>alert('XSS')</script>
...
Payload ile XSS bulundu: %3Cscript%3Ealert('XSS')%3C%2Fscript%3E
XSS zafiyeti sömürülüyor...
Çerez çalma başarılı!
WAF atlatma teknikleri deneniyor...
Bypass başarılı: %3Cscript%3Ealert(1)%3C%2Fscript%3E

Uyarı

Bu araç yalnızca eğitim ve etik test amaçlarıyla kullanılmalıdır. İzin alınmadan bu aracı web sitelerine karşı kullanmak yasadışı ve etik dışıdır. Her zaman bir sistemi test etmeden önce gerekli izinleri aldığınızdan emin olun.
Katkıda Bulunma

Aracın geliştirilmesi için, yeni payload'lar ekleme veya WAF atlatma tekniklerini geliştirme gibi katkılar memnuniyetle karşılanır. Depoyu fork'layarak ve pull request göndererek katkıda bulunabilirsiniz.
Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Detaylar için LICENSE dosyasına bakabilirsiniz.
Teşekkürler

Bu araç, OWASP, PayloadAllTheThings gibi çeşitli açık kaynak güvenlik araçları ve kaynaklardan ilham almıştır. Güvenlik topluluğuna katkılarından dolayı teşekkür ederiz.




### Ek Notlar:
- Klonlama URL'sindeki `kullaniciadi` kısmını kendi GitHub kullanıcı adınızla değiştirmeyi unutmayın.
- Eğer `LICENSE` dosyasını kullanmayı planlıyorsanız, MIT Lisansı veya başka bir açık kaynak lisansı kullanacağınızdan emin olun.
- `requirements.txt` dosyasında gerekli Python kütüphanelerini listeleyebilirsiniz (`requests`, `BeautifulSoup4`, `colorama` gibi). Eğer bu dosya mevcut değilse, bu bağımlılıkları listeleyerek bir tane oluşturabilirsiniz.

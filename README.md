# Book Data Mining Project

Bu proje, Veri Biliminin Temelleri dersi kapsamında, dünya genelinde en çok satan kitapların verilerini gerçek bir kaynaktan (Wikipedia) çekerek analiz edilebilir bir veri setine dönüştürmek amacıyla hazırlanmıştır.

## Proje Hakkında
Proje, yapılandırılmamış web verilerini (HTML) Python kullanarak anlamlı ve yapılandırılmış bir Excel tablosuna dönüştürür. Veri kazıma (Web Scraping) tekniği kullanılarak oluşturulan bu veri seti, farklı veri tiplerini ve istatistiksel hipotezleri test etmek için uygun nitelikleri içermektedir.

## Kullanılan Teknolojiler
* Programlama Dili: Python 3.12
* Kütüphaneler:
    * BeautifulSoup4 & Requests: Web kazıma işlemleri için.
    * Pandas: Veri manipülasyonu ve tablo oluşturma için.
    * Openpyxl: Excel dosyası üretimi için.

## Veri Seti İçeriği
Veri seti 100 adet örnek (satır) ve 10 farklı nitelikten oluşmaktadır:

| Nitelik | Veri Tipi | Tanım |
| :--- | :--- | :--- |
| Kitap_ID | Sayısal (Ayrık) | Benzersiz kayıt numarası |
| Kitap_Adi | Kategorik (Nominal) | Kitabın başlığı |
| Yazar | Kategorik (Nominal) | Kitabın yazarı |
| Dil | Kategorik (Nominal) | Orijinal dili |
| Tahmini_Satis_Milyon | Sayısal (Sürekli) | Satış rakamları |
| Sayfa_Sayisi | Sayısal (Ayrık) | Sayfa sayısı (Rastgele üretilmiştir) |
| Okuyucu_Puani | Sayısal (Sürekli) | 1-5 arası kullanıcı puanı |
| Indirim_Var_Mi | İkili (Binary) | İndirim durumu (0/1) |
| Kapak_Tipi | Kategorik (Nominal) | Karton Kapak / Ciltli |
| Populerlik | Kategorik (Ordinal) | Düşük < Orta < Yüksek |

## Dosya Yapısı
* odev_hazirla.py: Verileri kazıyan ve veri setini oluşturan ana script.
* 231220046_aysenurCakmak.xlsx: Çıktı olarak üretilen veri seti.
* rapor.pdf: Detaylı proje raporu ve hipotezler.

## Kurulum ve Kullanım
Projeyi yerel bilgisayarınızda çalıştırmak için:
1. Depoyu klonlayın: git clone https://github.com/aysenurcakmak/Book-Data-Mining-Project.git
2. Gerekli kütüphaneleri kurun: pip install requests beautifulsoup4 pandas openpyxl
3. Scripti çalıştırın: python odev_hazirla.py

---
Hazırlayan: Ayşenur Çakmak - 231220046

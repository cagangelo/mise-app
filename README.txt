MISE — Mobil beslenme ve akıllı buzdolabı prototipi

Başlatma: index.html dosyasını Chrome, Safari veya başka bir tarayıcıda aç.
Telefon üzerinde ana ekrana ekleyerek uygulama benzeri kullanabilirsin.

İçerik:
- 6 adımlık kişiselleştirme
- Kalori ve öğün kaydı
- Tarif kütüphanesi, porsiyon miktarları, eksik malzeme belirleme
- Buzdolabı stok ve tüketim tarihi takibi
- Alışveriş listesi ve alışveriş sonrası stok kaydı
- 7 günlük plan ve plan bazında eksikleri bulma
- Yerel tarayıcı depolaması

Sınırlar:
- Gerçek iOS uygulaması / App Store build değildir, çalışan mobil web prototipidir.
- Veriler sadece tarayıcı localStorage'da kalır. Tarayıcı verilerini silersen kaybolur.
- Push bildirimleri, arka planda kontrol, AI API ve bulut senkronizasyonu henüz yoktur.
- Son tüketim tarihlerini kullanıcı girmelidir; otomatik tahmin güvenilir değildir.
- Kitapta ölçüsü belirsiz kalemler yaklaşıklaştırılmıştır ve makro bilgileri değişikliklere göre yeniden hesaplanmaz.
- Örnek dolap onboarding sonunda eklenir; gerçek stokları girerek değiştir.

MISE 1.4 — Bütçe ve Fiyat Hafızası (ek)
- Market sekmesinde haftalık bütçeyi kaydedin.
- "Manuel fiyat kaydet" alanına örneğin 1,2 kg tavuk / 360 TL girin.
- "Fiş yükle" ile fotoğraftan metin tanımayı deneyebilirsiniz. OCR işlemi için ilk kullanımda internet ve harici Tesseract.js kütüphanesi gerekir. Türkçe fişlerde hata olabilir; satırları kaydetmeden denetleyin.
- Fiş satırlarının beklenen biçimi: TAVUK 1,2 KG 360,00 (ürün, miktar, birim, fiyat). Diğer biçimler algılanmayabilir.
- Fiyat hafızası, son üç kaydın birim fiyat ortalamasını kullanır.
- Haftalık menü oluşturucu fiyatı bilinen ürünlerin tarif maliyetine göre yaklaşık seçim yapar. Bütçe ve kalori hedefini kesin olarak tutturma garantisi vermez; özellikle fiyatı bilinmeyen malzemeler maliyete dahil değildir.
- Alışveriş listesindeki gösterilen tutarlar malzeme miktarının yaklaşık maliyetidir; market paket boyutu karşılaştırması bu sürümde yoktur.
- Görsellerdeki ve ekrandaki stok miktarlarını kontrol edin. Fişten dolaba eklenen ürünlerde tarih varsayılandır, gerçek ambalaj tarihini elle düzeltin.
- Mevcut veriler aynı site adresi ve tarayıcıda localStorage ile saklanır. Güncelleme öncesi profil menüsünden JSON yedeğinizi indirin.
- Bu paket yüklenen 'mise-mobil-prototip(2).zip' üzerine geliştirilmiştir; daha önceki farklı sürümlerdeki özelliklerin tümünü içerdiği iddia edilmez.

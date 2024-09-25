# Turkish Privacy Guide (Türkçe Mahremiyet Rehberi)

Bu rehber, mahremiyetin ayaklar altında olduğu 2024 Türkiyesinde mahremiyetinizi ve veri güvenliğinizi korumak için pratik bilgiler ve öneriler sunar.

## İçindekiler

1. [İşletim Sistemleri](#1-işletim-sistemleri)
2. [Web Tarayıcıları](#2-web-tarayıcıları)
3. [VPN Hizmetleri](#3-vpn-hizmetleri)
4. [DNS Hizmetleri](#4-dns-hizmetleri)
5. [E-Posta Hizmetleri](#5-e-posta-hizmetleri)
6. [Şifre Yöneticileri](#6-şifre-yöneticileri)
7. [İki Faktörlü Doğrulama (2FA)](#7-iki-faktörlü-doğrulama-2fa)
8. [Sosyal Medya ve Mesajlaşma](#8-sosyal-medya-ve-mesajlaşma)
9. [Veri Silme Yöntemleri](#9-veri-silme-yöntemleri)
10. [Yapay Zeka Sistemleri](#10-yapay-zeka-sistemleri)
11. [Faydalı Kaynaklar](#11-faydalı-kaynaklar)
12. [Ek Notlar](#12-ek-notlar)



---

## 1. İşletim Sistemleri

 Kullandığınız işletim sistemi, dijital mahremiyetinizin temelini oluşturur. Kapalı kaynak kodlu işletim sistemleri, verilerinizin nasıl toplandığı ve kullanıldığı konusunda şeffaf değildir. Açık kaynak kodlu sistemler ise daha fazla kontrol ve güvenlik sunar.

### Mobil

- [iOS](https://www.apple.com/tr/ios/ios-18/): Güvenli **görünüyor**, ancak kısıtlayıcı. Apple ID gerektirmesi ve veri toplama politikaları dezavantaj. Apple'ın ekosistemine hapsolursunuz. Diyelim ki ülkenizde VPN'ler yasaklandı, ne yapacaksınız iPhone'lar ile :) 
- [Android](https://www.android.com/): Daha özgür ama güvenlik riskleri mevcut. [LineageOS](https://lineageos.org/), [GrapheneOS](https://grapheneos.org/) gibi özel işletim sistemleri (Custom ROM'lar) daha fazla mahremiyet sunar.

**Neden Standart Android Kullanılmamalı?**

- Google hizmetleri entegre, yoğun veri toplama
- Üretici ve operatör bloatware'leri
- Geç gelen veya hiç gelmeyen güncellemeler

**Neden IOS Kullanılmamalı?**

- **Yine kapalı kaynak kodlu.**
- **Veri toplama konusunda şeffaf değil.**
- **Kullanıcı kontrolü sınırlı.**
- **Tamir hakkı yok (Apple cihazlarını tamir ettirmek zor ve pahalı).**

**Android'i deGoogle ederseniz iyi olabilir, [Örnek Rehber: De-Google Your Life - Part 2_LTT YouTube!](https://odysee.com/@Timbo303Reuploads:d/De-Google-Part-2:8)**

### Masaüstü

- [Linux](https://www.linux.org/): En güvenli ve mahremiyete saygılı seçenek. Dağıtım seçimi önemli (örn. [Linux Mint](https://linuxmint.com/), [Fedora](https://fedoraproject.org/), [Debian](https://www.debian.org/), [Arch](https://archlinux.org/) ).
- **Windows**: Veri toplama politikaları **çok** sorunlu. Ayarlar dikkatle yapılandırılmalı **ancak yine de yeterli değil.**
- **macOS**: Windows'tan iyi ama Linux'tan zayıf. FileVault kullanımı önerilir.

**Neden Windows Kullanılmamalı?**

- Telemetri ve veri toplama yaygın
- Kullanıcı kontrolü sınırlı
- Kapalı kaynak kod

**Neden MacOS Kullanılmamalı?**

- **Yine kapalı kaynak kodlu.**
- **Veri toplama konusunda şeffaf değil.**
- **Apple ekosistemine entegrasyon, daha fazla veri toplanmasına yol açabilir.**

## 2. Web Tarayıcıları

 Web tarayıcınız, internette gezinirken bıraktığınız izleri kontrol etmenizi sağlar. Gizlilik odaklı tarayıcılar, izlemeyi engeller, parmak izinizi gizler ve verilerinizi korur.

- **Mozilla Firefox Forkları ([Librewolf](https://librewolf.net/)  [Floorp](https://floorp.app/en)):** Açık kaynak, mahremiyet odaklı. Default Firefox artık önermiyoruz çünkü her güncellemesiyle mahremiyete zarar veriyor.
- **[Brave](https://brave.com/):** Yerleşik reklam engelleyici ve kripto cüzdan entegrasyonu, Chromium Tabanlı **Ancak Brave'in kendi reklam sistemi ve bazı veri toplama uygulamaları tartışmalıdır.**
- [Tor Browser](https://www.torproject.org/download/): Maksimum anonimlik için. **Ancak Tor, normal internet kullanımından daha yavaştır ve bazı sitelerle uyumlu olmayabilir.**

**Neden Chrome, Edge veya Opera Kullanılmamalı?**

- Google (Chrome) Microsoft (Edge)  ve Opera yoğun veri toplar
- Opera, Çinli birileri tarafından satın alındı, gizlilik politikaları şüpheli **SPYWARE ALERT**
- Bu tarayıcılar, kullanıcı davranışlarını izler ve profilleme yapar
- Chromium tekel olmamalı

**Öneriler:**

- [Ublock Origin](https://github.com/gorhill/uBlock) veya [AdGuard](https://adguard.com/) gibi reklam engelleyiciler kullanın.
- Tarayıcı parmak izini minimize edin.
- HTTPS-Only modu etkinleştirin.
- **Gizlilik odaklı eklentiler kullanın (Örneğin [Privacy Badger](https://privacybadger.org/))**

## 3. VPN Hizmetleri

 VPN (Virtual Private Network), internet trafiğinizi şifreleyerek ve farklı bir sunucu üzerinden yönlendirerek çevrimiçi aktivitelerinizi gizlemenizi sağlar. Bu, İSS'nizin ve diğerlerinin sizi izlemesini zorlaştırır.

- [Proton VPN](https://protonvpn.com/): Ücretsiz plan mevcut, güvenilir. 
- [Mullvad](https://mullvad.net/): Anonim kayıt, Bitcoin ve nakit ödeme kabul eder.
- [IVPN](https://www.ivpn.net/): Gizlilik politikası fena değil, bağımsız denetimden geçmiş.
- **SelfHosting**: Sanal sunucunuzu nereden alacağınıza göre değişken güvenliğe sahip, en azından arka planda hangi kodun nasıl çalıştığını bilirsiniz.

**Neden Ücretsiz VPN'ler Kullanılmamalı?**

- Çoğu ücretsiz VPN verilerinizi satar veya reklamcılarla paylaşır
- Güvenlik standartları genellikle düşüktür
- Bant genişliği ve hız sınırlamaları

**Kullanılmaması Gereken VPN'ler**

- VPN Super
- Panda VPN
- Private VPN
- **Diye uzar gider liste, adı sanı belli olmayan, arkasındaki şirketin 100 tane ücretsiz VPN servisine sahip olduğu tipteki VPN'lerden uzak durun. Ücretsiz güvenebileceğiniz alternatifler zaten sınırlı.**
- oPeRaVpN **verilerinizi Çine satmaya hazır mısınız, bu hizmet aslında bir vpn bile değil sadece bir proxy**

**Önemli Not:** Herhangi bir VPN sağlayıcısına %100 güvenmeyin.

## 4. DNS Hizmetleri

 DNS (Domain Name System), internet site isimlerini IP adreslerine çeviren bir sistemdir. ISP'niz varsayılan olarak DNS hizmetini sağlar, ancak bu, internet trafiğinizin izlenmesi anlamına gelir. Alternatif DNS sağlayıcıları daha fazla gizlilik ve güvenlik sunar.

- [Quad9](https://www.quad9.net/): Güvenlik odaklı, ücretsiz. 
- [NextDNS](https://nextdns.io/): Özelleştirilebilir filtreler, analitik özellikleri, ücretli(ücretsizde kota var) 
- [Mullvad DNS](https://mullvad.net/tr/help/dns-over-https-and-dns-over-tls): VPN hizmetlerinden bağımsız kullanılabilir, ücretsiz, reklam tracker hatta malware engelleyen filtrelere sahip domainleri var.

**Neden ISP DNS'i Kullanılmamalı?**

- ISP'ler genellikle DNS sorgularınızı kaydeder ve analiz eder (*ehem ehem acaba hangileri*)
- Bazı ISP'ler DNS manipülasyonu yaparak belirli sitelere erişimi engeller
- ISP DNS'leri genellikle daha yavaştır ve DNSSEC desteği sunmaz

**Öneri**: DoH (DNS over HTTPS) veya DoT (DNS over TLS) kullanın.

## 5. E-Posta Hizmetleri

 E-posta, doğası gereği güvenli bir iletişim yöntemi değildir, ancak uçtan uca şifreleme sunan sağlayıcılar kullanarak gizliliğinizi artırabilirsiniz.

- [Proton Mail](https://protonmail.com/): Uçtan uca şifreleme, İsviçre merkezli. 
- [Tutanota](https://tutanota.com/): Almanya merkezli, açık kaynak. 

**Neden Gmail veya Outlook Kullanılmamalı?**

- Google ve Microsoft e-postalarınızın içeriğini tarar ve analiz eder
- Reklam ve profilleme için veri kullanımı
- Epostalarınıza bu şirketlerin tam erişimi

**Not**: E-posta, doğası gereği tam olarak güvenli değildir. Hassas iletişim için alternatif yöntemler düşünün (Signal, Session).

## 6. Şifre Yöneticileri

 Şifre yöneticileri, karmaşık ve benzersiz şifreler oluşturarak ve bunları sizin için saklayarak çevrimiçi hesaplarınızı korumanızı kolaylaştırır.

- [Bitwarden](https://bitwarden.com/): Açık kaynak, ücretsiz plan mevcut. 
- [KeePassXC](https://keepassxc.org/): Tamamen çevrimdışı, maksimum güvenlik. 
- [Proton Pass](https://proton.me/pass): Açık kaynak, ücretsiz plan mevcut. Yeni, güzel ancak Türkiye Proton şirketini sevmediği için arada engelleniyor. 

**Neden Tarayıcı Tabanlı Şifre Yöneticileri Kullanılmamalı?**

- Tarayıcıya bağımlılık
- Senkronizasyon güvenliği sorunları
- Sınırlı özellikler ve güvenlik seçenekleri

**Öneri**: Güçlü, benzersiz şifreler kullanın ve düzenli olarak değiştirin. Şifre oluşturucu kullanın.

## 7. İki Faktörlü Doğrulama (2FA)

 İki faktörlü doğrulama (2FA), hesaplarınıza ek bir güvenlik katmanı ekler. Şifrenizin çalınması durumunda bile, hesabınıza erişmek için ikinci bir faktöre (örneğin, telefonunuza gönderilen bir kod) ihtiyaç duyulur.

- [Aegis Authenticator](https://getaegis.app/): Android için açık kaynak. 
- [Ente Auth](https://ente.io/auth/): Platformlar arası, açık kaynak. 
- [Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro): Açık kaynak, Güzel görünümlü :p 

**Neden SMS Tabanlı 2FA Kullanılmamalı?**

- SMS'ler kolayca ele geçirilebilir (SIM swapping saldırıları)
- Gerçek zamanlı koruma sağlamaz

**Uyarı**: SMS tabanlı 2FA'dan kaçının, güvenli değil.

**Öneri**: Donanım anahtarlarını (hardware keys) kullanın, mümkünse. (Örnek Pubikey, yeterli bilgim olmadığı için detay veremeyeceğim)

## 8. Sosyal Medya ve Mesajlaşma

 Sosyal medya platformları ve mesajlaşma uygulamaları, kullanıcı verilerini yoğun şekilde toplar ve paylaşır. Gizlilik odaklı alternatifler, verilerinizi korumanıza ve iletişiminizi güvence altına almanıza yardımcı olur.

- [Signal](https://signal.org/): Uçtan uca şifreli mesajlaşma ve arama. 
- [Session](https://getsession.org/): Merkeziyetsiz, anonim iletişim. 
- [Element](https://element.io/) veya  [Matrix](https://matrix.org/): Açık kaynak, merkeziyetsiz iletişim protokolü. 

**Alternatif Sosyal Medya Platformları:**

- [Mastodon](https://joinmastodon.org/): Twitter alternatifi, merkeziyetsiz sosyal ağ. 
- [Lemmy](https://lemmy.ml/): Reddit alternatifi, merkeziyetsiz forum platformu. 
- [Pixelfed](https://pixelfed.org/): Instagram alternatifi, merkeziyetsiz fotoğraf paylaşım platformu. 

**Neden WhatsApp, Facebook Messenger, Instagram, Telegram Kullanılmamalı?**

- Meta (Facebook) kullanıcı verilerini yoğun şekilde toplar ve analiz eder
- Uçtan uca şifreleme varsayılan olarak açık değil (Telegram)
- Telegram Durov'un tutuklanmasından sonra uçtan uca şifrelemeyi bile bypass edecek seviyeye getirdi sistemini.
- Metadata toplanması ve paylaşılması

**Neden SMS ve Çağrılara Güvenmemelisiniz?**

- Güvenli değil ve çok kolay şekilde izleniyor, depolanıyor (muhtemelen aktif şekilde izleniyor).

> [Kaynak: NSA files decoded: Edward Snowden's surveillance revelations | theguardian.com](https://www.theguardian.com/world/interactive/2013/nov/01/snowden-nsa-files-surveillance-revelations-decoded#section/1)

**Öneri**: Mümkün olduğunca merkeziyetsiz, açık kaynak ve uçtan uca şifreleme sunan platformları tercih edin.

## 9. Veri Silme Yöntemleri

 Bilgisayarınızdan veya telefonunuzdan bir dosyayı "sildiğinizde", veri aslında tamamen yok olmaz. Özel yazılımlar kullanılarak kurtarılabilir. Hassas verileri kalıcı olarak silmek için özel yöntemler kullanmanız gerekir.

- **shred** (Unix/Linux): Komut satırı aracı.
- **Eraser** (Windows): Grafiksel arayüzlü güvenli silme yazılımı.

**Neden Standart "Sil" Fonksiyonu Yeterli Değil?**

- Standart silme işlemi dosyayı gerçekten silmez, sadece referansını kaldırır
- Silinen veriler özel yazılımlarla kurtarılabilir
- Hassas verilerin tamamen yok edilmesi için güvenli silme gereklidir

**Not**: SSD'ler için farklı yöntemler gerekebilir. Fiziksel imha en garanti yöntemdir. (**Diskinizi ikiye ayırıp yakabilirsiniz**)

## 10. Yapay Zeka Sistemleri

 Yapay zeka sistemleri, özellikle dil modelleri, büyük miktarda veriye ihtiyaç duyar. Bu veriler genellikle kullanıcı etkileşimlerinden toplanır. Gizlilik odaklı AI çözümleri, verilerinizin kontrolünü elinizde tutmanızı sağlar.

Lokal Model olarak Llama 3.1 önerilebilir, gpt4o mini ile yarışan görüş kapasiteli Llama 3.2'ye de göz atabilirsiniz

- [Ollama](https://ollama.com/) + [OpenWebUI](https://github.com/open-webui/open-webui): Yerel çalışan, mahremiyete saygılı AI çözümü. 

**Neden ChatGPT veya Google Gemini Kullanılmamalı?**

- Bu hizmetler, sohbet geçmişinizi ve verilerinizi saklar ve analiz eder
- AI modellerini eğitmek için kullanıcı verilerini kullanabilirler
- Gizlilik politikaları genellikle kullanıcı aleyhine değişebilir

**Uyarı**: ChatGPT gibi ücretsiz AI hizmetleri verilerinizi kullanır ve saklar.

## 11. Faydalı Kaynaklar

- [Privacy Guides](https://www.privacyguides.org/)
- [F-Droid - Daha iyi bir Android uygulama mağazası, genellikle açık kaynak uygulamaları barındırıyor](https://f-droid.org/)
- [FMHY - Önerdiğim bir site, her şey var](https://fmhy.pages.dev/)
- [Awesome-Privacy-xyz - Mahremiyet Araçları](https://awesome-privacy.xyz/)
- [Digital Defence](https://digital-defense.io/)

## 12. Ek Notlar

- İSS'lere güvenmeyin.
- Google, Amazon, Microsoft, Meta tarzı büyük şirketlerin ürünlerini kullandığınızda mümkün olduğunca çok verinizi işlediklerini bilin.
- Her zaman tetikte olun ve dijital haklarınızı savunun.
- Proton bazı kötü yanlara sahip olsa bile Google'ın mahremiyete saygı duyan hali olmaya çalışıyor.
- Yasalara uyun :).

Güvenli, özgür ve mahremiyete saygılı bir dijital dünya dileğiyle!

---

Bi yıldız bırakırsanız sevinirim, Mahremiyet toplumlar bilinçleştikçe gerçekleşecek bir olgudur :).

Bu rehber güncellenecektir. Katkıda bulunmak için lütfen bir issue açın veya pull request gönderin. Katkılara açığım.

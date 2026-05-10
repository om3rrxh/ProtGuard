# 🛡️ ProtGuard v1.1 - Gelişmiş Özel Bilgisayar Kilitleme Sistemi
ProtGuard, standart Windows kilit ekranına alternatif olarak geliştirilmiş, kullanıcı tanımlı kimlik doğrulama katmanı sunan bir güvenlik yazılımıdır. Özellikle belirli terminallerde veya yetkilendirilmiş bilgisayarlarda erişim kontrolünü kişiselleştirmek amacıyla tasarlanmıştır.

# 🚀 Temel Özellikler
Dinamik Kimlik Tanımlama: Uygulama ilk kez çalıştırıldığında kullanıcıdan bir kullanıcı adı ve şifre belirlemesini ister.

Tam Ekran Güvenlik Modu: Kilitleme komutu verildiğinde veya sistem otomatik kilitlendiğinde, Windows arayüzünü tamamen kapatarak yetkisiz erişimi engeller.

Güvenli Şifreleme: Belirlenen kimlik bilgileri hashlib kütüphanesi kullanılarak karma (hash) yöntemleriyle işlenir, böylece veriler düz metin olarak saklanmaz.

Sistem Entegrasyonu: winreg ve ctypes kullanarak Windows'un düşük seviyeli sistem bileşenleriyle etkileşime girer ve kilit ekranının bypass edilmesini zorlaştırır.

🛠️ Nasıl Çalışır?
Yapılandırma: Program başlatıldığında kullanıcıdan ana kimlik bilgilerini (Username & Password) girmesi istenir.

Kilit Aktivasyonu: "Kilitle" butonuna basıldığında veya belirlenen senaryo gerçekleştiğinde uygulama tüm ekranı kaplar.

Doğrulama: Bilgisayara tekrar erişim sağlamak için, başlangıçta belirlenen kullanıcı adı ve şifrenin hatasız girilmesi zorunludur.

Yetki Kontrolü: Yazılım, sadece yetkilendirilmiş ve kullanım izni alınmış cihazlarda çalışacak şekilde optimize edilmiştir.

# ⚠️ Önemli Güvenlik Notu ve Kullanım Koşulları
ProtGuard, kurumsal güvenlik politikaları veya kişisel kullanım izinleri çerçevesinde geliştirilmiştir. Bu yazılımın kullanımıyla ilgili şu hususlar dikkate alınmalıdır:

Sadece Yetkili Cihazlar: Bu uygulama sadece sahibinin izin verdiği veya kurum tarafından yetkilendirilen bilgisayarlarda çalıştırılmalıdır.

Erişim Sorumluluğu: Kullanıcı tarafından belirlenen şifrenin unutulması durumunda sistem erişimi kısıtlanabilir. Bu nedenle şifre yönetimi tamamen kullanıcının sorumluluğundadır.

Yasal Uyarı: Yazılımın izinsiz sistemlerde veya kötü niyetli amaçlarla kullanılması kesinlikle önerilmez.

### powered by om3rrxh

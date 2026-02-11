# ⚡ Şimşek Security V2
**Firewall ve Antivirüs Öncesi Güvenlik Katmanı**

Şimşek Security V2, Windows tabanlı sunucular için geliştirilmiş, açık kaynaklı bir **HIPS (Host Intrusion Prevention System)** aracıdır. Kritik servisleri (RDP, SMB, MSSQL, vb.) hedef alan brute-force saldırılarını milisaniyeler içinde tespit eder ve saldırganları otomatik olarak karantinaya alır.

## 🚀 Temel Özellikler
- **Canlı Log İzleme:** EventID bazlı (4625 vb.) anlık trafik analizi.
- **Aktif Koruma Modülleri:** RDP, SMB, MSSQL, IIS, VPN, FTP ve OpenSSH için özel denetim.
- **Otomatik Engelleme:** Tehdit tespit edildiği anda kaynak IP'yi kalıcı veya geçici olarak yasaklar.
- **SMTP Bildirimleri:** Saldırı anında belirlediğiniz e-posta adresine detaylı uyarı gönderir.
- **Coğrafi Kontrol:** Ülke bazlı erişim kısıtlama ve Blacklist/Whitelist yönetimi.
- **Raporlama:** Tüm güvenlik olaylarını PDF formatında dışa aktarma.

## 🛠️ Kurulum
1. [Releases](https://github.com/erkam-kaya/simsekv2/releases) sayfasından en güncel `.zip` dosyasını indirin.
2. Dosyaları sunucunuzda bir klasöre çıkartın.
3. `SimsekV2.exe` uygulamasını yönetici olarak çalıştırın.
4. "SMTP Ayarları" ve "Koruma Modülleri" sekmelerinden yapılandırmanızı tamamlayın.

## 👨‍💻 Geliştirici
**Erkam KAYA**
[Web Sitesi](https://erkamkaya.com) | [LinkedIn](https://linkedin.com/in/erkamkaya)

---
*Bu proje siber güvenlik farkındalığı ve sunucu güvenliği amacıyla geliştirilmiştir.*

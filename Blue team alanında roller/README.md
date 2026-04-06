# 💿 Blue Team alanında ki rollere şimdi daha detaylı bir giriş yapacağız. 

Blue Team dünyası, sadece "savunma" demek değildir; bu ekip, dijital bir kalenin hem mimarı, hem nöbetçisi hem de dedektifidir.


# SOC ANALİSTİ

🌟  1. SOC Analisti (Güvenlik Operasyon Merkezi Analisti)
SOC Analistleri, bir kurumun dijital sinir sistemini izleyen ilk gözlerdir. Genellikle kademeli (Tier) bir yapıda çalışırlar:

🌟 Tier 1 (L1 - Triyaj): Ön cephedir. SIEM (Güvenlik Bilgisi ve Olay Yönetimi) ekranlarına düşen binlerce alarmı filtrelerler.
Hangisi "yanlış alarm" (False Positive), hangisi "gerçek tehdit" (True Positive) ayrımını yaparlar.

🌟 Tier 2 (L2 - İnceleme): L1'den gelen gerçek tehditleri devralırlar. Saldırganın hangi sistemlere ulaştığını, hangi kullanıcı hesabını ele geçirdiğini analiz ederler.

🌟 Tier 3 (L3 - Uzmanlık): En karmaşık vakalarla ilgilenirler. Henüz çözülememiş, derinlemesine teknik analiz gerektiren kritik olaylara odaklanırlar.


# 🔵 INCIDENT RESPONDER - OLAY MÜDAHALE UZMANI

🔵 2. Incident Responder (Olay Müdahale Uzmanı)
Siber dünyanın "itfaiyecileri"dir. SOC analisti bir yangın (saldırı) ihbarı verdiğinde, Incident Responder sahaya iner.

🔵 Karantina ve Müdahale: Saldırganın yayılmasını engellemek için etkilenen sunucuların ağ bağlantısını keser veya zararlı yazılımın çalıştığı işlemleri durdurur.

🔵Kurtarma Planı: Saldırı durdurulduktan sonra sistemlerin güvenli bir şekilde nasıl ayağa kaldırılacağına karar verir. Yedeklerin temiz olduğundan emin olur.

🔵 Kriz Yönetimi: Sadece teknik değil, aynı zamanda yönetimsel bir roldür. Saldırının boyutunu yönetime raporlar ve iş sürekliliğini sağlar.


# 👩‍⚖️ ADLİ BİLİŞİM UZMANI - DFIR 

3. Adli Bilişim Uzmanı (Digital Forensics & Incident Response - DFIR)
Bu rol, siber saldırının "otopsisini" yapan kişidir. Olay bittikten sonra devreye girer ve "post-mortem" (ölüm sonrası) analiz yapar.

👩‍⚖️ Delil Toplama: Disk imajlarını alır, RAM (bellek) dökümlerini inceler. Bu işlem sırasında delillerin bozulmaması (Chain of Custody) hayati önem taşır.

👩‍⚖️ Tersine Mühendislik: Saldırganın kullandığı özel bir zararlı yazılım varsa, bu yazılımı güvenli bir ortamda çalıştırıp kodlarını analiz eder.

👩‍⚖️ Zaman Çizelgesi Oluşturma: Saldırganın sisteme girdiği ilk andan, tespit edildiği ana kadar yaptığı tüm hareketlerin kronolojik bir dökümünü çıkarır.

# ❗️ TEHDİT İSTİHBARATI ANALİSTİ

4. Tehdit İstihbaratı Analisti (Threat Intelligence Analyst)
Bu rolün görevi, "Düşmanını tanı" felsefesine dayanır. Kurumun dışındaki dünyayı izlerler.

 ❗️ OSINT ve Dark Web: Hacker forumlarını, sızıntı sitelerini ve istihbarat beslemelerini takip ederek kurumun verilerinin satılıp satılmadığını veya kuruma yönelik bir hazırlık olup olmadığını kontrol ederler.

 ❗️ TTP Analizi: Saldırganların kullandığı Taktik, Teknik ve Prosedürleri (TTP) belirlerler. Örneğin; "X grubu şu an Türkiye'deki bankalara şu yöntemle saldırıyor" bilgisini savunma ekibine iletirler.

 ❗️Stratejik Savunma: Elde edilen verilerle güvenlik duvarlarında veya SIEM sistemlerinde "önleyici" kurallar yazılmasını sağlarlar.

# ✅  GÜVENLİK MİMARI VE MÜHENDİSİ

5. Güvenlik Mimarı ve Mühendisi (Security Architect/Engineer)
Savunma sistemlerinin kurucularıdır. Onlar sağlam bir yapı inşa etmezse, diğer rollerin işi imkansız hale gelir.

 ✅  Sistem Tasarımı: Ağın nasıl bölümleneceğine (Segmentation), hangi trafiğin geçeceğine ve hangi güvenlik cihazlarının (Firewall, IPS, EDR, DLP) nereye konumlandırılacağına karar verirler.

 ✅  Otomasyon: Güvenlik süreçlerini otomatize eden scriptler ve araçlar yazarlar. Manuel yapılması saatler sürecek bir analizi saniyelere indirirler.

 ✅  Politika Geliştirme: "Parolalar nasıl olmalı?", "Kimler hangi veriye erişebilir?" gibi temel güvenlik kurallarını teknik altyapıya entegre ederler.

# 🏹  TEHDİT AVCISI

6. Tehdit Avcısı (Threat Hunter)
Blue Team içindeki en proaktif roldür. En gelişmiş saldırganların (APT grupları gibi) sistemde hiç iz bırakmadan, alarm üretmeden aylarca saklanabileceğini varsayarak hareket ederler.

🏹 Hipotez Kurma: "Eğer bir saldırgan Active Directory sunucumuza sızsaydı, hangi alışılmadık logları bırakırdı?" diye sorar ve bunu manuel olarak arar.

🏹 Anomali Tespiti: Standart alarmların yakalayamadığı, normal kullanıcı davranışından sapan çok küçük sapmaları takip ederler.

🏹 Gizli Tehditlerin Temizlenmesi: Henüz "olay" statüsüne geçmemiş, sessizce veri sızdıran yapıları bulup ortaya çıkarırlar.


# Özetle söylemek gerekirse:
SOC Analisti ile izler, Incident Responder ile müdahale eder, Adli Bilişimci ile kanıt toplar, İstihbarat Analisti ile öngörür,
Mimar ile korur ve Tehdit Avcısı ile arar. Bu birimlerin koordineli çalışması, modern bir kurumun siber dayanıklılığının temelidir.

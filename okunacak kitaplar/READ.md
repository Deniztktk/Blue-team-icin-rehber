# Kaynaklar 📖 

**Kitaplar**

📍 Blue Team Handbook: Incident Response Edition (Don Murdoch)

Bu kitap bir romandan ziyade, bir "savaş alanı el kitabı"dır. Bir saldırı anında (örneğin bir fidye yazılımı vakasında)
ne yapacağını şaşırdığında açıp bakacağın ilk kaynaktır.

❔ Ne İşe Yarar? Olay müdahale sürecinin (Identification, Containment, Eradication, Recovery) her aşamasını adım adım anlatır.

🌟 Öne Çıkan Özelliği: İçerisinde hazır kontrol listeleri (checklists) bulunur. "Bir SQL Injection tespit edildiğinde izlenmesi gereken 10 adım" gibi pratik şablonlar sunar.

2026 Bakışı: Modern versiyonları, bulut (AWS/Azure) tabanlı sızıntılara müdahale ve otomatize edilmiş SOAR süreçlerini de kapsar.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

📍 Blue Team Field Manual (BTFM) (Alan White & Ben Clark)

Eğer bir "komut ezberleme" sorunun varsa, BTFM senin en iyi dostundur. Bu kitapta uzun anlatımlar yoktur; sadece çözüm odaklı komutlar vardır.

❔Ne İşe Yarar? Windows, Linux, PowerShell, ağ cihazları ve çeşitli güvenlik araçları (Splunk, Wireshark vb.) için kritik komutları kategorize eder.

🌟 Öne Çıkan Özelliği: Küçük boyutludur (Field Manual). Bir sunucuya SSH ile bağlandığında, o an ihtiyacın olan o karmaşık log analiz komutunu şak diye bulmanı sağlar.

Neden Şart? GUI (Arayüz) çöktüğünde veya sadece terminale erişimin olduğunda savunma yapabilmeni sağlar.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

📍 Practical Packet Analysis (Chris Sanders)

Ağ trafiği, bir saldırganın asla gizleyemeyeceği tek izdir. Chris Sanders, bu kitapta sana "paketlerin dilini" öğretir.

❔Ne İşe Yarar? Wireshark kullanarak ağdaki normal trafik ile anormal (saldırı) trafiği arasındaki farkı cerrah titizliğiyle ayırmanı sağlar.

🌟 Öne Çıkan Özelliği: TCP/IP protokollerini sıkıcı bir ders gibi değil, gerçek vaka incelemeleri (Case Studies) üzerinden anlatır. Bir malware'in dışarıyla nasıl haberleştiğini paket paket izlemeyi öğrenirsin.

Mottosu: "Paket yalan söylemez." Loglar silinebilir, sistemler manipüle edilebilir ama ağdaki trafik gerçektir.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

📍 Linux Basics for Hackers (OccupyTheWeb)

Savunma yapacağın kalenin taşlarını bilmeden o kaleyi koruyamazsın. Dünyadaki sunucuların ve güvenlik araçlarının %90'ı Linux tabanlıdır.

❔ Ne İşe Yarar? Dosya sisteminden yetki yönetimine, ağ konfigürasyonundan Bash script yazımına kadar her şeyi "güvenlik" perspektifiyle anlatır.

🌟 Öne Çıkan Özelliği: Klasik Linux kitapları gibi "klasör nasıl oluşturulur" ile vakit kaybetmez; doğrudan "bir portu nasıl izlersin", "logları nasıl manipüle edersin" gibi konulara girer.

Neden Şart? İyi bir Blue Team üyesi, terminalde bir hacker kadar hızlı hareket edebilmelidir.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 


📍 Applied Network Defense (Chris Sanders) / The Practice of Network Security Monitoring

Bu kitaplar, "izleme" (monitoring) felsefesini savunmanın kalbine koyar.

❔ Ne İşe Yarar? Sadece "firewall kurdum, güvendeyim" demeyi değil; ağdaki her hareketi görünür kılmayı (Visibility) öğretir. 
Zeek (Bro), Suricata ve Snort gibi IDS/IPS sistemlerinin nasıl kurulacağını ve yönetileceğini anlatır.

🌟 Öne Çıkan Özelliği: Honeypot (Bal küpü) gibi saldırganı yanıltan sistemlerin stratejik kurulumunu kapsar.

Vizyon: Savunmayı statik bir duvar olmaktan çıkarıp, saldırganı takip eden dinamik bir av sahasına dönüştürür.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

📍 Incident Response & Computer Forensics

Saldırı bittikten sonra "Ne oldu?" sorusuna bilimsel yanıt verme kitabıdır.

❔ Ne İşe Yarar? Dijital delil toplama (Forensics) süreçlerini anlatır. Bir diskin imajı nasıl alınır, silinen veriler nasıl kurtarılır ve
saldırganın bıraktığı dijital parmak izleri nasıl birleştirilir sorularına yanıt verir.

🌟 Önemli Katkısı: Hukuki boyutu da ele alır. Topladığın delillerin mahkemede geçerli olması için gereken teknik prosedürleri öğretir.

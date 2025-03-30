# Vega
📶 WiFi Bağlantısı ve Akıllı Yönetim <br>
✔️ Cihaz açıldığında otomatik olarak tanımlı WiFi ağına bağlanır. <br>
✔️ Bağlantı koparsa sistem her 10 saniyede bir durumu kontrol eder ve otomatik olarak tekrar bağlanmaya çalışır. <br>
✔️ WiFi'ye bağlanılamazsa, cihaz otomatik olarak bir WiFi ağı oluşturur ("Ares ve Mia") ve kullanıcıdan yeni WiFi bilgisi ister. <br>
✔️ Web arayüzü üzerinden cihazın bağlı olduğu WiFi ağının adı (SSID), sinyal gücü (dBm) ve IP adresi gibi bilgileri görüntüleyebilirsiniz. <br>
✔️ WiFi bilgilerini silebilir ve cihazı fabrika ayarlarına döndürebilirsiniz.

🔄 Bu sayede cihaz internetsiz kalmaz, bağlantı her zaman aktif kalır.

🌐 Mobil Uyumlu Web Arayüzü
✔️ Cihazın kontrolü, herhangi bir uygulama gerektirmeden web tarayıcısı üzerinden yapılabilir.
✔️ Telefon, tablet ya da bilgisayardan erişim için mobil uyumlu tasarıma sahiptir.
✔️ Ana Sayfa:

Anlık mama seviyesi gösterilir.

"Besle" butonlarıyla manuel besleme yapılabilir.

Haftalık planlar, geçmiş loglar ve ayarlar sayfalarına hızlı erişim sunar.

✔️ Ayarlar Sayfası:

Cihaz ismini ve e-posta adresini değiştirme

WiFi bilgilerini görüntüleme ve sıfırlama

OTA (kablosuz güncelleme) yapma imkanı sunar.

✔️ Sistem Sayfası:

RAM ve flash kullanımı gibi teknik veriler gösterilir.

Güncelleme yükleme ve resetleme işlemleri yapılabilir.

🖥️ Arayüz, sade ve kullanıcı dostudur. Teknolojik bilgi gerektirmez.

🐾 Mama Seviyesi Ölçümü (HC-SR04 Ultrasonik Sensör)
✔️ Haznedeki mama yüksekliği ölçülerek %0 (boş) - %100 (dolu) aralığında görsel olarak gösterilir.
✔️ Seviyeyi ölçmek için ultrasonik dalgalar kullanır (temassız ve hijyenik).
✔️ Her 30 saniyede bir kontrol yapılır.
✔️ Mama seviyesi %10’un altına düşerse, kullanıcıya otomatik e-posta uyarısı gönderilir.
✔️ Seviyenin tekrar %10 üzerine çıkması durumunda sistem sıfırlanır ve yeniden uyarı göndermeye hazır hale gelir.

📉 Böylece mama bitmeden haberdar olursunuz.

📩 E-posta Bildirim Sistemi
✔️ Cihaz ilk kez ağa bağlandığında, girilen e-posta adresine "Hoş Geldiniz" mesajı gönderilir.
✔️ Manuel olarak mama verildiğinde, hangi butona (tek, çift, üçlü) basıldığına dair e-posta gönderilir.
✔️ Mama seviyesi kritik seviyeye düşerse, sistem otomatik uyarı e-postası gönderir.
✔️ E-posta adresi kolayca web arayüzü üzerinden değiştirilebilir.

📬 Evin dışında bile olsanız, cihaz sizi bilgilendirir!

⚙️ Servo Motor ile Hassas Mama Dağıtımı
✔️ Servo motor kontrollü sistem ile kapak yavaşça açılıp kapanır.
✔️ 3 farklı besleme seçeneği:
・🔹 Tek Besleme (1 porsiyon)
・🔹 Çift Besleme (2 porsiyon)
・🔹 Üçlü Besleme (3 porsiyon)
✔️ Mama sıkışmalarına karşı yavaş açılma ve kapanma hareketi uygulanır.
✔️ “x2” ve “x3” modlarında motor döngüleri tekrarlanarak mama akışı artırılır.

🐾 Evcil hayvanınızın mama ihtiyacına göre seçim yapabilirsiniz.

🧠 Planlı Otomatik Besleme
✔️ Haftanın 7 günü için her gün 3 farklı zaman planlanabilir.
✔️ Her plan için saat, dakika, porsiyon ve aktiflik ayarlanabilir.
✔️ Cihaz her dakikayı kontrol eder ve planlı saate ulaştığında otomatik besleme yapar.
✔️ Planlar web arayüzünden kolayca görülebilir, değiştirilebilir ve silinebilir.
✔️ Aktif planlar haftalık tabloda listelenir, isteğe göre gün bazlı filtreleme yapılabilir.

📅 Tatilde ya da evde olmadığınızda bile düzenli besleme sağlanır.

🗂️ Loglama Sistemi (Besleme Geçmişi)
✔️ Cihaz tüm manuel ve planlı besleme olaylarını tarih ve saat bilgisiyle kayıt altına alır.
✔️ Her kayıt: Tarih, besleme türü ve porsiyon bilgilerini içerir.
✔️ Son 50 kayıt hafızada tutulur (daha fazla yer kaplamaması için).
✔️ Geçmiş kayıtlar tablo halinde listelenir ve grafikle görselleştirilir.
✔️ İsteğe bağlı olarak loglar tek tuşla silinebilir.

📈 Bu sayede hangi gün ve saatte ne kadar mama verildiğini takip edebilirsiniz.

📊 Grafikli Mama Takibi
✔️ Geçmiş beslemeler bir çizgi grafik üzerinde gösterilir.
✔️ Grafik her cihazda uyumlu şekilde (responsive) gösterilir.
✔️ Porsiyon miktarları zaman çizgisine göre izlenebilir.
✔️ Görsel olarak hangi zamanlarda yoğun besleme yapıldığı anlaşılır.

📉 Görsel analiz sayesinde besleme alışkanlıklarını takip edebilirsiniz.

🔄 OTA (Kablosuz Yazılım Güncelleme)
✔️ Web arayüzü üzerinden .bin dosyası yükleyerek cihazın yazılımı güncellenebilir.
✔️ Güncelleme sonrası cihaz otomatik olarak yeniden başlar.
✔️ Yeni özellikler, hata düzeltmeleri ve iyileştirmeler kolayca yüklenebilir.

🛠️ Bilgisayar bağlantısı olmadan cihaz güncel kalır!

🔗 JSON API ile Dış Sistem Entegrasyonu
✔️ /mamaSeviyesi adresinden cihazın anlık mama seviyesi JSON formatında alınabilir.
✔️ Başka bir sistem veya uygulama bu veriyi kullanarak kendi ekranında gösterim yapabilir.

📡 Bu sayede ev otomasyonu gibi sistemlere kolayca entegre olur.

💡 Ek Özellikler
✔️ Kullanıcı tarafından cihaz ismi değiştirilebilir ve web arayüzde bu isim görünür.
✔️ Hazne seviyesi API’si dış sistemlerle bağlantı kurmak için uygundur.
✔️ WiFi sinyal gücü grafiksel emojiyle gösterilir (🚀, ✅, ⚠️, 🔴, ❌).
✔️ Cihaz adı ve e-posta adresi kalıcı olarak EEPROM’da saklanır, elektrik kesilse bile kaybolmaz.

🔋 Enerji kesilse bile verileriniz güvende!


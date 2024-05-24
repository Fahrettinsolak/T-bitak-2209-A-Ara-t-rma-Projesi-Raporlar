# Tubitak-2209-A Arastirma-Projesi-Raporlar
TÜBİTAK 2209-A Araştırma Projesi kapsamında hazırladığım tüm proje raporları ve yarışma ile ilgili bilgilendirmeler mevcuttur.

# Akıllı Ulaşım Projesi - DATABOX

## 1. Giriş 

Günümüzün trafik koşullarında meydana gelen olayların izlenmesi ve geri bildirim ile kontrol altına alınması için akıllı ulaşım altyapıları inşa edilmeye başlanmıştır. Bu altyapıların etkin çalışabilmesi, son kullanıcı olan sürücünün interaktif bir şekilde takip edilmesini gerektirir. Artan üretim maliyetleri nedeniyle araçlarda opsiyonel olarak sunulan güvenlik paketlerinin dışında, kullanıcıların satın alabileceği ve araçlara harici olarak takılabilecek donanımlara ihtiyaç duyulmaktadır. Bu proje kapsamında, sensörler aracılığıyla sürücüler için nasıl faydalı hizmetler sağlanabileceği üzerine çıkarımlar yapılmıştır. 

Bu çalışma, VANET (Vehicular Ad Hoc Network) ağına dahil olmadan, araçlarda bulunacak harici bir IoT cihazı üzerinden kurgulanmıştır. Çalışma süresince yapılan geliştirmeler ile çoklu ham sensör verisinin, akıllı ev uygulamaları için geliştirilmiş modelleri, VANET kapsamında akıllı ulaşım için daha etkin bir şekilde kullanılarak geliştirilmiştir. Sensör verilerinden elde edilen çıkarımlar, trafikte oluşabilecek kazalar için kanıt toplama ve sürücü davranışlarını sınıflandırma amaçlı kullanılmış ve bu amaçlara uygun tavsiye ve karar destek sistemi geliştirilmiştir. 

ESP32 tabanlı geliştirilen cihaza entegre ivme, yön, GPS ve diğer sensörlerden toplanan veriler, Bluetooth ile mobil uygulamaya aktarılarak, oradan da sunucuya işlenmek üzere gönderilir. Bu verilerden kaza takibi ve sürücü profillendirme için gerekli bilgiler elde edilir ve önleyici olabilecek çıkarımlar mobil uygulama üzerinden sunucudan telefona, oradan da hem cihaza hem de sürücüye aktarılabilir. Ayrıca kaza anında sürücüler verilerini kablosuz olarak paylaşarak kaza tutanaklarını tutabileceklerdir. 

## 2. Rapor Dönemlerinde Yapılan Çalışmalar 

Projemizin başlangıcından itibaren, belirlenen iş paketleri ve hedefler doğrultusunda yoğun bir çalışma süreci gerçekleştirilmiştir. İlk olarak, akıllı ulaşım sistemleri ve sentetik sensör teknolojileri üzerine kapsamlı bir literatür taraması yapıldı. Bu süreçte mevcut teknolojiler, metodolojiler ve uygulama alanları hakkında derinlemesine bilgi edinildi. Literatür taraması sonucunda, projenin özgün değerini artıracak ve mevcut sorunlara yenilikçi çözümler sunacak bir yaklaşım belirlendi. Aynı zamanda proje planlaması yapılarak iş paketleri detaylandırıldı ve bir iş zaman çizelgesi oluşturuldu. Görev dağılımları yapılarak ekip üyelerinin sorumlulukları belirlendi. Kullanılacak ESP32 cihazları ve ilgili sensörler temin edilerek donanım ve yazılım gereksinimlerinin belirlenmesi süreci başlatıldı. 

ESP32 cihazlarıyla uyumlu çeşitli sensörler entegre edilerek veri toplama sistemi oluşturuldu. Bu sensörler hız, ivme, konum ve diğer önemli verileri toplayabilecek şekilde yapılandırıldı. Sensörlerden elde edilen verilerin doğruluğunu ve güvenilirliğini test ın kullanıcı arayüzü tasarlandı ve temel fonksiyonları kodlandı. Mobil uygulamanın anlaşılabilirliğinin kolay olmasına ve hızlı veri iletimine yönelik optimizasyonlar gerçekleştirildi. Geliştirilen mobil uygulamanın ekran resmi Şekil 1’deki gibidir.

### Şekil 1 – Mobil Uygulama Giriş Arayüzü

![Ekran görüntüsü 2024-05-24 034251](https://github.com/Fahrettinsolak/Tubitak-2209-A-Arastirma-Projesi-Raporlari/assets/79358514/4c00bfdf-a591-42c8-bddf-34e3f1f8fab3)


Toplanan verilerin işlenmesi ve analiz edilmesi için gerekli yazılım modülleri geliştirildi. Bu modüller, sürücü davranışlarını analiz ederek normal ve anormal sürüş örüntülerini belirlemek üzere tasarlandı. Veriler, makine öğrenimi algoritmaları kullanılarak işlenmiş ve sürücü profilleme çalışmaları gerçekleştirilmiştir. Analiz edilen veriler kullanılarak sürücü profilleri oluşturulmuş ve bu profiller, sürücülerin güvenli sürüş alışkanlıkları ve potansiyel risk faktörleri hakkında bilgi sağlamıştır. Ayrıca, sürücü profillerine dayalı olarak güvenli sürüşü teşvik eden ve potansiyel riskleri azaltan önleyici tavsiyeler geliştirilmiştir. Bu tavsiyeler mobil uygulama üzerinden sürücülere iletilmiş ve anında geri bildirim sağlanmıştır.

Sonuç olarak, gerçekleştirilen çalışmalar sonucunda projenin başlangıçta belirlenen amaçlarına büyük ölçüde ulaşıldığı görülmüştür. Akıllı ulaşım sistemlerinde kullanılabilecek düşük maliyetli ve etkin bir sentetik sensör çözümü geliştirilmiş olup, sürücülere ve ilgili birimlere anlık veri sağlayarak trafik güvenliğini artırmaya yönelik önemli bir adım atılmıştır. Geliştirilen prototipe ait görseller Şekil 2 ve Şekil 3’deki gibi verilmiştir.

### Şekil 2 – Prototipe Ait Görsel

![4](https://github.com/Fahrettinsolak/Tubitak-2209-A-Arastirma-Projesi-Raporlari/assets/79358514/645e7a7d-e3fa-49ea-a17f-5e33a0b18754)


### Şekil 3 – Prototipe Ait Görsel

![2](https://github.com/Fahrettinsolak/Tubitak-2209-A-Arastirma-Projesi-Raporlari/assets/79358514/0741d25b-eb93-4be0-8548-a434541b4fc6)


## 3. Sonuç
Projemizin gerçekleştirilme süreci boyunca yapılan çalışmalar ve elde edilen sonuçlar, başlangıçta belirlenen amaçlara ulaşıldığını göstermektedir. Günümüzün trafik koşullarında meydana gelen olayların izlenmesi ve geri bildirim ile kontrol altına alınması için geliştirilen bu sistem, akıllı ulaşım altyapılarının etkinliğini artırmakta önemli bir rol oynamıştır. Sürücülerin interaktif bir şekilde takip edilmesi ve anlık veri sağlanması, trafik güvenliğinin artırılmasına yönelik büyük bir adım olmuştur.

Projenin başlangıcında yapılan kapsamlı literatür taraması, mevcut teknolojiler ve metodolojiler hakkında derinlemesine bilgi edinilmesine olanak sağlamış, böylece proje özgün ve yenilikçi bir yaklaşımla şekillendirilmiştir. Belirlenen iş paketleri ve zaman çizelgesi doğrultusunda yapılan planlama, projenin disiplinli bir şekilde ilerlemesini sağlamış ve her aşamada net hedeflerin belirlenmesine yardımcı olmuştur.

ESP32 tabanlı cihazların çeşitli sensörlerle entegre edilmesi, veri toplama sisteminin oluşturulmasında önemli bir adım olmuştur. Hız, ivme, konum gibi kritik verilerin toplanması, bu verilerin doğruluğunun saha testleri ile teyit edilmesi ve analiz edilmesi, sistemin güvenilirliğini artırmıştır. Mobil uygulama geliştirilmesi ve optimizasyonu, kullanıcıların kolay ve hızlı bir şekilde veri erişimini sağlamış, bu sayede sürücülere anlık geri bildirim verilerek güvenli sürüş teşvik edilmiştir.

Toplanan verilerin makine öğrenimi algoritmaları ile işlenmesi ve sürücü profilleme çalışmaları, sistemin etkinliğini artırmış ve sürücülerin davranışlarını analiz ederek normal ve anormal sürüş örüntülerini belirlemiştir. Bu analizler sonucunda, sürücülere yönelik önleyici tavsiyeler geliştirilmiş ve bu tavsiyeler mobil uygulama üzerinden anında iletilmi

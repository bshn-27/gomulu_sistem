# Gömülü Sistemler: Temel Bilgiler, Gereksinimler, Yapı, Kartlar, Geliştirme Ortamları ve Uygulama Alanları

## Gömülü Sistemlere Giriş

Gömülü sistemler, belirli bir görevi yerine getirmek üzere tasarlanmış, donanım ve yazılım bileşenlerinden oluşan özel amaçlı sistemlerdir. İlk örnekleri 1960'lı yıllara dayanan bu sistemlerin öncüsü, 1961'de Charles Stark Draper Laboratuvarı tarafından geliştirilen Apollo Kılavuzluk Bilgisayarı'dır. Günümüzde otomotiv, sağlık, telekomünikasyon, tüketici elektroniği ve endüstriyel otomasyon gibi çeşitli sektörlerde yaygın olarak kullanılmaktadırlar. Düşük maliyet, yüksek performans ve enerji verimliliği gibi avantajları, gömülü sistemlerin kullanımını giderek artırmaktadır.

### Gömülü Sistemlerin Temel Bileşenleri

Gömülü sistemler, belirli işlevleri yerine getirmek için bir araya getirilmiş çeşitli cihaz ve bileşenlerden oluşur:

1.  **Mikrodenetleyici (Microcontroller):** Gömülü sistemlerin merkezi işlem birimidir (CPU). İşlemci, bellek ve giriş/çıkış birimlerini içerir.
2.  **Sensörler:** Çevresel verileri toplayarak dijital sinyallere dönüştürür ve mikrodenetleyiciye iletir.
3.  **Aktüatörler:** Elektriksel sinyalleri mekanik harekete dönüştürerek sistemin çevreyle etkileşime girmesini sağlar.
4.  **Hafıza Birimleri:** Verilerin geçici veya kalıcı olarak saklanmasını sağlar. Flash bellek, EEPROM ve SRAM gibi farklı türleri bulunur.
5.  **Güç Kaynağı:** Sistemin çalışması için gerekli enerjiyi sağlar. Pil, adaptör veya enerji toplama yöntemleriyle sağlanabilir.
6.  **Haberleşme Modülleri:** Sistemin diğer cihazlarla veya ağlarla iletişim kurmasını sağlar. Wi-Fi, Bluetooth, Zigbee gibi protokolleri destekler.
7.  **Giriş/Çıkış Birimleri (I/O Devices):** Kullanıcıların sistemle etkileşime geçmesini sağlar. Düğmeler, anahtarlar, ekranlar gibi cihazları içerir.
8.  **Geliştirme Kartları:** Sistemin prototiplenmesi ve test edilmesi için kullanılır. Arduino, Raspberry Pi gibi kartlar bu amaçla kullanılır.

### Gömülü Sistemlerin Gereksinimleri

Gömülü sistemlerin başarılı bir şekilde çalışabilmesi için belirli gereksinimlerin karşılanması önemlidir:

1.  **Güvenilirlik:** Gömülü sistemlerin kesintisiz ve doğru bir şekilde çalışması gereklidir. Özellikle kritik uygulamalarda güvenilirlik büyük önem taşır.
2.  **Enerji Verimliliği:** Gömülü sistemler genellikle pil ile çalıştığından, düşük güç tüketimi önemlidir. Enerji verimliliği, sistemin uzun süre çalışmasını sağlar.
3.  **Gerçek Zamanlı İşlem:** Birçok gömülü sistem, belirli bir zaman diliminde tepki vermesi gereken gerçek zamanlı uygulamalar için tasarlanır. Bu nedenle, zamanlama ve hızlı işlem yetenekleri önemlidir.
4.  **Ölçeklenebilirlik:** Gömülü sistemlerin farklı uygulamalara adaptasyonunu kolaylaştırmak için ölçeklenebilir olması gereklidir. Donanım ve yazılım bileşenleri, farklı gereksinimlere göre uyarlanabilir olmalıdır.
5.  **Maliyet Etkinliği:** Gömülü sistemlerin üretim ve bakım maliyetleri düşük olmalıdır. Bu, özellikle geniş çaplı üretimlerde ve tüketici elektroniği gibi alanlarda önemlidir.

## Gömülü Sistemlerde Kullanılan Kartlar

Gömülü sistemlerde kullanılan kartlar, sistemin tasarımı ve geliştirilmesi aşamalarında büyük önem taşır. Bu kartlar, özellikle prototipleme, test ve uygulama geliştirme süreçlerinde kullanılır.

### Yaygın Gömülü Sistem Kartları

1.  **Arduino:** Açık kaynaklı donanım ve yazılımlarıyla bilinir. Kolay kullanılabilirliği ve geniş topluluk desteği sayesinde hobi projelerinden profesyonel uygulamalara kadar geniş bir yelpazede tercih edilir. Analog ve dijital giriş/çıkış pinleri, çeşitli sensörler ve aktüatörlerle kolayca entegre edilebilir.
2.  **Raspberry Pi:** Tam teşekküllü bir mini bilgisayardır. Yüksek işlem gücü ve geniş bağlantı seçenekleri sunar. HDMI, USB, Ethernet gibi bağlantı noktaları sayesinde çeşitli uygulamalarda kullanılabilir. Linux tabanlı bir işletim sistemi çalıştırabilir ve daha karmaşık projeler için idealdir.
3. **ESP32:** Düşük maliyetli ve yüksek performanslı bir Wi-Fi ve Bluetooth mikrodenetleyicisidir. Kablosuz iletişim gerektiren projeler için idealdir. Geniş bir topluluk desteği ve çeşitli geliştirme araçları sunar.
4.  **STM32 Discovery:** STMicroelectronics tarafından üretilen mikrodenetleyici geliştirme kartlarıdır. Yüksek performanslı ARM Cortex-M serisi işlemciler kullanır. Endüstriyel uygulamalar ve gerçek zamanlı işlemler için uygundur. Geniş bir kütüphane ve araç desteği sunar.
5.  **BeagleBone:** Yüksek performans ve geniş I/O seçenekleri sunar. Linux tabanlı bir işletim sistemi çalıştırabilir ve endüstriyel uygulamalar için uygundur. HDMI, Ethernet, USB gibi bağlantı noktaları sayesinde çeşitli projelerde kullanılabilir.

### Kartların Karşılaştırmalı Özellikleri

| Kart            | Kullanım Kolaylığı | İşlem Gücü | Bağlantı Seçenekleri | Uygulama Alanları                                                 |
| :-------------- | :----------------- | :--------- | :------------------- | :---------------------------------------------------------------- |
| Arduino         | Kolay              | Düşük      | Sınırlı              | Eğitim, hobi projeleri, prototipleme                              |
| Raspberry Pi    | Orta               | Yüksek     | Geniş                | Multimedya, IoT, ev otomasyonu, eğitim, araştırma                 |
| STM32 Discovery | Orta               | Yüksek     | Orta                 | Endüstriyel uygulamalar, gerçek zamanlı işlemler                  |
| BeagleBone      | Orta               | Yüksek     | Geniş                | Endüstriyel otomasyon, gelişmiş IoT uygulamaları                  |
| ESP32           | Kolay              | Orta       | Sınırlı              | Kablosuz iletişim, düşük güç tüketimi gerektiren IoT uygulamaları |

### Kartların Yetenekleri ve Kısıtlamaları

1.  **Arduino:**

    *   **Yapabildikleri:**
        *   Kolay Kullanım: Basit programlama dili ve geniş topluluk desteği sayesinde hızlı prototipleme sağlar.
        *   Çeşitli Sensör ve Aktüatör Desteği: Analog ve dijital giriş/çıkış pinleri ile birçok sensör ve aktüatör ile uyumlu çalışır.
        *   Geniş Donanım Çeşitliliği: Farklı ihtiyaçlara yönelik çeşitli Arduino modelleri bulunur.
    *   **Yapamadıkları:**
        *   Yüksek İşlem Gücü Gerektiren Uygulamalar: Karmaşık ve yüksek işlem gücü gerektiren uygulamalarda yetersiz kalabilir.
        *   İleri Düzey Grafik ve Multimedya İşlemleri: Grafik ve multimedya işlemleri için yeterli donanıma sahip değildir.
2.  **Raspberry Pi:**

    *   **Yapabildikleri:**
        *   Yüksek İşlem Gücü: Tam teşekküllü bir mini bilgisayar olarak yüksek işlem gücü sunar.
        *   Geniş Bağlantı Seçenekleri: HDMI, USB, Ethernet gibi çeşitli bağlantı noktaları ile geniş uygulama yelpazesi sunar.
        *   İşletim Sistemi Desteği: Linux tabanlı işletim sistemleri çalıştırabilir, bu da daha karmaşık projeler için idealdir.
    *   **Yapamadıkları:**
        *   Düşük Güç Tüketimi Gerektiren Uygulamalar: Göreceli olarak yüksek güç tüketimi nedeniyle pil ile uzun süreli çalışmalarda uygun olmayabilir.
        *   Gerçek Zamanlı İşlemler: Gerçek zamanlı işlem gereksinimleri olan uygulamalarda, mikrodenetleyiciler kadar hassas ve güvenilir olmayabilir.
3.  **STM32 Discovery:**

    *   **Yapabildikleri:**
        *   Yüksek Performans: ARM Cortex-M serisi işlemciler ile yüksek performans sunar.
        *   Gerçek Zamanlı İşlem: Endüstriyel ve gerçek zamanlı uygulamalar için uygundur.
        *   Geniş Kütüphane ve Araç Desteği: Gelişmiş kütüphane ve araç desteği ile çeşitli uygulamalara entegre edilebilir.
    *   **Yapamadıkları:**
        *   Kapsamlı Multimedya İşlemleri: Multimedya işlemleri için uygun değildir.
        *   Geniş Topluluk Desteği Eksikliği: Arduino ve Raspberry Pi kadar geniş bir topluluk desteği bulunmayabilir.
4.  **BeagleBone:**

    *   **Yapabildikleri:**
        *   Yüksek Performans: Güçlü işlemcileri ve geniş I/O seçenekleri ile yüksek performans sunar.
        *   Endüstriyel Uygulamalar: Endüstriyel otomasyon ve kontrol uygulamaları için idealdir.
        *   İşletim Sistemi Desteği: Linux tabanlı işletim sistemleri çalıştırabilir.
    *   **Yapamadıkları:**
        *   Düşük Güç Tüketimi Gerektiren Uygulamalar: Yüksek güç tüketimi nedeniyle pil ile uzun süreli çalışmalarda uygun olmayabilir.
        *   Basit ve Hızlı Prototipleme: Arduino kadar basit ve hızlı prototipleme imkanı sunmayabilir.
5.  **ESP32:**

    *   **Yapabildikleri:**
        *   Kablosuz İletişim: Wi-Fi ve Bluetooth desteği ile kablosuz iletişim gerektiren projeler için uygundur.
        *   Düşük Maliyet ve Güç Tüketimi: Düşük maliyetli ve enerji verimli bir çözümdür.
        *   Geniş Topluluk Desteği: Geniş bir topluluk ve çeşitli geliştirme araçları sunar.
    *   **Yapamadıkları:**
        *   Yüksek İşlem Gücü Gerektiren Uygulamalar: Raspberry Pi kadar yüksek işlem gücü sunmaz.
        *   Kapsamlı Bağlantı Seçenekleri: HDMI ve Ethernet gibi geniş bağlantı seçeneklerine sahip değildir.

### Proje Tabanlı Donanım Seçimi

Gömülü sistem projelerinde kullanılan donanımın seçimi, projenin gereksinimlerine ve özelliklerine bağlı olarak değişir:

*   **Arduino:** Eğitim projeleri, hobi projeleri, prototipleme.
*   **Raspberry Pi:** Multimedya uygulamaları, IoT ve ev otomasyonu, eğitim ve araştırma.
*   **STM32 Discovery:** Endüstriyel uygulamalar, gerçek zamanlı işlemler, gelişmiş prototipleme.
*   **BeagleBone:** Endüstriyel otomasyon, gelişmiş IoT uygulamaları, eğitim ve araştırma.
*   **ESP32:** Kablosuz iletişim, IoT uygulamaları, düşük güç tüketimi gerektiren projeler.

### Kartlar Arasındaki Hız Farkları

Gömülü sistem projelerinde kullanılan çeşitli kartlar arasında hız farkları bulunmaktadır:

*   **Arduino:** 16 MHz - 48 MHz (Düşük hız, basit projeler için uygun)
*   **Raspberry Pi:** 1.2 GHz - 2.4 GHz (Yüksek işlem gücü, karmaşık projeler için ideal)
*   **STM32 Discovery:** 72 MHz - 480 MHz (Orta-yüksek hız, gerçek zamanlı ve endüstriyel projeler için uygun)
*   **BeagleBone:** 1 GHz (Yüksek hız, endüstriyel ve IoT projeleri için ideal)
*   **ESP32:** 160 MHz - 240 MHz (Orta hız, kablosuz iletişim ve düşük maliyetli projeler için uygun)

## Geliştirme Ortamları ve Linux Desteği

Gömülü sistem projelerinde kullanılan geliştirme ortamları ve bazı kartların Linux desteği hakkında bilgiler:

### Geliştirme Ortamları

*   **Arduino:** Arduino IDE (Kolay kullanım, geniş kütüphane desteği, geniş topluluk desteği)
*   **ESP32:** ESP-IDF (FreeRTOS tabanlı, kablosuz iletişim, gelişmiş araç seti)
*   **Raspberry Pi:** Raspberry Pi OS ve Visual Studio Code (Gelişmiş projeler ve multimedya uygulamaları, geniş Linux desteği)

### Linux Desteği

*   **Raspberry Pi:** Debian tabanlı, çoklu dil desteği, geniş bağlantı seçenekleri

### Arduino IDE ve İşleyişi

**Arduino IDE (Integrated Development Environment)**, Arduino kartları için özel olarak tasarlanmış, açık kaynak kodlu bir geliştirme ortamıdır. Temelde C ve C++ dillerini temel alır ve kod yazma, derleme ve Arduino kartına yükleme süreçlerini basitleştirir.

*   **Arduino Bootloader:** Arduino kartlarının üzerinde bulunan ve kartın başlatılmasını sağlayan küçük bir programdır. Bilgisayardan gönderilen yeni kodların kartın hafızasına yazılmasını yönetir.
    *   *İşlevi:* Kartın enerji verildiğinde başlamasını sağlar, bilgisayar ile iletişim kurarak yeni programların yüklenmesini mümkün kılar.
*   **C/C++ Kodlarının Çalıştırılması:** Arduino IDE'de yazılan C/C++ kodları, derleyici (compiler) aracılığıyla makine koduna çevrilir ve Arduino kartına yüklenir.
    *   *Süreç:*
        1.  Kod yazılır ve Arduino IDE'de derlenir.
        2.  Derlenen kod, bootloader aracılığıyla Arduino kartının hafızasına (genellikle Flash bellek) yazılır.
        3.  Kart yeniden başlatıldığında, bootloader yeni kodu çalıştırır.

*   **Setup ve Loop Fonksiyonları:**
    *   `setup()`: Programın başlangıcında sadece bir kez çalışır. Giriş/çıkış pinlerinin ayarlanması, seri haberleşme başlatılması gibi işlemler bu fonksiyon içinde yapılır.
    *   `loop()`: `setup()` fonksiyonu tamamlandıktan sonra sürekli olarak tekrar eden ana program döngüsüdür. Sensörlerden veri okuma, motorları kontrol etme, LED'leri yakıp söndürme gibi işlemler bu fonksiyon içinde gerçekleştirilir.
    *   *Çalışma Prensibi:* Arduino programı başladığında, önce `setup()` fonksiyonu çalışır. Daha sonra, `loop()` fonksiyonu sürekli olarak tekrarlanır. Bu döngü, kartın enerjisi kesilene kadar devam eder.

### Arduino ile Yapay Zeka ve IoT Projeleri

*   **Arduino ile Yapay Zeka Projeleri:**
    *   Arduino'nun sınırlı işlem gücü ve hafızası nedeniyle karmaşık yapay zeka projeleri doğrudan Arduino üzerinde çalıştırmak zordur. Ancak, basit algoritmalar (örneğin, basit bir sinir ağı veya karar ağacı) veya önceden eğitilmiş modellerin çıkarım (inference) işlemleri Arduino üzerinde gerçekleştirilebilir.
        *   *Nasıl Yapılır:* TensorFlow Lite Micro gibi kütüphaneler kullanılarak, küçük boyutlu ve optimize edilmiş yapay zeka modelleri Arduino'ya yüklenebilir.
    *   Daha karmaşık yapay zeka uygulamaları için, Arduino sensör verilerini toplayıp bir bilgisayara veya bulut platformuna gönderebilir ve yapay zeka işlemleri bu ortamlarda gerçekleştirilebilir.
        *   *Neden Karmaşık AI Modelleri Doğrudan Çalışmaz:* Arduino'nun sınırlı kaynakları (RAM, işlemci hızı) nedeniyle, büyük ve karmaşık AI modelleri pratik olarak çalıştırılamaz.
*   **Arduino Uno ile IoT Projeleri:**
    *   Arduino Uno, sınırlı kaynaklara sahip olduğu için doğrudan Wi-Fi veya Bluetooth bağlantısı sunmaz. Bu nedenle, IoT projeleri için ek modüller (örneğin, ESP8266 Wi-Fi modülü) kullanılması gerekir.
        *   *Ek Modüller ile IoT:* ESP8266 gibi modüller, Arduino Uno'ya Wi-Fi yeteneği kazandırarak internete bağlanmasını ve veri göndermesini/almasını sağlar.
    *   Arduino Uno ile sıcaklık, nem, ışık gibi sensör verilerini toplayıp bu verileri bir IoT platformuna gönderebilir ve uzaktan izleme veya kontrol uygulamaları geliştirebilirsiniz.
        *   *Örnek Uygulamalar:*
            *   Ev otomasyonu (ışık kontrolü, sıcaklık izleme)
            *   Çevresel izleme (hava kalitesi, toprak nemi)
            *   Akıllı tarım (sensör verileriyle sulama kontrolü)

## Gömülü Sistem Projelerinin Uygulanabilirliğinin Ölçülmesi

Gömülü sistem projelerinin uygulanabilirliğini ölçmek için çeşitli faktörler dikkate alınır:

1.  **Performans:** Sistemin belirlenen görevleri ne kadar hızlı ve verimli bir şekilde yerine getirdiği.
    *   *Ölçütler:* İşlem hızı, tepki süresi, veri işleme kapasitesi.
2.  **Güvenilirlik:** Sistemin ne kadar süreyle hatasız çalıştığı ve arızalara karşı ne kadar dayanıklı olduğu.
    *   *Ölçütler:* Ortalama arızalar arası süre (MTBF), hata toleransı, yedekleme mekanizmaları.
3.  **Güç Tüketimi:** Sistemin ne kadar enerji tükettiği ve pil ömrünün ne kadar uzun olduğu (özellikle mobil uygulamalar için önemlidir).
    *   *Ölçütler:* Aktif modda tüketilen güç, uyku modunda tüketilen güç, pil ömrü.
4.  **Maliyet:** Sistemin donanım, yazılım ve üretim maliyetleri.
    *   *Ölçütler:* Bileşen maliyetleri, geliştirme maliyetleri, üretim maliyetleri.
5.  **Boyut ve Ağırlık:** Sistemin fiziksel boyutu ve ağırlığı (özellikle taşınabilir veya küçük cihazlar için önemlidir).
    *   *Ölçütler:* Hacim, yüzey alanı, ağırlık.
6.  **Gerçek Zamanlılık:** Sistemin belirli olaylara zamanında tepki verme yeteneği (gerçek zamanlı uygulamalar için önemlidir).
    *   *Ölçütler:* En kötü durum tepki süresi, jitter.
7.  **Güvenlik:** Sistemin yetkisiz erişime ve saldırılara karşı ne kadar güvenli olduğu.
    *   *Ölçütler:* Şifreleme yöntemleri, kimlik doğrulama mekanizmaları, güvenlik açıkları.
8.  **Ölçeklenebilirlik:** Sistemin yeni özellikler veya daha fazla yük ile başa çıkabilme yeteneği.
    *   *Ölçütler:* Modüler tasarım, kaynak yönetimi, esneklik.

Bu faktörler, projenin gereksinimlerine ve önceliklerine göre farklı ağırlıklara sahip olabilir. Uygulanabilirlik değerlendirmesi, bu faktörlerin dengeli bir şekilde analiz edilmesini ve projenin hedeflerine ulaşma potansiyelinin belirlenmesini içerir.


ARM Mikrodenetleyici Uygulamaları Donanım Listesi
=================================================

ÖNEMLİ NOT: LİSTEDEKİ STM32F4 KARTLARINDAN YALNIZCA BİRİNİ EDİNMENİZ YETERLİ OLACAKTIR. LİSTE SEÇENEK SUNMAK AMACIYLA HAZIRLANMIŞTIR

Derste kullanılması muhtemel kartlar ve diğer donanım elemanlarının bazıları aşağıdaki listede yer almaktadır. Bu liste dışında bazı ölçü aletleri ve elemanlar da derste kullanılacaktır, ancak bunlar temini ve/veya fiyatı nedeniyle doğrudan tavsiye listesinde verilmemiştir. Belirtilen linkler ürünün görseli ve temin edilmesi için örnek niteliktedir, fiyat karşılaştırmaları yapılmamıştır. Ürünleri başka satıcılardan da temin edebilirsiniz.

ST-LINK USB PROGRAMLAYICI
https://urun.n11.com/diger/stlink-v2-stm8-stm32-programlayici-P395490429

CORTEX M3 GELİŞTİRME KARTI
Blue Pill STM32F103 Geliştirme Kartı
https://www.elektrovadi.com/urun/stm32f103c8t6-gelistirme-karti

Bu kartın orijinal ST işlemcisi dışında Çin kaynaklı farklı işlemci kullanan klon versiyonları da bulunmakta. Özellikle CH32F103 işlemcili olanlar yaygın. Ders konularının tam uyum açısından orijinal STM32F103C8T6 işlemcili kartı edinmeye gayret gösteriniz.

CORTEX M4 GELİŞTİRME KARTI
Bu mimaride birçok alternatif geliştirme kartı bulunmaktadır. Derste STM32F407 işlemcili "STM32F4 Discovery" kartı ağırlıklı olarak kullanılacaktır. Linklerdeki ürünler örnek niteliktedir, uygun gördüğünüz bir kartı ya da burada belirtilmemiş STM32F4x işlemcili başka bir alternatif geliştirme kartını küçük değişiklikler ile uygulamalarınızda kullanabilirsiniz.

STM32F4 Discovery
https://www.robotistan.com/stm32f4-discovery?gclid=CjwKCAjwqIiFBhAHEiwANg9szhf32uJVQGdssZlZnL7jYPO9g1izP7d3vLmCR9l4rT0K65ksM9PWyhoCB8cQAvD_BwE

Bu kart için Mikroelektronika firmasının base board olarak kullanılan shield kartı da bazı uygulamalarda kullanılacaktır. Bu ürünün edinilmesi zorunlu değildir ancak discovery kartı ile Mikroelektronika firmasının click board'larını kullanmak isteyenler için kolaylık sağlayabilir. 
https://www.elektrovadi.com/STM32F4-Discovery-Shield,PR-1996.html

STM32F4x1 Geliştirme Kartı
https://tr.aliexpress.com/item/1005001636616276.html?spm=a2g0s.9042311.0.0.16564c4d1X2jto

Mikroelektronika STM32M4 Clicker
https://www.elektrovadi.com/STM32-M4-Clicker,PR-2324.html

BREADBOARD / JUMPER SET
Piyasada birçok breadboard ve jumper kablo seçeneği bulunmaktadır, linktekiler örnektir. Ağırlıklı olarak standart boy kullanılacak olsa da değişik boyutta alternatif breadboard'lar bulundurmak faydalı olabilir.

https://www.hepsiburada.com/cumhur-140-adet-breadboard-jumper-kablo-dupont-pm-HBC00000541QX
https://www.robotistan.com/120-parca-100-mm-jumper-kablo-seti

USB-UART DÖNÜŞTÜRÜCÜ
https://urun.n11.com/arduino-urunleri-ve-setleri/usb-to-ttl-cevirici-modul-cp2102-arduino-yeni-5-pin-kablo-P372861750

4x4 MATRIX KEYBOARD
https://urun.n11.com/arduino-urunleri-ve-setleri/4x4-16-buton-keyboard-4-x-4-keypad-matrix-tus-takimi-P390090560

ALFANÜMERİK LCD MODÜL
https://www.robotistan.com/2x16-isiksiz-lcd-yesil-uzerine-siyah-hy-1602f-001

I2C/SPI OLED DISPLAY MODÜL (SSD1306)
https://urun.n11.com/arduino-urunleri-ve-setleri/096-7-pinli-spi-iletisimli-oled-lcd-modulu-P488354879
https://urun.n11.com/arduino-urunleri-ve-setleri/128x64-oled-grafik-ekran-096-inch-4-pin-mavi-P453500624

DİJİTAL TERMOMETRE
https://urun.n11.com/arduino-urunleri-ve-setleri/ds18b20-sicaklik-sensoru-P266512858

I2C SERIAL EEPROM
24Cxx, 24LCxx
https://www.direnc.net/24lc32--32k-25v-i2c-smart-serial-eeprom

PASİF ELEMANLAR
Eleman seçiminde breadboard kullanımına uygunluğa dikkat ediniz. SMD elemanlar breadboard için uygun değildir. 

Push Button (birkaç adet)
https://www.robotistan.com/4-pinli-push-buton-siyah-6x6x5mm

Direnç (Breadboard kullanımına uygun 1/4 1/8 Watt)
Derste kullanılması muhtemel değerler birkaç adet 1k, 4.7k, 10k olmakla birlikte diğer projelerle birlikte kullanabilmek için direnç paketi önerilir

Kondansatör (Breadboard kullanımına uygun)
Birkaç adet 100 nF seramik ya da polyester

Trimpot (ayarlı direnç)
10k Lineer 

BATARYA (5V USB POWERBANK)
Akıllı şarj devresi olmayan powerbank'ler tercih edilmelidir. Diğerleri düşük akımda enerji iletimini kestikleri için ARM kartlarını için uygun değildir.
https://www.hepsiburada.com/dexim-daksp0011-b-5000-mah-powerbank-siyah-p-HBV00000EN5MS?magaza=Zoccoshop

ÖLÇÜ ALETLERİ, LEHİMLEME DONANIMLARI
Zorunlu olmayıp imkanlar ölçüsünde değerlendirilmelidir
Multimetre, DSO (digital storage oscilloscope), USB akım/gerilim ölçer, havya & lehim malzemeleri

DİĞER
Mikro USB kablosu
Büyüteç











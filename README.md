# Arduino Uno Tabanlı Hırsız Alarm Sistemi

Bu proje, Arduino Uno kullanarak basit ve etkili bir hırsız alarm sistemi oluşturmayı amaçlamaktadır. Sistem, hareket sensörleri, buzzer ve LED gibi bileşenlerle donatılmıştır ve izinsiz girişleri tespit ettiğinde alarm verir.

## İçindekiler
- [Gereksinimler](#gereksinimler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Katkıda Bulunanlar](#katkıda-bulunanlar)

## Gereksinimler
Bu projeyi kurmak ve çalıştırmak için aşağıdaki bileşenlere ihtiyacınız olacak:
- Arduino Uno
- PIR hareket sensörü
- 2 Adet buton
- Buzzer veya siren
- LED ve 220 ohm direnç
- Breadboard ve jumper kablolar

## Kurulum
1. **Donanım Kurulumu:**
   - PIR hareket sensörünü breadboard'a yerleştirin ve VCC, GND ve sinyal pinleriniayın.
   - LED'i ve direnci breadboard'a yerleştirip, uygun pinlere bağlayın.
   - Buzzer veya sireni breadboard'a yerleştirip, uygun pinlere bağlayın.

2. **Yazılım Kurulumu:**
   - Arduino IDE'yi bilgisayarınıza indirip kurun: [Arduino IDE İndirme Sayfası](https://www.arduino.cc/en/software)
   - Bu repo'yu klonlayın veya zip dosyasını indirip çıkarın:
     ```sh
     git clone https://github.com/Tuvci/ArdunioUno-Burglar-Alarm-System.git
     ```
   - `codes.ino` dosyasını Arduino IDE ile açın.
   - Arduino'nuzu bilgisayara bağlayın ve doğru kart ve port ayarlarını yapın.
   - Kodu Arduino'ya yükleyin.

## Kullanım
Sistem kurulduktan ve kod yüklendikten sonra:
- Hareket sensörü herhangi bir hareket algıladığında LED yanacak ve buzzer çalacaktır.
- Alarm, hareket algılandığı sürece devam edecektir.
- Alarmı aktifleştirmek ve devre dışı bırakmak için butonları kullanmanız gerekmektedir.

## Katkıda Bulunanlar

Bu projede katkıda bulunan ekip üyeleri:

- **Üye 1**: [FATMAOZBEK](https://github.com/FATMAOZBEK)
- **Üye 2**: [GitHub Kullanıcı Adı](https://github.com/kullanici2)
- **Üye 3**: [GitHub Kullanıcı Adı](https://github.com/kullanici3)



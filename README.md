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
   - PIR hareket sensörünü breadboard'a yerleştirin ve VCC, GND ve sinyal pinlerini bağlayın.
   - LED'i ve direnci breadboard'a yerleştirip, uygun pinlere bağlayın.
   - Buzzer veya sireni breadboard'a yerleştirip, uygun pinlere bağlayın.

2. **Yazılım Kurulumu:**
   - Arduino IDE'yi bilgisayarınıza indirip kurun: [Arduino IDE İndirme Sayfası](https://www.arduino.cc/en/software)
   - Bu repo'yu klonlayın veya zip dosyasını indirip çıkarın:
     ```sh
     git clone https://github.com/Tuvci/ArdunioUno-HirsizAlarmSistemi.git
     ```
   - `codes.ino` dosyasını Arduino IDE ile açın.
   - Arduino'nuzu bilgisayara bağlayın ve doğru kart ve port ayarlarını yapın.
   - Kodu Arduino'ya yükleyin.

## Kullanım
Sistem kurulduktan ve kod yüklendikten sonra:
- Buton ile alarm sistemi aktif edilir.Alarmın aktif olduğu ledlere bakılarak anlaşılır.(kırmızı=alarm aktif değil, yeşil= alarm aktif)
- Hareket sensörü herhangi bir hareket algıladığında buzzer çalacaktır.
- Alarm, hareket algıladığı anda çalmaya devam edecektir.
- Alarmı devre dışı bırakmak için yeniden buton kullanmanız gerekmektedir.

## Katkıda Bulunanlar

Bu projede katkıda bulunan ekip üyeleri:

- **Üye 1**: [Tuğçe Karakuş](https://github.com/tugcekarakuss) 
- **Üye 2**: [Fatma ÖZBEK](https://github.com/FATMAOZBEK) 
- **Üye 3**: [Enes Efe AVŞAROĞLU](https://github.com/MaSCaR50)
- **Üye 4**:[Razen ŞEYHYUSUF](https://github.com/Razen20sh)



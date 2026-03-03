# Java IP Subnet Calculator

Bu proje, Java kullanarak ağ yöneticileri ve bilgisayar ağları öğrencileri için geliştirilmiş bir Alt Ağ (Subnet) Hesaplama aracıdır. Bitsel operatörler (bitwise operations) kullanılarak IP adreslerinin bellekteki 32-bitlik yapıları üzerinden matematiksel hesaplamalar yapılmıştır.

## Özellikler
Kullanıcıdan "IP_Adresi/CIDR" formatında (Örn: 192.168.1.10/24) alınan veriyle şu değerleri hesaplar:
* **Subnet Mask** (Alt Ağ Maskesi)
* **Network Address** (Ağ Adresi)
* **Broadcast Address** (Yayın Adresi)
* **Usable Host Count** (Kullanılabilir Cihaz/Host Sayısı)

## Nasıl Çalıştırılır?

1. Kodu derleyin:
   `javac SubnetCalculator.java`
2. Programı başlatın:
   `java SubnetCalculator`
3. Konsoldan istenen formatta bir IP ve prefix değeri girin (Örn: 10.0.0.5/8)

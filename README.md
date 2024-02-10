# Hesap Makinesi Uygulaması

Bu PyQt5 ile geliştirilmiş bir hesap makinesi uygulamasıdır. Kullanıcıların basit matematiksel işlemler yapmasına olanak tanır.

## Kurulum

Uygulamayı çalıştırmak için PyQt5 kütüphanesine ihtiyacınız olacaktır. Eğer PyQt5 yüklü değilse, terminal veya komut istemcisinde aşağıdaki komutu çalıştırarak PyQt5'i yükleyebilirsiniz:

```pip install pyqt5```


## Nasıl Kullanılır

- Hesap makinesi basit arayüzüyle kullanıcı dostudur.
- Sayılar ve işlemler için düğmeler kullanılır.
- Toplama, çıkarma, çarpma, bölme işlemleri yapılabilir.
- "=" düğmesine basarak hesaplamalar yapılabilir.
- "C" düğmesiyle ekran temizlenebilir.
- "<-" düğmesine basarak son girilen karakter silinebilir.
- Hesaplanamayan bir işlem girildiğinde ekranda "Hata!" mesajı gösterilir.

## Uygulamanın Çalıştırılması

Uygulamayı çalıştırmak için terminal veya komut istemcisinde dosyanın bulunduğu dizine gidin ve aşağıdaki komutu çalıştırın:

```python hesap_makinesi.py```


## Ek Bilgiler

- PyQt5, Python ile kullanıcı arayüzü geliştirmek için yaygın olarak kullanılan bir kütüphanedir.
- Bu hesap makinesi uygulaması, PyQt5'in temel özelliklerini kullanarak basit bir arayüz oluşturmayı ve temel hesaplama işlemlerini gerçekleştirmeyi göstermektedir.
- Güvenlik amacıyla `eval()` fonksiyonu kullanılarak girilen metinler doğrudan çalıştırılmamış, bu sayede zararlı kodların en aza indirilmesi hedeflenmiştir.



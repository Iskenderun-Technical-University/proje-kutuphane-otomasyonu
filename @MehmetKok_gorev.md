# proje-kutuphane-otomasyonu
proje-onerisi-kutuphane-otomasyonu created by GitHub Classroom

# YAZILIMIN GELİŞTİRİLMESİ(YERİNE GETİRİLEN SORUMLULUKLAR)

## Formlar
###  Login Ekranı(Formu)
**
    ***Login ekranı işlemleri yapıldı. Kullanıcılar ve yöneticiler farklı girişler ile otomasyona giriş yapabilecekler. Şifresini unutan ve değiştirmek istemeyen kullanıcılar için veritabanında kayıtlı olduğu mail ile şifresi gönderilecektir. Bunun için kullanılan kütüphaneler ise  “using System.Security;” ve "Sysytem.Net.Mail;". Bu kütüphaneler ile smtp protokolü ve otomasyonumuz arasında bağlantı sağlanmıştır.
    Üye olmayan kullanıcılar ek bir bağlantı üzerinden yeni bir üyelik oluşturabilecekler.***
###  Personel Ekranı
**    ***Personeller kitaplar, yazarlar , ve kendi bilgileri ile ilgili değişiklik yapabilecekler. Kullanıcıların forumlarda oluşturdukları yorumları kontrol edip gerekli işlemleri yapabilecektir.
#### Yönetici
**    Sadece yönetici tüm  işlemleri yapma hakkına sahiptir. Herhangi gibi bir personelin üyelerle ilgili değişiklik hakkı veya bilgilerini görme hakkı güvenliği sağlamak açısından yoktur.
###  Kitaplar
**    Kullanıcılar bu form üzerinde sadece kitaplar hakkında veritabanından çekilen bilgileri görebiliyor. Filtreleme yaparak ulaşmak istedikleri bilgilere ulaşabiliyor.

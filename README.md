# 🎓 Teknoloji Atölyeleri Sınıf Yönetim Platformu – yap_web

Bu proje, ortaokul düzeyindeki **Teknoloji Atölyeleri** öğrencileri için özel olarak geliştirilmiş bir **sınıf yönetim ve etkileşim platformudur**.  
Eğitmenler ve öğrenciler, sınıflara özel paneller üzerinden:

- 📢 Duyuruları takip edebilir  
- ✅ Yoklamalara katılabilir  
- 📂 Ödev teslim edebilir  
- ⏳ Mazeret bildiriminde bulunabilir  
- 📊 Eğitmen paneli üzerinden tüm verileri analiz edebilir  
- 🔐 Kayıt ve giriş işlemlerini güvenli şekilde gerçekleştirebilir

Platform, 6 farklı eğitim başlığına göre yapılandırılmıştır:

- 📡 IoT  
- 🤖 Robotik  
- 🚁 Drone  
- 🚀 Roket  
- 🎨 Tasarım ve Üretim  
- 🎮 Oyun Geliştirme  

> Bu repo: [https://github.com/enesckk/yap_web](https://github.com/enesckk/yap_web)

Mobil uyumlu, kullanıcı dostu ve sade arayüzü ile eğitim ortamını dijital olarak destekler.



## 🎯 Özellikler

Platform; öğrenci, eğitmen ve yöneticiler için aşağıdaki modülleri içerecek şekilde tasarlanmıştır:

1. **🔐 Kayıt ve Giriş Sistemi**
   - Rol (öğrenci/eğitmen) ve sınıf (IoT, Robotik, Drone vb.) seçimiyle kayıt
   - Şifre güvenliği, JWT token doğrulama ve role-based yönlendirme

2. **📢 Duyuru Modülü**
   - Eğitmenler sınıflara özel duyurular paylaşabilir
   - Öğrenciler sadece kendi sınıfına ait duyuruları görür
   - Mobil uyumlu, emoji destekli, tarih formatlı arayüz

3. **✅ Yoklama Sistemi**
   - Öğrenciler yoklamaya katılabilir
   - Eğitmenler katılım durumunu ve geçmişi görebilir
   - Renk kodlu durum göstergeleriyle kullanıcı dostu yapı

4. **📂 Ödev Sistemi**
   - Eğitmenler sınıfa ödev atayabilir
   - Öğrenciler dosya yükleyerek ve yorum ekleyerek teslim yapar
   - Eğitmen ödevleri listeleyip değerlendirebilir

5. **⏳ Mazeret Bildirme**
   - Öğrenciler geçerli nedenlerle dosya ve açıklama yükleyebilir
   - Eğitmenler gelen bildirimleri onaylar/redder
   - Bekleyen, onaylanan, reddedilen şeklinde durum yönetimi

6. **📊 Eğitmen Paneli**
   - Sınıf istatistikleri, öğrenci listesi, son katılım durumu
   - Ödev ve mazeret durumu analizi
   - Filtreleme ve arama özelliği ile yönetim kolaylığı

7. **👤 Profil Sayfası**
   - Kullanıcı bilgilerini görüntüleme
   - Şifre güncelleme
   - Giriş/çıkış ve dashboard yönlendirmeleri

8. **🔔 Bildirim Sistemi**
   - Başarı ve hata mesajları (toast) ile kullanıcı geri bildirimi
   - Oturum durumları, yükleme durumu, işlem sonucu gibi anlık tepkiler

9. **🔐 Güvenlik Özellikleri**
   - Tüm API’lerde token doğrulama ve role-based yetki kontrolü
   - `middleware.ts` ile rota koruması
   - Email formatı ve form validasyonları

10. **📱 Mobil ve UI/UX Odaklı Tasarım**
    - Tailwind CSS ile responsive yapı
    - Emoji ikonları, gradient renk geçişleri ve sade arayüz


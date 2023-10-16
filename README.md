

# Shipment Project 

. Proje Symfony 6.3 sürümü ile geliştirildi.    
. Veritabanı işlemleri için Doctrine ORM kullanıldı.  
. templates/shipment/create.html.twig klasör yapısı kullanıldı.  
. Url üzerinden erişilebilir. Sayfada Ad-Soyad, Telefon, Email, Açıklama ve Ülke bilgisi doldurulabilmesi için alanlar mevcuttur. Bilgiler girildikten sonra arka tarafta ise bu bilgiler alınıp kargo kodu ile birlikte Veritabanına kaydetme işlemi gerçekleşiyor.  
. Kargo kodunun daha önceden varlığı kontrol ediliiyor eğer varsa kaydetme işlemi gerçekleşmiyor. Yoksa benzersiz kod oluşturucu ile kod yaratıldıktan sonra kaydediyor.  
. Form oluşturmada Syfony'nin FormBuilderInterface arayüzü kullanılmıştır.  
. templates/shipment/list.index.html.twig sayfasında oluşturulan kargolar listelenmekte ve Aktif et, Pasif et butonu ile statusu güncelleniyor.
 

 

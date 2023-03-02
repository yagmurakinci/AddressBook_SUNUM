# AddressBook_SUNUM
Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de Kursiyerlik yaptığım süreçte yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

* Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
* Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
* Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
* Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor) Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik. 
* Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor. Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir. Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34 Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .
![adres1](https://user-images.githubusercontent.com/73273677/220844077-6f10af68-c88a-4551-a8c3-d3eda05a8b54.PNG)
![adres2](https://user-images.githubusercontent.com/73273677/220844081-baa697e9-c472-4a94-83ea-d907a5b7d0f8.PNG)
![adres3](https://user-images.githubusercontent.com/73273677/220844089-69714dc8-260b-432a-8fd8-2721f9ee5d06.PNG)
![adresss](https://user-images.githubusercontent.com/73273677/220844195-5430a288-6b79-4808-bb32-69ae4af11809.png)
![adresssss](https://user-images.githubusercontent.com/73273677/220844208-2757bb4f-3d75-4b58-95d8-c95278883f63.png)
![219598418-2f5b06fe-c4fd-4541-9600-7c859a6a1eee](https://user-images.githubusercontent.com/73273677/220844249-b7657ad4-641b-4538-aed9-bffcbfc68ed3.png)
![219598433-ad43bb43-6a4a-4999-937d-844bfa2e9078](https://user-images.githubusercontent.com/73273677/220844277-704e8d8f-6434-427d-bbbd-d58249079b10.png)
![219598450-94cab1d6-5ff4-4623-8f8f-27cb0e1aed8f](https://user-images.githubusercontent.com/73273677/220844292-3f4381ba-808b-4611-8edb-dba4436384ec.png)
![219598457-8ecbbd81-3b1a-4e2d-93a0-15cb5acb3208](https://user-images.githubusercontent.com/73273677/220844312-05c8d771-5365-41d5-8982-836ce801791e.png)

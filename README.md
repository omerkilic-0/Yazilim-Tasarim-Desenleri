# Yazilim-Tasarim-Desenleri

Eğitim kavram haritası mantığında kısa bilgiler vererek devam etmektedir.

# 1. Açık/Kapalı Prensibi

- Arayüzler
- Genişlemeye açık, değişikliğe kapalı.

# 2. Programlama Dili

- Nesne yönetimli programlama kavramları
- Derste kullanılacak programlama dili: Java

# 3. Yazılım Tasarım Desenleri

- Tanım: Sık karşılaşılan nesne yönelimli programlama problemlerinin çözümleridir.
- Hazır sınıflar
- Soyut tanımlar
- Çözümlerin tekrar kullanımı

# 4. Tasarım Deseni Özellikleri

- Adı,
- Sınıfı,
    - Yaratımsal
    - Yapısal
    - Davranışsal
- Amacı,
- Yapı,
- Sonuçları,
- Bilinen kullanımları,
- İlgili Desenler

# 5. Desen Sınıfları

- Yaratımsal
- Yapısal
- Davranışsal

# 6. Desen Kapsamları

- Sınıf
- Nesne

# 7. Yaratımsal

- İlklendirmenin soyutlaştırılması
- Sistemin nesnelerin yaratılmasından bağımsız hale gelmesi
- Sınıf ve Nesne desenleri
- Yaratımsal desenler
    - Sumut sınıf bilgisi
    - Nesnelerin ilklendirimesi gizli
- Ne, kim, nasıl, ne zaman

# 8. Yaratımsal Desenler

- Abstract Factory
- Builder
- Factory Method
- Prototype
- Singleton

# 9. Yapısal

- Kalıtım (İnheritance) yerine bileşim (composition)
- Sınıf ve nesneler ile daha büyük yapıların oluşturulması.

## 9.1 Yapısal Desenler

- Adapter
- Bridge
- Composite
- Decorator
- Façade
- Flyweight
- Proxy

# 10. Davanışsal

- Algoritmaların ve nesneler arası sorumlulukların atanması ile ilgili
- Nesneler arası ilişki

## 10.1 Davranışsal Desenler

- Chain of Responsibility
- Command
- İnterpreter
- Mediator
- Memento
- Observer
- State
- Strategy
- Template
- Visitor

# 11. İterator Deseni

- İterator: Yineyici, tekrarlayıcı
- Diğer bilinen adı: Cursor; imleç
- Amaç: Koleksiyonun aly yapısını teşhir etmeden elemanlarına sıralı erişim sağlamak
- Koleksiyonda farklı şekilde gezinmek mümkün
- Koleksiyona erişim ve gezinme sorumluluğu koleksiyondan iterator’a geçiyor
- Nesne Davranışsal
- Kütüphanelerde iterator kullanımı
- Dikatli kullanım
- Ek iterator yöntemleri

# 12. İlgili Desenler

- Composite
- Factory

# 13. Composite Deseni

- Composite: Bileşim, birçok parçadan oluşan
- Amaç: Bütüne ve bütünün parçalarına aynı şekilde erişim sağlamak
- Nesne yapısal
- Pencere
    - Etiket
    - Metin satır
    - Açılır menü
        - Düğme
        - Metin satırı
- Bileşim içerisindeki tüm nesnelere aynı şekilde davranma

- Ebeveyn referansları,
- Ortak yöntemler,
- Command deseni ile birlikte MacroCommand,
- Decorar ile birlikte sıkça kullanılır,
- İterator ile composite sınıflar gezilebilir.

# 14. Command Deseni

- Command: Komut, emir
- Diğer bilinen adları: Action (Eylem), Transaction (İşlem)
- Amaç: Bir isteği yada komutu nesne olarak tanımlamak
- İstek nesnesi
- Nesne Davranışsal

- Yöntem çağran ve yöntemi yürüten nesneler ayrılıyor
- Komut nesneleri
- Macrocommand
- Genişletilebilir

# 15. State Deseni

- State: Durum, hal
- Amaç: Bir nesnenin iç durumu değişince davranışının da değişmesini sağlamak
- Nesne Davranışsal
- State Değişken
- Finite State Machines, Sonlu Durum Makineleri

- State ve bilgisayar oyunları
- Durum özel davranşlar
- Singleton
- Context ve State

# 16. Factory Method Deseni

- Factory: Fabrika, imalathane, yapımevi, Merhod: Yönyem
- Diğer bilinen adı: Virtual Constructor; sanal yapılandırıcı
- Sınıf Yaratımsal
- Amacı: Bir nesnenin yaratılması için tanımlanan ara yüzün altsınıflarına bu nesnenin hangi sınıftan olacağına karar verme hakkı sağlamak

- Kancalar (Hooks)
- ana sınıf olabilir
- İsimler
- Abstract Factory
- Template
- Prototype

# 17. Abstract Factory Deseni

- Abstract: Soyut, Factory: Fabrika, imalathane, yapımevi…
- Diğer bilinen adı: Kit (Takım Çantası, Alet Takımı)
- Factory Method
- Nesne Yaratımsal
- Amacı: Somut sınıflarını belirtmeden bağlantılı ya da bağımlı olan nesneler grubunu yaratacak bir arayüz sunmak

- Somut sınıfların ayrıştırılması
- Ürün aileleri arasında geçiş
- Yeni ürün desteği zayıf
- Singleton

# 18. Singleton Deseni

- Singleton: Tekil, tekil kalıp
- Nesne yaratımsal
- Amacı: Bir sınıftan yalnızca bir nesnenin olması ve bu nesneye global erişim için bir nokta sağlanması
- Neden?
- Nasıl?
- Tek bir sınıf
- Static İsntance() { return uniquelnstance; }
- Çok iş parçacıklı (multithreaded)
- Static
- Kontrollü erişim
- İsim alanı temizliği
- Birden fazla nesne
- Diğer desenlerle birlikte
    - Abstract Factory
    - Builder
    - Prototype

# 19. Adapter Deseni

- Adapter: Adaptör, uyarlayan
- Bilinen diğer adı: Wrapper, sarmalayan, saran
- Amacı: Bir sınıfın arayüzünü, istemcilerini beklediği arayüze dönüştürmek
- Hem sınıf hemde nesne yapısal

# 20. Observer Deseni

- Observer: Gözlemci, izleyici
- Bilinen diğer adları:
    - Dependents: Bağımlılar
    - Publish-Subscribe: Yayında-Abone ol
- Nesne Davranışsal
- Amacı: Nesneler arasında birden-çok’ a (one-to-many) bağımlılık tanımıyla ve bir nesne durum değiştirildiğinde bağımlı olanların otomatik güncellmemsini sağlamak
- Birden fazka subject
- Güncelleme
- Silinen nesneler

# 21. Proxy Deseni

- Proxy: Vekil
- Bilinen diğer adları: Surrogate
- Nesne Yapısal
- Amacı: Bir nesneye erişimi kontrol etmek için o nesneye bir vekil nesne sağlamak.
- Uzak vekil
- Sanal vekil
- Koruyucu vekil
- Akıllı referans

# 22. yazar:
**Ömer Kılıç**

# 23. Yayınlanma Tarihi:
**25.02.2023**

# 24. Yazar İletişim/Bilgi/Özgeçmiş:
**http://omerkilic.rf.gd/**

# 1. Giriş: Yazılım Tasarım Desenleri Nedir?

Yazılım tasarım desenleri, yazılım mühendisliğinde tekrarlanabilir çözüm şablonlarıdır. Bu şablonlar, belirli bir sorunu çözmek veya belirli bir görevi yerine getirmek için birlikte çalışan bileşenlerin tasarımını belirler. Tasarım desenleri, yazılımın daha etkili, sürdürülebilir, değiştirilebilir ve genişletilebilir olmasını sağlar.

Tasarım desenleri, yazılımın nesne yönelimli programlama (OOP) ve başka birçok yazılım tasarımı paradigmasıyla birlikte kullanılabilir. Tasarım desenleri, belirli bir tasarım problemine yönelik en iyi çözümü bulmak için kullanılır ve tasarım kalıpları olarak adlandırılır.

Yazılım tasarım desenleri, yazılım mühendisliğinde önemli bir rol oynar. Aşağıdaki nedenlerden dolayı yazılım tasarım desenleri önemlidir:

**1. Kod yeniden kullanımı:** Yazılım tasarım desenleri, kodun yeniden kullanılabilirliğini artırır. Bu, daha az kod yazmak, daha hızlı ve daha verimli bir geliştirme süreci sağlar.

**2. Kodun sürdürülebilirliği:** Tasarım desenleri, kodun daha sürdürülebilir olmasını sağlar. Bu, kodun daha az hatalı olmasını, daha kolay bakım yapılmasını ve değiştirilmesini sağlar.

**3. Kodun değiştirilebilirliği:** Tasarım desenleri, kodun daha değiştirilebilir olmasını sağlar. Bu, gereksinimlerin ve iş gereksinimlerinin değişmesi durumunda daha az çabayla değişiklik yapılmasını sağlar.

**4. Kodun genişletilebilirliği:** Tasarım desenleri, kodun daha genişletilebilir olmasını sağlar. Bu, kodun gelecekteki ihtiyaçlara göre kolayca genişletilebilmesini sağlar.

Bu nedenlerden dolayı, yazılım tasarım desenleri, yazılım mühendisliğinde önemli bir araçtır ve yazılım geliştirme sürecinde dikkate alınması gereken bir faktördür.

# 2. Yazılım Tasarım Desenleri Türleri

## 1. Creational Design Patterns (Yaratıcı Tasarım Desenleri)

## 2. Structural Design Patterns (Yapısal Tasarım Desenleri)

## 3. Behavioral Design Patterns (Davranışsal Tasarım Desenleri)

İşte bu üç tür yazılım tasarım deseni hakkında daha detaylı bilgi:

**1. Creational Design Patterns (Yaratıcı Tasarım Desenleri):** Bu desenler, nesnelerin oluşturulmasını ve örneklenmesini yönetmek için kullanılır. Bu tür desenler, nesnelerin yaratılmasının karmaşık olduğu durumlarda kullanışlıdır. Bu tür tasarım desenleri, Singleton, Factory Method, Abstract Factory, Builder, Prototype gibi isimlerle örneklenebilir.

- Singleton, yalnızca bir örneğe sahip olan bir nesne oluşturmak için kullanılır.
- Factory Method, bir sınıftan nesne oluşturma sürecini yönetmek için kullanılır.
- Abstract Factory, nesne ailesi oluşturmak için kullanılır.
- Builder, kompleks nesnelerin oluşturulmasını kolaylaştırmak için kullanılır.
- Prototype, var olan bir nesnenin kopyasının oluşturulması için kullanılır.

**2. Structural Design Patterns (Yapısal Tasarım Desenleri):** Bu desenler, nesnelerin birbirleriyle nasıl ilişkilendirileceğini ve bir arada nasıl çalışacağını belirlemek için kullanılır. Bu tür desenler, birbirleriyle uyumlu olan nesnelerin tasarımı için kullanışlıdır. Bu tür tasarım desenleri, Adapter, Bridge, Composite, Decorator, Facade, Flyweight ve Proxy gibi isimlerle örneklenebilir.

- Adapter, bir sınıfın arabirimi üzerinde çalışabilmesi için başka bir arabirime dönüştürülmesini sağlar.
- Bridge, nesne arayüzünü ve uygulamasını ayrı ayrı tasarlamak için kullanılır.
- Composite, nesneleri hiyerarşik bir şekilde gruplamak için kullanılır.
- Decorator, nesnelere dinamik olarak özellikler eklemek için kullanılır.
- Facade, karmaşık bir sistemin bir yüzeyini basitleştirmek için kullanılır.
- Flyweight, hafıza kullanımını azaltmak için nesnelerin paylaşılmasını sağlar.
- Proxy, gerçek bir nesnenin yerine geçen bir nesne oluşturmak için kullanılır.

**3. Behavioral Design Patterns (Davranışsal Tasarım Desenleri):** Bu desenler, nesnelerin nasıl etkileşim kuracağını ve birbirleriyle nasıl çalışacağını belirlemek için kullanılır. Bu tür desenler, nesnelerin davranışlarını yönetmek için kullanılır. Bu tür tasarım desenleri, Chain of Responsibility, Command, Interpreter, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, ve Visitor gibi isimlerle örneklenebilir.

- Chain of Responsibility, bir dizi işlemin birbirini takip eden bir zincirinde işlenmesi için kullanılır.

# 3. Yaratıcı Tasarım Desenleri

## 1.Singleton Deseni

Bu desen, yalnızca bir tane örneği olan bir sınıf oluşturmak için kullanılır. Bu desen, bir nesnenin yalnızca bir kez oluşturulmasını sağlamak istediğimiz durumlarda kullanışlıdır. Bu desen, özellikle hafızayı boşa harcamak istemediğimiz veya birden fazla örnek kullanmanın doğru olmadığı durumlarda kullanışlıdır. Singleton deseninde, örnekleme işlemi statik bir yöntemle gerçekleştirilir ve sınıfın tek örneği statik bir değişkende saklanır.

## 2.Factory Method Deseni

Bu desen, bir sınıftan nesne oluşturma sürecini yönetmek için kullanılır. Bu desen, nesne oluşturma işlemini alt sınıflara devreder ve böylece nesne yaratma işleminin sınıf yapısından bağımsız olmasını sağlar. Bu desen, alt sınıfların farklı nesne türlerinin oluşturulmasını yönettiği durumlarda kullanışlıdır.

## 3.Abstract Factory Deseni

Bu desen, nesne ailesi oluşturmak için kullanılır. Bu desen, birbiriyle ilişkili nesnelerin bir arada kullanılması gereken durumlarda kullanışlıdır. Örneğin, bir uygulama geliştirirken, kullanıcı arayüzü bileşenleri, veri kaynağı bağlantısı, veri erişim nesneleri ve benzeri birçok nesne türü oluşturmanız gerekebilir. Bu desen, bu nesneleri oluşturmanın bir yolunu sağlar ve nesne ailesi içindeki nesnelerin birbirleriyle uyumlu olduğundan emin olur.


## 4.Builder Deseni

Bu desen, kompleks nesnelerin oluşturulmasını kolaylaştırmak için kullanılır. Bu desen, nesnenin yapısını oluşturma sürecini ayrı ayrı yönetmek için kullanılır. Bu desen, nesne oluşturma sürecinin adımlarını basitleştirir ve bir nesnenin oluşturulması sırasında ortaya çıkabilecek karmaşıklığı azaltır.

## 5.Prototype Deseni

u desen, var olan bir nesnenin kopyasının oluşturulması için kullanılır. Bu desen, nesne oluşturma işlemini basitleştirir ve bir nesnenin birebir kopyasını oluşturmanın kolay bir yolunu sağlar. Bu desen, nesne oluşturma sürecinin maliyetini düşürür ve daha hızlı nesne oluşturma sağlar.

# 4. Yapısal Tasarım Desenleri

## 1. Adapter Deseni

Bu desen, iki farklı arayüzü birbirine bağlamak için kullanılır. Bir arayüzdeki bir sınıfın diğer bir arayüzle uyumlu hale getirilmesini sağlar. Bu desen, mevcut bir kodun yeniden kullanılmasını sağlar.

## 2. Bridge Deseni

Bu desen, soyutlama ve uygulama arasındaki bağımlılığı azaltmak için kullanılır. Bu desen, bir sınıfın uygulama ayrıntılarından ayrılmak için soyutlama katmanı oluşturur. Bu desen, farklı platformlar arasında geçiş yapmanın gerektiği durumlarda kullanışlıdır.

## 3. Composite Deseni

Bu desen, ağaç benzeri yapıları temsil etmek için kullanılır. Bu desen, hiyerarşik bir yapıda nesneleri gruplandırmak ve bu nesneleri tek bir nesne olarak yönetmek için kullanılır. Bu desen, birden fazla nesnenin bir arada yönetilmesi gerektiği durumlarda kullanışlıdır.

## 4. Decorator Deseni

Bu desen, nesnelere yeni davranışlar eklemek için kullanılır. Bu desen, bir nesnenin davranışını değiştirmek istediğimiz durumlarda kullanılır. Bu desen, bir nesnenin davranışını değiştirerek yeni özellikler ekleyebilir veya mevcut özellikleri değiştirebilir.

## 5. Facade Deseni

Bu desen, karmaşık bir sistemdeki alt sistemleri birleştirmek için kullanılır. Bu desen, sistem bileşenlerinin karmaşıklığını gizleyerek, kullanıcıların sistemi daha kolay kullanmalarını sağlar. Bu desen, bir sistemin dışındaki kullanıcıların içindeki sistem hakkında bilgi sahibi olmalarını önler.

## 6. Flyweight Deseni

Bu desen, benzer nesnelerin ortak özelliklerini paylaşarak hafıza kullanımını azaltmak için kullanılır. Bu desen, çok sayıda nesne oluşturmanın maliyetini azaltır ve bellek kullanımını optimize eder.

## 7. Proxy Deseni

Bu desen, bir nesne üzerindeki erişimi kontrol etmek için kullanılır. Bu desen, nesneye erişimi kontrol etmek istediğimiz durumlarda kullanışlıdır. Bu desen, nesneye erişim kontrolünün yanı sıra nesne üzerindeki işlemleri izlemek veya kaydetmek için de kullanılabilir.

# 5. Davranışsal Tasarım Desenleri

**1. Chain of Responsibility Deseni:** Bu desen, bir işlemi sırayla bir dizi nesne üzerinden geçirerek her nesnenin işlemi gerçekleştirmesine izin verir. Bu desen, işlemi farklı şekillerde işleyen nesneler arasında işlem zincirleri oluşturmak için kullanılır.

**2. Command Deseni:** Bu desen, bir istemci isteğini nesne yöntemleri olarak paketleyerek ve isteği bir sınıfın nesnesi olarak kullanarak işlemi gerçekleştirir. Bu desen, istemci ve gerçekleştiricinin birbirinden bağımsız çalışmasını sağlar.

**3. Interpreter Deseni:** Bu desen, belirli bir dilde yazılmış ifadeleri yorumlamak için kullanılır. Bu desen, yorumlanması gereken bir dildeki ifadelere bir arayüz sağlar ve bu ifadeleri yorumlamak için bir yorumlayıcı oluşturur.

**4. Iterator Deseni:** Bu desen, bir koleksiyonda gezinmek için kullanılır. Bu desen, bir koleksiyonun elemanlarını döngü kullanarak gezinmek yerine, bir dizi metot sağlayarak koleksiyondan elemanları getirmek için kullanılır.

**5. Mediator Deseni:** Bu desen, nesneler arasındaki iletişimi kontrol etmek için kullanılır. Bu desen, bir nesne üzerindeki değişikliklerin diğer nesnelere etkisini kontrol etmek ve nesneler arasındaki etkileşimi azaltmak için kullanılır.

**6. Memento Deseni:** Bu desen, bir nesnenin önceki durumunu kaydetmek ve geri yüklemek için kullanılır. Bu desen, bir nesnenin durumunu değiştirmeden önce önceki durumunu kaydederek, istenildiğinde önceki duruma geri dönebilir.

**7. Observer Deseni:** Bu desen, bir nesnenin durumunda değişiklik olduğunda diğer nesnelere bildirim göndermek için kullanılır. Bu desen, bir nesne üzerindeki değişikliklerin diğer nesneler tarafından takip edilmesini ve değişikliklerin otomatik olarak güncellenmesini sağlar.

**8. State Deseni:** Bu desen, bir nesnenin durumuna bağlı olarak davranışını değiştirmek için kullanılır. Bu desen, bir nesnenin farklı durumlarına sahip olmasını ve durumuna bağlı olarak farklı davranışlar sergilemesini sağlar.

**9. Strategy Deseni:** Bu desen, benzer amaçları olan farklı algoritmaların kullanımını kolaylaştırmak için kullanılır. 

**10. Template Method Deseni:** Bu desen, bir süreci yürütmek için bir şablon sağlar ve bu şablonun belli noktalarında alt sınıflar tarafından belirlenen özelleştirme noktalarını kullanır. Bu desen, bir işlemi yapmak için farklı adımların birleştirilmesi gerektiğinde kullanılır.

Örneğin, bir veritabanına bağlanmak ve veri almak için bir şablon oluşturulabilir. Bu şablonun belli noktalarında, örneğin veritabanı türü veya sorgu özellikleri gibi, alt sınıflar tarafından belirlenen özelleştirme noktaları kullanılabilir.

**11. Visitor Deseni:** Bu desen, bir nesne yapısındaki nesneleri ziyaret etmek ve her bir nesne üzerinde belirli işlemleri gerçekleştirmek için kullanılır. Bu desen, nesne yapısının değişmesi gerektiğinde işlemlerin değiştirilmesi yerine, yeni bir ziyaretçi eklenerek işlemlerin değiştirilmesini sağlar.

Örneğin, bir HTML belgesi ağacındaki nesneleri ziyaret ederek her bir nesne için farklı işlemler yapmak isteyebilirsiniz. Bu durumda, her bir HTML nesnesi için ayrı bir ziyaretçi sınıfı oluşturabilir ve bu ziyaretçi sınıfları, nesne yapısının değişmesi gerektiğinde kolayca değiştirilebilir.

# 6. Tasarım Desenlerinin Uygulanması

Tasarım desenleri, yazılım geliştirme sürecinde bir problemle karşılaşıldığında, bu problemi çözmek için oluşturulmuş tekrar kullanılabilir çözümlerdir. Tasarım desenlerinin uygulanması, bir yazılım projesinin başından sonuna kadar değişebilir.

Tasarım desenleri genellikle, yazılım projesinin tasarım ve kodlama aşamalarında kullanılır. Tasarım desenleri, bir proje için bir çerçeve veya temel oluşturabilir ve proje geliştirme sürecinde tekrar tekrar kullanılabilir.

Tasarım desenlerinin uygulanması, öncelikle tasarım desenlerini anlamak ve belirli bir problemi çözmek için hangi tasarım deseninin uygun olduğunu belirlemekle başlar. Daha sonra, uygun tasarım deseni seçilir ve bu desenin uygulanması için bir plan hazırlanır.

## Tasarım desenlerinin uygulanması, aşağıdaki adımları içerebilir:

**1. Tasarım deseninin seçimi:** Öncelikle, kullanılacak tasarım deseninin belirlenmesi gerekmektedir. Bu, projenin gereksinimlerine ve problemine bağlı olarak belirlenir.

**2. Tasarım deseni uygulama planının hazırlanması:** Tasarım deseni uygulama planı hazırlanır ve projede kullanılacak sınıflar, arayüzler, yöntemler vb. belirlenir.

**3. Tasarım deseni uygulama kodunun yazılması:** Tasarım desenine uygun kod yazılır ve tasarım deseni uygulanır.

**4. Test etme:** Tasarım deseni uygulaması test edilir ve gerekli değişiklikler yapılır.

Tasarım desenleri, farklı yazılım geliştirme örneklerinde kullanılabilir. Örneğin, bir Singleton deseni, bir uygulamada yalnızca bir örnek oluşturmak için kullanılabilir. Factory Method deseni, bir nesnenin oluşturulması için kullanılabilir. Composite deseni, bir nesne yapısının hiyerarşik bir şekilde oluşturulması için kullanılabilir.

Bir diğer örnek olarak, bir web uygulaması geliştirirken, Facade deseni kullanarak, web uygulamasının farklı bileşenleri arasında iletişimi kolaylaştırabilirsiniz. Visitor deseni, bir HTML belgesindeki nesneleri ziyaret ederek her bir nesne için farklı işlemler yapmak için kullanılabilir. Özetle, tasarım desenleri, yazılım geliştirme sürecinde birçok farklı problemi çözmek için kullanılabilir.

# 7. Yazılım Tasarım Desenleri Ne Kadar Önemlidir?

Sonuç olarak, yazılım tasarım desenleri, yazılım geliştirme sürecinde karşılaşılan sorunları çözmek ve daha iyi, ölçeklenebilir, bakımı kolay, anlaşılır ve değiştirilebilir yazılımlar üretmek için kullanılan güçlü araçlardır. Tasarım desenleri, yazılımın farklı bölümleri arasındaki etkileşimleri daha anlaşılır hale getirir ve yeniden kullanılabilir bileşenler sağlar. Ayrıca, kod kalitesini artırır, hataları azaltır ve zaman ve maliyet tasarrufu sağlar.

Tasarım desenlerinin uygulanması, öncelikle sorunu tanımlamak, desenin kullanım amacını belirlemek ve ardından uygun desenleri seçmekle başlar. Daha sonra desenleri uygulamak, kodlamak ve test etmek gerekmektedir. Desenlerin doğru bir şekilde uygulanması, yazılımın genel performansını ve bakımını kolaylaştırır.

Yazılım geliştirme örnekleri olarak, bir web uygulaması geliştirirken, bir Singleton deseni kullanarak veritabanı bağlantı nesnesinin yalnızca bir kez oluşturulmasını sağlayabilirsiniz. Bir Builder deseni kullanarak, bir karmaşık nesnenin oluşturulmasını kolaylaştırabilirsiniz. Bir Decorator deseni kullanarak, bir nesne üzerinde çalışan özellikleri dinamik olarak değiştirebilirsiniz. Bir Observer deseni kullanarak, bir nesnenin durumu değiştiğinde bağımlı nesnelere bildirim gönderebilirsiniz.

Tasarım desenleri, yazılım geliştirme sürecinde oldukça önemlidir ve gelecekteki etkileri daha da artacak gibi görünmektedir. Yapay zeka ve nesnelerin interneti gibi teknolojilerin gelişmesi ile birlikte, daha ölçeklenebilir ve yeniden kullanılabilir yazılımlara olan ihtiyaç artacaktır. Bu nedenle, tasarım desenleri, yazılım geliştirme sürecinde vazgeçilmez bir araç olarak kalmaya devam edecektir.

# 8. Yazar

**Ömer Kılıç**

# 9. Yayınlanma Tarihi:

**24.02.2023**

# 10. Yazar İletişim/Bilgi/Özgeçmiş:

**http://omerkilic.rf.gd/**

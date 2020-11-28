# 5.Hafta Ödevi

## Lazy Loading kavramı hakkında temel bir araştırma yapınız.

   Lazy Loading, sayfa yükleme zamanında kritik olmayan kaynakların yüklenmesini erteleyen bir tekniktir. Bunun yerine, kritik olmayan bu kaynaklar ihtiyaç anında yüklenir. Avantajları ise;

- Zaman tüketimini ve bellek kullanımını azaltarak içerik dağıtımını optimize eder. Önce gerekli olan web sayfasının sadece bir kısmı yüklendiğinden, geçen süre daha az olur ve bölümün geri kalanının yüklenmesi gecikir, bu da depolamadan tasarruf sağlar.
- Gereksiz kod yürütmeden kaçınılır.

## SQLite ve LocalDB kavramlarını karşılaştırınız.

   SQLite, düşük bellekli ortamlarda bile taşınabilirliği, güvenilirliği ve güçlü performansı ile bilinen bağımsız, dosya tabanlı ve tamamen açık kaynaklı bir İlişkisel Veri Tabanı Yönetim Sistemi (RDBMS)'dir.

   Çoğu ilişkisel veritabanı motoru, programların istekleri aktaran bir işlemler arası iletişim aracılığıyla ana sunucu ile iletişim kurduğu bir sunucu işlemi olarak uygulanır. SQLite ile, veritabanına erişen herhangi bir işlem doğrudan veritabanı disk dosyasından okur ve ona yazar. Bu, bir sunucu sürecini yapılandırma ihtiyacını ortadan kaldırdığı için SQLite'ın kurulum sürecini basitleştirir. Aynı şekilde, SQLite veritabanını kullanacak programlar için herhangi bir yapılandırma gerekmez: tek ihtiyaçları olan diske erişimdir.

   LocalDB, ihtiyaç duyulduğunda otomatik olarak açılabilen ve kullanılmadığında kapatılabilen, SQL Server motorunun geliştirici odaklı, isteğe bağlı yönetilen bir örneğidir. Çalıştırmak için hiçbir yapılandırma gerektirmez ve tam bir SQL Server örneğini yönetme ve yükleme ek yükü olmadan bir veritabanı motoruna hızlı erişim sağlar. LocalDB, tüm bunları başarmak için gereken minimum miktarda dosya kullanır. Veritabanı erişiminin yerel kalması, bir SQL Server arka uç ile uygulama geliştirme ve test etme karmaşıklığını büyük ölçüde azaltır.


[Karşılaştırma](https://www.diericx.net/post/benchmark-embedded-dotnet-databases/)

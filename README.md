# Harezm
## Veri Paylaşım Taahüdü

Projemiz kapsamında toplanan tüm veriler, sadece araç üzerindeki sensörler aracılığıyla gerçek zamanlı olarak elde edilmektedir. Bu veriler; nesne tanıma, yol takibi, çevresel haritalama, konum takibi, sesli komut algılama ve sistem hata analizleri gibi amaçlarla kullanılmaktadır.

### Veri Türleri ve Kullanımı
- **Görüntü Verisi:** Araç üstü kameradan JPEG/MP4 formatında alınır, nesne tanıma ve yol takibi için kullanılır.
- **LIDAR Verisi:** LIDAR sensöründen alınan point cloud verisi, mesafe ölçümü ve haritalama amacıyla işlenir.
- **GPS Verisi:** GPS modülünden JSON formatında toplanır ve konum takibi için değerlendirilir.
- **Ses Verisi:** Ses sensör kartından MP3/WAV formatında elde edilir, sesli komut algılama için kullanılır.
- **Sistem Logları:** Yerel bilgisayarda tutulan log dosyaları, hata ayıklama ve test analizleri için kullanılır.

### Veri Saklama ve Güvenlik
Toplanan veriler öncelikle yerel araç içi bilgisayarda kısa vadeli geçici olarak depolanmakta, önemli ve gerekli veriler merkezi bilgisayara aktarılmakta ve uzun vadeli olarak saklanmaktadır. Tüm veriler, proje ekibi tarafından erişilebilir olup, güvenlik tedbirleri kapsamında korunmaktadır. Haftalık yedekleme işlemleri harici SSD’lerde güvenli şekilde gerçekleştirilmektedir.

### Veri Paylaşımı ve Gizlilik
Projede toplanan veriler **kişisel veri içermemekte** olup, sadece proje içi test, analiz ve model eğitimi amacıyla kullanılmaktadır. Bu veriler dış üçüncü taraflarla paylaşılmayacak ve başka amaçlarla kullanılmayacaktır.

### Etik ve Yasal Uyum
Veri toplama, işleme ve saklama süreçleri, yürürlükteki veri koruma mevzuatlarına ve etik standartlara tam uyumlu olarak yürütülmektedir. Proje süresince kişisel veri toplanmayacak, yalnızca çevresel ve sistem verileri şeffaf ve sorumlu bir şekilde yönetilecektir.

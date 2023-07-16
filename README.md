# Ritim. Bu kod Google Collabs ortamında çalışır.

Ritim Soru Üretimi için Ritmik Hücre Bankaları ve Yönergeler
Önbilgiler Ölçü sayısı: 2 Zaman İşareti seçenekleri: 4/4 Örnek:

Kullanıcı kod içinde 3 zorluk derecesini (1,2 ve ara zorluk 1.5) seçecek. Opsiyon olarak ta üçlükler (opsiyon-1, triplet) ya da dörtlük ve sekizlikler seçşlecek (opsyion-2, dörtlük ve sekizlikler)

Yönergeler İki kademe ve üç seviyeden biri seçildikten sonra, bu seviyenin içinde yer alan ritmik hücreler seçkisiz (random) kullanılarak ritimler üretilecektir. Burada dikkat edilecek hususlar; • Kullanılan ritmik hücre sayısı Ölçü Sayısı X Ölçü Zamanı kadar olmalıdır. • Aynı ritmik hücre ardarda en fazla 3 kez kullanılabilir. • Seçilen hücrelerdeki vuruş sayıları (Q) toplanacaktır (Total Q). • 9 < Total Q < 15 • Kullanılacak ilk hücrede 1.bölünüm dolu olmalıdır; Örneğin Level 1-B bankası seçildiğinde kullanılacak ilk ritmik hücre S2 olamaz çünkü bu hücrede ilk vuruş 3.bölünümde yer almaktadır. Örnek#1 Ritmik Hücreler 8 kere kullanılacaktır Seviye 1-B bankasından rastgele üretelim; • S1 – S4 – S3 – S6 – S5 – S2 – S5 – S4;

Total Q = 20,
Total Q > 15 tekrar rastgele üretelim; • S1 – S6- S2 – S3 – S2 – S4 – S1 – S1

Total Q = 14 Output 

Kullanıcı kod içinde seviye (1/2) ve opsiyon (1/2) parametrelerini değiştirerek bu tablolar ile ritmleri hesaplar.
Mixed alternatifinde ise ilk 4 ölçü seviye-1, kalan 4 ölçü ile seviye-2'den alınır.

Otomatik Ritim Üreticisi Prof.Dr. Barış Bozkurt'un (İzmir Demokrasi Üniversitesi) yürütücülüğünde gerçekleştirilen 121E198 no'lu "Çevrimiçi müzik eğitiminde kullanılma amaçlı öğrenci müzik egzersiz icrası otomatik notlandırma sistemi tasarımı" başlıklı Tübitak 1001 projesi kapsamında, kuralları Doç. Dr. Ozan Baysal (İstanbul Teknik Üniversitesi) tarafından tasarlanmış, Yavuz Buruk (İstanbul Teknik Üniversitesi) tarafından kodu geliştirmiştir.


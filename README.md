# Ritmiyum. Bu kod Google Collabs ortamında çalışır.
Ritim Soru Üretimi için Ritmik Hücre Bankaları ve Yönergeler
Önbilgiler Ölçü sayısı: 2 Zaman İşareti seçenekleri: 4/4 Örnek:

Kullanıcı kod içinde 3 zorluk derecesini (1,2 ve ara zorluk 1.5) seçecek. Opsiyon olarak ta üçlükler (opsiyon-1, triplet) ya da dörtlük ve sekizlikler seçşlecek (opsyion-2, dörtlük ve sekizlikler)

Yönergeler İki kademe ve üç seviyeden biri seçildikten sonra, bu seviyenin içinde yer alan ritmik hücreler seçkisiz (random) kullanılarak ritimler üretilecektir. Burada dikkat edilecek hususlar; • Kullanılan ritmik hücre sayısı Ölçü Sayısı X Ölçü Zamanı kadar olmalıdır. • Aynı ritmik hücre ardarda en fazla 3 kez kullanılabilir. • Seçilen hücrelerdeki vuruş sayıları (Q) toplanacaktır (Total Q). • 9 < Total Q < 15 • Kullanılacak ilk hücrede 1.bölünüm dolu olmalıdır; Örneğin Level 1-B bankası seçildiğinde kullanılacak ilk ritmik hücre S2 olamaz çünkü bu hücrede ilk vuruş 3.bölünümde yer almaktadır. Örnek#1 Ritmik Hücreler 8 kere kullanılacaktır Seviye 1-B bankasından rastgele üretelim; • S1 – S4 – S3 – S6 – S5 – S2 – S5 – S4;

Total Q = 20,
Total Q > 15 tekrar rastgele üretelim; • S1 – S6- S2 – S3 – S2 – S4 – S1 – S1

Total Q = 14 Output 
![image](https://github.com/yavuzburuk/rhythmium/assets/47657147/f23cd408-609f-4eec-b89d-3634da89c786)
![image](https://github.com/yavuzburuk/rhythmium/assets/47657147/485a1378-a067-4bbb-92ad-387282465762)
![image](https://github.com/yavuzburuk/rhythmium/assets/47657147/e83921bf-e761-472e-93d3-d10defd2a2c4)
![image](https://github.com/yavuzburuk/rhythmium/assets/47657147/7d956b89-ef2b-43db-9f95-5205205b52cf)


Kullanıcı kod içinde seviye (1/2) ve opsiyon (1/2) parametrelerini değiştirerek bu tablolar ile ritmleri hesaplar.
Mixed alternatifinde ise ilk 4 ölçü seviye-1, kalan 4 ölçü ile seviye-2'den alınır

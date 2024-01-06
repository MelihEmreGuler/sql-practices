**A. Aşağıda belirtilen özelliklerdeki tabloları oluşturunuz.**

1.  Tablo adı : OGRENCILER

    a.  ogrno : 100'den itibaren 1'er artan sayı

    b.  ograd : Max 5 karakterlik metin bilgisi

    c.  ogrsoyad : Max 15 karakterlik metin bilgisi

    d.  veliadsoyad : Max 20 karakterlik metin bilgisi

    e.  adres : Max 50 karakterlik metin bilgisi

    f.  sınıf : (10/11/12 A,B,C değerleri girilebilir. Örn: 10A, 12C...
        vb.)

    g.  dogumtar : Doğum tarihi bilgisi (zaman kısmı olmasın)

    h.  alan : FEN/TM/SOS değerlerinden biri girilebilir

2.  Tablo adı : URUNLER

    a.  urunno : 1'den itibaren 1'er 1'er artan sayı

    b.  urunad : Max 15 karakterlik metin bilgisi

    c.  uruntanım : Max 50 karakterlik ürün tanımı

    d.  maliyetfiyat : Üretim maliyeti parasal büyüklüğü

    e.  karoran : karoranı (%5 ile %25 arası)

    f.  KDV : kdv oranı (%3 ile %25 arası)

    g.  kolisekli : ADET/KG/DESTE/LITRE/SERI

3.  Tablo adı: ARABALAR

    a.  aracno :O/R/F harflerinden biri ile başlayan ve toplam 4
        karakterlik uzunluğa sahip, birincil anahtar (R100, F281..)

    b.  marka : OPEL, RENAULT, FORD değerlerinden biri

    c.  model : Max 10 karakterlik metin bilgisi

    d.  trafikyil : 2000 ile 2009 arası yıl bilgisi, default "2009"

    e.  renk : max 10 karakterlik metin bilgisi

    f.  yakit : BENZIN, DIZEL, LPG, KARMA değerlerinden biri

    g.  kilo : Aracların kilo değeri

**B. Yukarıda oluşturulmuş olan tablolar ile ilgili aşağıda belirtilen
yapısal değişiklik işlemlerini yapınız.**

1.  OGRENCILER tablosuna "kangurup" alanını ekleyiniz. (A+, A-, B+, B-,
    AB+, AB-, O+, O-)

2.  OGRENCILER tablosundaki "ograd" alanının uzunluğunu 15 karakterlik
    hale getiriniz.

3.  OGRENCILER tablosuna "dogumyer" alanını ekleyiniz.

4.  URUNLER tablosundaki "uruntanım" alanının uzunluğunu 40 karakterlik
    hale getiriniz.

5.  URUNLER tablosundaki "kolisekli" alanını siliniz.

6.  URUNLER tablosuna "renk" ve "kilo" alanlarını ekleyiniz. (kilo\>0
    olmalı)

7.  URUNLER tablosundaki "kilo" alanını siliniz.

8.  ARABALAR tablosundaki "aracno" alanına "H" seçeneği de girilebilir
    hale getiriniz.

9.  ARABALAR tablosundaki "marka" alanına "HYUNDAI" seçeneğini de
    ekleyiniz.

10. ARABALAR tablosundaki kilo alanını siliniz.

**C. Yukarıda oluşturulmuş olan tablolara kayıt girişi ile ilgili
aşağıda belirtilen işlemleri yapınız.**

1.  OGRENCILER tablosuna 3 adet tam dolu kayıt girişi yapınız. (Ayrı
    insert'ler ile ve tek insert ile)

2.  OGRENCILER tablosuna yeni 2 tam dolu kayıt girişi yapınız. (Her
    seferinde herhangi 2 alana "null" ataması yaparak)

3.  URUNLER tablosuna 3 adet tam dolu kayıt girişi yapınız.

4.  URUNLER tablosuna yeni 2 tam dolu kayıt girişi yapınız. (Her
    seferinde herhangi 2 alana "null" ataması yaparak)

5.  ARABALAR tablosuna 3 adet tam dolu kayıt girişi yapınız.

6.  ARABALAR tablosuna yeni 2 tam dolu kayıt girişi yapınız. (Her
    seferinde herhangi 2 alana "null" ataması yaparak)

7.  OGRENCILER tablosuna sadece "ograd" alanına veri girişi yapınız.

8.  OGRENCILER tablosunda sadece "ograd" ve "dogumtar" alanlarına veri
    girişi yapınız.

9.  URUNLER tablosuna urunad'ı olarak "kalem" , kolisekli olarak "GRAM"
    girişi yapınız.

10. URUNLER tablosuna urunno olarak "48", urunad olarak "SANDALYE"
    girişi yapınız.

11. ARABALAR tablosuna sadece "marka" ve "model" alanlarına veri girişi
    yapınız.

**D. Yukarıda oluşturulmuş olan tablolara girilmiş olan verilere göre
aşağıdaki sorgulama işlemlerini yapınız.**

1.  OGRENCILER tablosundaki tüm verileri listeleyiniz.

2.  OGRENCILER tablosundaki 11B sınıfındaki öğrencilerin ad ve
    numaralarını listeleyiniz.

3.  OGRENCILER tablosundaki dogumyer'i "BOLU" olan öğrencileri
    listeleyiniz.

4.  OGRENCILER tablosundaki 11. sınıf öğrencilerinin bilgilerini
    listeleyiniz.

5.  OGRENCILER tablosundaki adı 5 harfli öğrencilerin adlarını ve
    sınıflarını listeleyiniz.

6.  OGRENCILER tablosundaki 12. sınıf öğrencilerinden FEN alanındaki
    öğrencilerin bilgilerini listeleyiniz.

**E. Northwind veritabanı ile ilgili aşağıda belirtilen sorguları
yapınız.**

1.  PRODUCTS tablosundan productname alanındaki verileri listeleyen
    sorguyu yapınız.

2.  PRODUCTS tablosundan ProductID, ProductName, UnitPrice alanlarındkai
    verileri listeleyen sorguyu yapınız.

3.  PRODUCTS tablosundaki tüm alanları ve tüm verileri listeleyen
    sorguyu yapınız.

4.  PRODUCTS tablosundaki Productname alanındaki verileri, Productname
    alanına göre artan şekilde sıralayarak listeleyen sorguyu yapınız.

5.  PRODUCTS tablosundaki ProductName, UnitPrice alanlarındaki verileri
    önce Unitprice sonra Productname alanlarına göre artan şekilde
    sıralayarak listeleyen sorguyu yapınız.

6.  PRODUCTS tablosundaki ProductID, ProductName, UnitPrice
    alanlarındaki verileri ProductName, UnitPrice alanlarına göre artan
    şekilde sıralama yapan sorguyu, sıralama bloğunu rakamsal olarak
    yazarak yapınız.

7.  PRODUCTS tablosundaki ProductID, UnitPrice, ProductName
    alanlarındaki verileri Unitprice alanına göre azalan şekilde
    sıralayarak yapan sorguyu yapınız.

8.  PRODUCTS tablosundaki ProductID, UnitPrice, ProductName
    alanlarındaki verileri Unitprice alanına göre azalan, Productname
    alanına göre artan şekilde sıralayan sorguyu yapınız.

9.  PRODUCTS tablosundaki Unitprice değeri 2,5 olan kayıtların
    ProductName, UnitPrice alanlarındaki verileri listeleyen sorguyu
    yapınız.

10. PRODUCTS tablosundaki Unitprice değeri 5'den küçük olan kayıtların
    ProductName, UnitPrice alanlarındaki verileri listeleyen sorguyu
    yapınız.

11. PRODUCTS tablosundaki Unitprice değeri 10 ve üzerinde olan
    kayıtların ProductName, UnitPrice alanlarındaki verileri listeleyen
    sorguyu yapınız.

12. PRODUCTS tablosundaki SupplierID değeri 4 haricinde olan kayıtların
    SupplierID, ProductName alanlarındaki kayıtları listeleyen sorguyu
    yapınız.

13. PRODUCTS tablosundaki kayıtlardan Productname alanı "Chang"
    haricinde olan kayıtların Productname alanındaki verileri listeleyen
    sorguyu yapınız.

14. PRODUCTS tablosundaki kayıtlardan Unitprice alanındaki değeri 10 ile
    20 arasındaki kayıtların ProductName, UnitPrice alanlarındaki
    verileri listeleyen sorguyu yapınız. (10 ve 20 dahil)

15. PRODUCTS tablosundaki kayıtlardan Productname alanındaki değerleri
    "Chang" ve "LongLife Tofu" arasındaki kayıtların Productname ve
    Unitprice alanlarındaki verileri listeleyen sorguyu yapınız.
    ("Chang" ve "LongLife Tofu" dahil )

16. PRODUCTS tablosundaki kayıtlardan SupplierID değeri 8 ve Unitprice
    değeri 40'dan küçük olan kayıtların SupplierID, ProductName,
    UnitPrice alanlarındaki verileri listeleyen sorguyu yapınız.

17. PRODUCTS tablosundaki kayıtlardan SupplierID değeri 8 veya 10 olan
    kayıtların SupplierID, ProductName, UnitPrice alanlarıdaki verileri
    listeleyen sorguyu yapınız.

18. PRODUCTS tablosundaki kayıtlardan SupplierID değeri 8 veya 10 ve
    Unitprice değeri 20 ve üzerinde olan kayıtların SupplierID,
    ProductName, UnitPrice alanlarındaki verileri listeleyen sorguyu
    yapınız.

19. PRODUCTS tablosundaki kayıtlardan SupplierID değer 8 veya 10 olan
    kayıtların SupplierID, ProductName, UnitPrice alanlarındaki verileri
    Productname alanına göre artan şekilde sıralayarak listeleyen
    sorguyu yapınız.

20. PRODUCTS tablosundaki kayıtlardan SupplierID değeri 8 olmayan
    kayıtların SupplierID, ProductName alanlarındaki verileri listeleyen
    sorguyu yapınız.

21. PRODUCTS tablosundaki kayıtlardan Productname'i "R" harfi ile
    başlayan kayıtların Productname alanındaki verileri listeleyen
    sorguyu yapınız.

22. PRODUCTS tablosundaki kayıtlardan Productname'in içerisinde "chef"
    geçen kayıtların Productname alanındaki verileri listeleyen sorguyu
    yapınız.

23. PRODUCTS tablosundaki kayıtlardan Productname'i "S" harfi ile
    başlayıp "s" harfi ile başlayan kayıtların Productname alanındaki
    verileri listeleyen sorguyu yapınız.

24. PRODUCTS tablosundaki kayıtlardan Productname alanında 4 karakterli
    veri bulunan ve ilk 3 karakteri "Tof" olan kayıtların Productname
    alanındaki verileri listeleyen sorguyu yapınız.

25. PRODUCTS tablosundaki kayıtlardan Productname alanında 5 karakterli
    veri bulunan ve 2. karakterden itibaren "kur" verisi olan kayıtların
    Productname alanındaki verileri listeleyen sorguyu yapınız.

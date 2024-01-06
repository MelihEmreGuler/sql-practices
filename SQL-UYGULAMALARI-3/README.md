  ------------------------------------------------------------------------------------------------------
  **Yayınevleri**         **Kitaplar**         **Satışlar**         **Müşteriler**           **İller**
  ----------------- ----- -------------- ----- -------------- ----- ---------------- ------- -----------
  Yayınevi No             Kitap No             Satno                Müşteri No               İlkodu

  Yayınevi Adı            Kitap Adı            Tarih                Ad                       İl adı

  Yetkili                 Yazar Adı            Müşterino            Soyad                    

  İlkodu                  Birim Fiyat          Kitapno              Tel                      

  Tel                     Basım Yılı           Adet                 İlkodu                   

  webadresi               Kategori                                                           

                          Yayınevi No                                                        
  ------------------------------------------------------------------------------------------------------

1.  Yukarıdaki tabloları gerekli veri türleri, birincil/yabancı
    anahtarlar, silme/güncelleme işlemlerinin gerekli yerleri de
    etkilemesi ve aşağıda belirtilen kısıtlamalara ve özelliklere göre
    *[oluşturan]{.underline}* SQL ifadelerini yazınız.

    a.  Tel alanındaki örnek yapı kontrolü (380-5142789)

    b.  Web adresindeki örnek yapı kontrolü (www.pusula.com)

    c.  Birim fiyatın negatif olamaması kontrolü

    d.  Kitap ve yazar adlarının ve müşteri ad/soyadlarının harflerden
        oluşması kontrolü

    e.  İl kodu alanının pozitif sayılardan oluşması

    f.  Tarih alanındaki verilerin sistem tarihinden büyük olamaması,
        boş geçilirse sistem tarihinin yazılması

    g.  Kategori alanına sadece "Programlama, Grafik-Tasarım, Network,
        Genel, Veritabanı" verilerinin girilebilmesi

    h.  Adet alanının negatif olamaması kontrolü

2.  Oluşturulan her tabloya parçalı ve tam dolu *[kayıt
    girişlerini]{.underline}* yapan SQL ifadelerini yazınız. (Tekli ve
    çoklu kayıt girişleri kullanarak)

    a.  4 tane yayınevi kaydı girişi

    b.  7 tane kitap kaydı girişi

    c.  10 tane satış kaydı girişi

    d.  5 tane il kaydı girişi

    e.  3 tane müşteri kaydı girişi

3.  Girilmiş olan kayıtlar üzerinde aşağıdaki
    *[güncellemeleri]{.underline}* yapan SQL ifadelerini yazınız.

    a.  Soyadı boş bırakılmış olan müşterilerin soyad'larına 'UNKNOWN'
        yazdırılması

    b.  Yayınevi adlarının ilk harfi büyük, diğer harfleri küçük olacak
        şekilde yazdırılması

    c.  Kitap isimlerinin tüm harfleri büyük olacak şekilde yazdırılması

    d.  "Com" uzantılı olan web sayfası adreslerinin "org" uzantılı hale
        çevrilmesi

    e.  İsmi 5 harfli ve içinde "Ş" harfi geçen kayıtların silinmesi

4.  Girilmiş olan kayıtlar üzerinde aşağıda belirtilen
    *[silme]{.underline}* işlemlerini yapan SQL ifadelerini yazınız.

    a.  İsmi 5 harfli ve içinde "Ş" harfi geçen kayıtların silinmesi

    b.  Kars ilinden olan müşterilerin silinmesi

    c.  "C#" kitabını almış olan Ankara'lı müşterilere dair kayıtların
        satışlar tablosundan silinmesi

    d.  Belirteceğiniz kişinin, yetkili kişisi olduğu yayınevine ait
        olan kitaplara ait satış kayıtlarının silinmesi

5.  Girilmiş olan kayıtlara göre, aşağıda istenilen
    *[listeleme]{.underline}* işlemlerini yapan SQL ifadelerini yapınız.
    (Çoklu tablo kullanımı gereken şıkları önce "alt sorgular"
    kullanarak, sonra da "Join" çeşitlerinden uygun olanları kullanarak
    yapınız.)

    a.  Kendi seçeceğiniz bir "kitap adına" ait satış kayıtlarını
        listeleyin

    b.  Kendi seçeceğiniz bir "müşteri adına" dair satış kayıtlarını
        listeleyin

    c.  Kendi seçeceğiniz bir "kitab adını" almış olan müşteri
        isimlerini listeleyin

    d.  Kendi seçeceğiniz bir yayınevi adına ait olan kitapları almış
        olan müşterilerin adlarını listeleyin

    e.  Birim fiyatı, belirteceğiniz rakamdan daha fazla olan kitaplara
        ait kaç satış kaydı olduğunu listeleyin

    f.  Ankara'lı müşterilerin, kaç tane "Programlama" kitabı aldığını
        listeleyin

    g.  Hiç kitabı satılmayan yayınevi varsa, adını listeleyin

6.  Aşağıdaki işlemleri yapacak olan stored procedure(sp)'leri yazınız.

    a.  Müşteriler tablosundaki tüm kayıtları listeleyen sp

    b.  Girilen kitap adının satış kayıtlarını listeleyen sp

    c.  Adı girilen yayınevi'nin toplam kaç adet kitabı satıldığını
        veren sp

    d.  Adı girilen yayınevinin tüm kitaplarının birim fiyatlarına %10
        zam yapan sp

    e.  Hiç satışı olmayan kitapların birim fiyatlarına %20 indirim
        yapan sp

    f.  En çok satılmış olan kitabın adı ve yayınevi adını listeleyen sp

    g.  En çok alışveriş yapmış olan müşterinin ismin ekranda listeleyen
        sp

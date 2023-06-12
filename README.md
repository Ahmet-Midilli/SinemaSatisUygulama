# Sinema Satış Uygulaması
Müşteriden alınan ürünler (mısır,su,çay,bilet) yan tarafında fiyat tablosu (mısır,su,cola,bilet)
onlarında yanında kasa , toplam fiyat ve hesapla butonu olucak.
## Uygulamanın Geliştirileceği Yer.
Windows Form.
## Uygulama Anlatımı
Uygulamamız bir sinema şirketinin film öncesi insanların vakit geçirebileceği bir cafenin satışını yapacağı 4 ürünün (Çay,Mısır,Su,Bilet) sisteme adet fiyat olarak kayıt edilmesini sağlayacak.Müşteriler siparişi verecek isim soyisim kayıt edilip sırayla teslim edilecek.

## Uygulama Yapım Aşamaları
* 1.aşamada groupBox1(ürün miktar) imizi adetlerin gireceği kısım olarak ayarladık

![adet bölümü](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/656fbf23-4ee9-4d48-a4a5-648c0a52a37e)

Burada

kutucukları 

 * textbox 1 : mısır
 * textbox 2 : su
 * textbox 3 : çay
 * textbox 4 : bilet

 2.aşamada groupBox2'mizi etiket olarak kullanacağız kasayı burada ki fiyatlara göre hesaplayacağız.

![Fiyat Tablosu](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/b3286db7-3671-402b-9ff4-3ed525bb0b86)

3.aşamada groupBox3'ümüzü ise kasa olarak kullanacağız.müşterinin ödeyeceği total tutarı burada göreceğiz.

![kasa](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/4f5d5cb5-98cc-4929-a250-6eea254e6661)

* Ürünlerin adet bilgisini öğrenmek için kullandığım kod dizini ;

![adet hesaplama](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/c3174fa7-07c1-4d43-acf7-638a961da993)

* Müşterilerin aldığı ürünlerin toplam TL değerinden karşılığını veren kod dizini ; 

![toplam hesaplama](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/1c76cc60-e0f4-45f0-b05c-be39a6430b52)

* Gün için verilen tüm siparişleri ortak bir kasada karşılığını gösteren kod dizinim ; 
* 
![total kasa hesaplama](https://github.com/Ahmet-Midilli/SinemaSatisUygulama/assets/104301620/c6d1557f-b544-4993-a3bc-70a1180190c1)

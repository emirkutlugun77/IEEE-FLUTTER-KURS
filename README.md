# IEEE-FLUTTER-KURS





# KURS ÖNCESİ HAZIRLIK

## Yüklemeler
https://flutter.dev/docs/get-started/install

Kurumları yapmak için Git yüklemeniz şart değil ama oldukça işinize yarar
###### IOS

https://flutter.dev/docs/get-started/install/macos

###### WINDOWS

https://flutter.dev/docs/get-started/install/windows

###### EDİTÖR
Tercih Sizin Ama Eğitimde VS Code Kullanılacak 

VS Code;

https://flutter.dev/docs/get-started/editor?tab=vscode

Andorid Studio;

https://flutter.dev/docs/get-started/editor?tab=androidstudio

###### EMULATOR
https://flutter.dev/docs/get-started/install/windows#set-up-the-android-emulator

## Faydalı İçerikler
Flutter Nedir;

https://www.youtube.com/watch?v=I9ceqw5Ny-4 & https://www.youtube.com/watch?v=fq4N0hgOWzU

Flutter yapısını daha iyi anlamanız için;

https://www.youtube.com/watch?v=O2YE9IYwCoc

###### Flutter Ekibinin dökümanları

Widget Kataloğu;

https://flutter.dev/docs/development/ui/widgets

Orijinal Dökümantasyon;

https://flutter.dev/docs






# HAFTA 1

Mobil uygulamaların çalışma prensibinden ve yapısından bahsedildi.

## İşlenen Konular

### Stateful&Stateless Widget
  
  Flutter’da neredeyse her şey widget’tır ve widget dediğimiz kavram bize hazır olarak verilmiş bileşenlerdir. Her bir arayüz elemanı gibi birçok yapı birer widget olarak geçer. Flutter’ın widget özelliklerine ve örneklerine bakmak için widget kataloğunu inceleyebilirsiniz. Bu widgetları kullanarak kolay ve hızlı bir şekilde uygulamamızı geliştirebiliriz. Yeri geliyor, widget içinde widget kullanıyoruz. Bunun için widget yapısını kavramak önem taşıyor. Her bir yapının aslında birer widget olduğunu ve bu widgetların özelliklerini bilmeliyiz.

İç içe yazacağımız widgetlar demişken, örnek verebiliriz. Bazı widgetlar, içine sadece bir widget kabul ederken; bazı widgetlar içine birden çok widget kabul edebiliyor. Bunu da şöyle düşünebiliriz. Flutter’da, Column diye bir widget vardır ki ilerleyen derslerde sayfa yapıları olarak bunu da ayrıntılı işleyeceğiz, birden çok widget alabilir. Çünkü Column widgetını, alt alta hizalanan bir liste gibi düşünebiliriz. Böylece aslında birden fazla eleman alabileceğini anlayabiliriz kolaylıkla. Fakat Container widgetını ise kutu gibi düşünüyoruz ve buna ise sadece bir eleman ekleyebiliyoruz.

 

Temel widget yapılarıTemel widget yapıları
 
State nedir?

State, oluşturduğumuz uygulamanın durumu olarak tanımlanabilir. Ekranın anlık görüntüsüdür. Bir ekranın görüntüsünü yani State’i etkileyen birçok widget vardır. Örnek vermek gerekirse: yazılar, resimler yine en basit örnekleridir. State değiştiğinde, ekrandaki görüntü de değişir. O yüzden, kullandığımız widgetlara göre state seçimini doğru kulanmak önemlidir.

Stateless ve Stateful Widget farkıStateless ve Stateful Widget farkı
Stateful ve Stateless Widget farkı nedir?

Uygulamamızı Stateful veya Stateless widget sınıflarıyla oluşturuyoruz. Bu sınıflar da birer widgettır. Fakat neye göre Stateless veya Stateful widget sınıfı oluşturuyoruz, bu biraz kafa karıştırabiliyor. Şimdi sırayla incelediğimizde aslında çok kolay olduğunu beraber görebiliriz.

Öncelikle anlamlarına bakarak ip ucu yakalayabiliriz.

Stateless = Durumsuz,   Stateful = Durumsal 

Eğer, kullanacağımız ekranda değişen herhangi bir yapımız yoksa bunu Stateless widget kullanarak oluştururuz. Sabit yapılarla, durumsuz bir haldir. Yani değişen bir şey yoktur. Örnek olarak, koyacağımız bir başlık yazısı gibi değişmeyen widgetlarla, stateless widget kullanırız.

Eğer, kullanacağımız ekranda widgetlarda değişiklik olacaksa bunu Stateful widget kullanarak oluştururuz. Değişken yapılarla, durumsal bir haldir yani belirli durumlara sahiptir. Örnek olarak, ekranda bir saat göstermek istersek veya sayaçlı bir sistem gibi sürekli değişen değerlerde, stateful widget kullanırız.

### Scaffold Widget'ı
  
  Uygulamanın çalışması için gerekli en önemli "Widget" olduğunu gösterdik. Dökümantasyon aşağıda.
  
https://api.flutter.dev/flutter/material/Scaffold-class.html

### App Bar Widget'ı
  
  Uygulamanın üstünde bulunan bar. Dökümantasyon aşağıda.
  
https://api.flutter.dev/flutter/material/AppBar-class.html

### Row ve Column

Row ve Column bizim sayfamızdaki ögeleri istediğimiz yerde konumlandırmak için kullandığımız temel widgetlardır.


Row;
https://api.flutter.dev/flutter/widgets/Row-class.html
Column;
https://api.flutter.dev/flutter/widgets/Column-class.html

## ÖDEV 1

MaterialApp ve Container widgetlarını incelemek.

## ÖDEV 2 I AM RICH UYGULAMASI

Bu uygulama App Store ve Google Play Store'da yaklaşık 10 yıl önce yayınlandı, uygulama sadece ana ekranda bir elmas resminden oluşuyordu, ve satış fiyatı 799 dolardı, kısa bir süre sonra mağazalardan kaldırılan bu uygulamayı 8 kişi satın almıştı ve yaratıcı yaklaşık 5600 dolar kazandı, uygulamanın amacı ise insanlara ne kadar zengin olduğunuzu göstermekti, sizden de beklentim bu uygulamanın aynısını yapmamız. Bu uygulamayı yapmak için biraz araştırma yapmanızı istiyorum gerekli dökümantasyonları aşağıda paylaşıyorum, uygulamayı yaptıktan sonra uygulamanın bir ekran görüntüsünü emirkutlugun01@gmail.com adresine göndermenizi istiyorum.

### Uygulamamıza resim eklemek için;

https://docs.flutter.dev/development/ui/assets-and-images

### Pubspec.yaml dosyası hakkında daha fazla bilgi için;

https://dart.dev/tools/pub/pubspec

Görsel olarak istediğiniz herhangi bir görseli kullanabilirsiniz.

## Örnek Ekran Görüntüsü

[![image](https://www.linkpicture.com/q/Ekran-Resmi-2021-12-21-19.46.27.png)](https://www.linkpicture.com/view.php?img=LPic61c205a58f6ae376357779)


## Kaynak Kod (Lütfen uygulamayı kendiniz yapmayı denedikten sonra bakın)

https://github.com/kreativecoder/i_am_rich

  

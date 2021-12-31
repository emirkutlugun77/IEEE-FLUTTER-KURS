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

# FLUTTER HAFTA 2 İŞLENEN KONULAR
## Layout alıştırmaları & miCard Uygulaması

## Row & Column Alıştırmaları

 [Basic Flutter layout concepts | Flutter](https://docs.flutter.dev/codelabs/layout-basics)

## MiCard
[GitHub - londonappbrewery/MiCard-Completed: The completed code for the MiCard Project - The Complete Flutter Development Bootcamp](https://github.com/londonappbrewery/MiCard-Completed)




# HAFTA 2 ÖDEV (4 KİŞİLİK GRUPLAR)
## Hesap Makinesi Yapımı
Gerekenler

1. 0-9 aralığında sayılar ve + - * / =  ve C, DEL butonları
2. Matematiksel işlemleri yapmak için fonksiyonlar ( Fonksiyon parametre almalı ve basılan butondaki sayı değerini işleme koymalı)
3. Stateful Widget kullanmalıyız çünkü ekranda göreceğimiz sonuç değişkeni her işlemde değişecek ve bunu kullanıcıya göstermek için setState komutunu çağırmamız gerekecek
4. Her buton için ayrı bir Widget oluşturmak mantıklı olmadığı için kendi buton Widgetımızı oluşturup ona parametreler vermeliyiz(https://www.raywenderlich.com/10126984-creating-reusable-custom-widgets-in-flutter)


# Simple Calculator App using Flutter

* Difficulty Level : [Easy](https://www.geeksforgeeks.org/easy/)
* Last Updated : 04 Oct, 2021

Flutter SDK is an open-source software development kit for building beautiful UI which is natively compiled. In this article we will build a Simple Calculator App that can perform basic arithmetic operations like addition, subtraction, multiplication or division depending upon the user input. Making this app will give you a good revision of flutter and dart basics. Concepts covered are:

* Showing Widgets on the screen.
* Gridview.builder
* Function writing
* If and else in dart

Follow the below steps to implement the simple calculator. Let’s get started.

Want a more fast-paced & competitive environment to learn the fundamentals of Android?
[Click here](https://practice.geeksforgeeks.org/courses/fundamentals-android-dev?utm_source=GeeksforGeeks&amp;utm_medium=Text&amp;utm_campaign=GFG_Article_Bottom_Text_Android) to head to a guide uniquely curated by our experts with the aim to make you industry ready in no time!

#### Step 1: Creating a Flutter App

Open the Terminal /Command-prompt. Change Directory to your choice and run **flutter create calculatorApp.** Open the calculatorApp in VS Code or Android Studio.

![](&&&SFLOCALFILEPATH&&&create.jpg)

#### Step 2: Coding Calculator App

In the Lib folder, there is a main.dart file already present. And now in the same folder create a new file named **buttons.dart.** Starting with **main.dart** file. Create **MyApp** class and make it **StatelessWidget**. Add an array of buttons to be displayed. Set the background-color, text-color, functionality **onTapped** to the buttons. Write a function to calculate the Answers

* Dart

## Dart 
 
```

`import` `'package:flutter/material.dart'` `;`
`import` `'buttons.dart'` `;`
`import` `'package:math_expressions/math_expressions.dart'` `;`

`void` `main() {`
 `runApp(MyApp());`
`}`

`class` `MyApp extends StatelessWidget {`
 `@override`
 `Widget build(BuildContext context) {`
 `return` `MaterialApp(`
 `debugShowCheckedModeBanner:` `false` `,`
 `home: HomePage(),`
 `);` `// MaterialApp`
 `}`
`}`

`class` `HomePage extends StatefulWidget {`
 `@override`
 `_HomePageState createState() => _HomePageState();`
`}`

`class` `_HomePageState extends State<HomePage> {`
 `var userInput =` `''` `;`
 `var answer =` `''` `;`

 `// Array of button`
 `final List<String> buttons = [`
 `'C'` `,`
 `'+/-'` `,`
 `'%'` `,`
 `'DEL'` `,`
 `'7'` `,`
 `'8'` `,`
 `'9'` `,`
 `'/'` `,`
 `'4'` `,`
 `'5'` `,`
 `'6'` `,`
 `'x'` `,`
 `'1'` `,`
 `'2'` `,`
 `'3'` `,`
 `'-'` `,`
 `'0'` `,`
 `'.'` `,`
 `'='` `,`
 `'+'` `,`
 `];`

 `@override`
 `Widget build(BuildContext context) {`
 `return` `Scaffold(`
 `appBar:` `new` `AppBar(`
 `title:` `new` `Text(` `"Calculator"` `),`
 `),` `//AppBar`
 `backgroundColor: Colors.white38,`
 `body: Column(`
 `children: <Widget>[`
 `Expanded(`
 `child: Container(`
 `child: Column(`
 `mainAxisAlignment: MainAxisAlignment.spaceEvenly,`
 `children: <Widget>[`
 `Container(`
 `padding: EdgeInsets.all(20),`
 `alignment: Alignment.centerRight,`
 `child: Text(`
 `userInput,`
 `style: TextStyle(fontSize: 18, color: Colors.white),`
 `),`
 `),`
 `Container(`
 `padding: EdgeInsets.all(15),`
 `alignment: Alignment.centerRight,`
 `child: Text(`
 `answer,`
 `style: TextStyle(`
 `fontSize: 30,`
 `color: Colors.white,`
 `fontWeight: FontWeight.bold),`
 `),`
 `)`
 `]),`
 `),`
 `),`
 `Expanded(`
 `flex: 3,`
 `child: Container(`
 `child: GridView.builder(`
 `itemCount: buttons.length,`
 `gridDelegate: SliverGridDelegateWithFixedCrossAxisCount(`
 `crossAxisCount: 4),`
 `itemBuilder: (BuildContext context,` `int` `index) {`
 `// Clear Button`
 `if` `(index == 0) {`
 `return` `MyButton(`
 `buttontapped: () {`
 `setState(() {`
 `userInput =` `''` `;`
 `answer =` `'0'` `;`
 `});`
 `},`
 `buttonText: buttons[index],`
 `color: Colors.blue[50],`
 `textColor: Colors.black,`
 `);`
 `}`

 `// +/- button`
 `else` `if` `(index == 1) {`
 `return` `MyButton(`
 `buttonText: buttons[index],`
 `color: Colors.blue[50],`
 `textColor: Colors.black,`
 `);`
 `}`
 `// % Button`
 `else` `if` `(index == 2) {`
 `return` `MyButton(`
 `buttontapped: () {`
 `setState(() {`
 `userInput += buttons[index];`
 `});`
 `},`
 `buttonText: buttons[index],`
 `color: Colors.blue[50],`
 `textColor: Colors.black,`
 `);`
 `}`
 `// Delete Button`
 `else` `if` `(index == 3) {`
 `return` `MyButton(`
 `buttontapped: () {`
 `setState(() {`
 `userInput =`
 `userInput.substring(0, userInput.length - 1);`
 `});`
 `},`
 `buttonText: buttons[index],`
 `color: Colors.blue[50],`
 `textColor: Colors.black,`
 `);`
 `}`
 `// Equal_to Button`
 `else` `if` `(index == 18) {`
 `return` `MyButton(`
 `buttontapped: () {`
 `setState(() {`
 `equalPressed();`
 `});`
 `},`
 `buttonText: buttons[index],`
 `color: Colors.orange[700],`
 `textColor: Colors.white,`
 `);`
 `}`

 `//  other buttons`
 `else` `{`
 `return` `MyButton(`
 `buttontapped: () {`
 `setState(() {`
 `userInput += buttons[index];`
 `});`
 `},`
 `buttonText: buttons[index],`
 `color: isOperator(buttons[index])`
 `? Colors.blueAccent`
 `: Colors.white,`
 `textColor: isOperator(buttons[index])`
 `? Colors.white`
 `: Colors.black,`
 `);`
 `}`
 `}),` `// GridView.builder`
 `),`
 `),`
 `],`
 `),`
 `);`
 `}`

 `bool` `isOperator(String x) {`
 `if` `(x ==` `'/'` `|| x ==` `'x'` `|| x ==` `'-'` `|| x ==` `'+'` `|| x ==` `'='` `) {`
 `return` `true` `;`
 `}`
 `return` `false` `;`
 `}`

`// function to calculate the input operation`
 `void` `equalPressed() {`
 `String finaluserinput = userInput;`
 `finaluserinput = userInput.replaceAll(` `'x'` `,` `'*'` `);`

 `Parser p = Parser();`
 `Expression` `exp` `= p.parse(finaluserinput);`
 `ContextModel cm = ContextModel();`
 `double` `eval =` `exp` `.evaluate(EvaluationType.REAL, cm);`
 `answer = eval.toString();`
 `}`
`}`
```

 

 

In Flutter main.dart file is the entry point from which the code starts to executing. In the main.dart file firstly material design package has been imported in addition to _math_expressions_ and _buttons.dart file_. Then a function _runApp_ has been created with parameter as _MyApp_. After the declaration of class _MyApp_ which is a stateless widget, the state of class _MyApp_ has been laid out.  

#### Step 3: Building the b *uttons.dart*

In _buttons.dart_ which is already imported in main.dart file we are declaring variables that will be used throughout the program using a constructor. The color, text color, button text, and the functionality of the button on tapped will be implemented in _main.dart file_  

* Dart

## Dart

 
 
 

 

 
 
 

`import` `'package:flutter/material.dart'` `;`

`// creating Stateless Widget for buttons`
`class` `MyButton extends StatelessWidget {`
  
 `// declaring variables`
 `final color;`
 `final textColor;`
 `final String buttonText;`
 `final buttontapped;`

 `//Constructor`
 `MyButton({` `this` `.color,` `this` `.textColor,` `this` `.buttonText,` `this` `.buttontapped});`

 `@override`
 `Widget build(BuildContext context) {`
 `return` `GestureDetector(`
 `onTap: buttontapped,`
 `child: Padding(`
 `padding:` `const` `EdgeInsets.all(0.2),`
 `child: ClipRRect(`
 `// borderRadius: BorderRadius.circular(25),`
 `child: Container(`
 `color: color,`
 `child: Center(`
 `child: Text(`
 `buttonText,`
 `style: TextStyle(`
 `color: textColor,`
 `fontSize: 25,`
 `fontWeight: FontWeight.bold,`
 `),`
 `),`
 `),`
 `),`
 `),`
 `),`
 `);`
 `}`
`}`

 

 

#### Step 4: Adding dependencies in pubspec.yaml file

To make the process easier we are using **math_expressions: ^2.0.0**  package which is imported in main.dart file to handle all the calculations and run time error exceptions. 

![](&&&SFLOCALFILEPATH&&&dependency-660x212.jpg)
Adding math_expressions : ^2.0.0 dependency

**Output:**  

Video Player [https://media.geeksforgeeks.org/wp-content/uploads/20201214170908/calculator.mp4](https://media.geeksforgeeks.org/wp-content/uploads/20201214170908/calculator.mp4)


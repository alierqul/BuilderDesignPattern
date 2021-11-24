# MenuBuilderDesignPattern

## Builder Design Pattern
Builder Design Pattern Yapısını kavramak ve console Uygulamaları için her zaman kullanabileceğimiz bir Menu Şablonunu tasarlamasıdır. Biraz Android studioda kullanılan notification builder a benzetmeye çalıştım. 

![consoleImg](https://github.com/alierqul/BuilderDesignPattern/raw/master/img/MenuBuilder.PNG)

	new MenuBuilder.Builder()
		.title("Menu başlık")
		.body("2021 by @alierqul")
		.addMenu(1, "Menu 1")
		.addMenu(2, "Menu 2")
		.foother("alt bilgi")
		.build().show();

Builder kavramı genel olarak içerisinde 5 den fazla opsiyonel özelliği olan sınıfları düzenli bir syntax yapısı içerisinde oluşturmamızı sağlayan bir tasarımdır. Constructor içerisinde birinci değişken neydi ikinci değişken hangi değeri alıyordu düşünmeden Ctrl+space ile tüm opsiyonel seçenekleri IDE yardımı ile rahatça görüp atamalarımızı yapabiliriz.
# Lisans
[MIT](https://choosealicense.com/licenses/mit/)

Приложение для преобразования текста в DataMatrix код 

Написано на языке C# с использованием библиотеки ZXing и фреймворка Xamarin.Android 

Xamarin.Android позволяет создавать приложения для мобильных устройств на платформе Android посредством использования языка C# 

  

Работа программы с точки зрения пользователя выглядит следующим образом: 

1. Вход в приложение 

2. Ввод текста 

3. Нажатие кнопки Convert для преобразования 

4. Отображение DataMatrix кода в виде изображения 

  

Работа программы с точки зрения разработчика выглядит следующим образом: 

В файле MainActivity описаны основные методы работы. В методе OnCreate происходит инициализация полей, а также подписка на событие от нажатия на кнопку. 

Метод ButtonClick предназначен для обработки нажатия на кнопку. Здесь вызывается метод MakeDataMatrix, который нужен для преобразования строки в DataMatrix код, а также вызывается метод IsValidISO, который проверяет, валидна ли строка согласно кодировке. 

В файле ActivityMain.xml описано отображение экрана 
## **Дипломный проект профессии «Инженер по тестированию»**

**Описание**

Автоматизация тестирования мобильного приложения "Мобильный хоспис".

Приложение предоставляет функционал по работе с претензиями хосписа и включает в себя:

1. Информацию о претензиях и функционал для работы с ними.
2. Новостную сводку хосписа.
3. Тематические цитаты.

### **Предварительные условия:**
**1.** Установить и открыть Android Studio 
      
Установочный файл: [по ссылке](https://developer.android.com/studio)

Инструкция по установке: [по ссылке](https://github.com/netology-code/guides/blob/master/android/android_studio/instruction1.md)

**2.** Склонировать репозиторий

   [ https://github.com/BekkerV8/Diplom   ](https://github.com/BekkerV8/Diplom)  

### **Инструкция по запуску**
 
**3.**  Открыть проект fmh-android в Android Studio.

**4.** Запустить эмулятор (API 29) или подключить устройство для тестирования.

**5.** Запустить тесты консольной командой `./gradlew connectedAndroidTest`.

### **Инструкция по запуску (с выгрузкой Allure-results)**

**1.** Открыть проект fmh-android в Android Studio.

**2.** Запустить эмулятор (API 29) или подключить устройство для тестирования.

**3.** Во вкладке Project левым кликом мыши (или аналогичным образом) выделить каталог app.

**4.** Запустить тесты сочетанием клавиш Shift+Ctl+R (Mac) или Shift+Ctrl+F10 (Windows). Если не получается, то во вкладке Run нажать Run all tests.

**5.** По завершению, выгрузить каталог /data/data/ru.iteco.fmhandroid/files/allure-results с эмулятора или тестового устройства (при помощи Device Manager). Лучше выгрузить в корень директории проекта.

**6.** Выполните локально консольную команду allure serve, находясь на уровень выше каталога allure-results.


### **Документация**

[План автоматизации тестирования](https://github.com/BekkerV8/Diplom/blob/master/Plan.md)

[Чек-лист](https://docs.google.com/spreadsheets/d/1Z753d42u6yaoEJ8OsW5gKqcFm4auGYG6bg61_7h17Kc/edit#gid=0)

[Тест-кейсы](https://docs.google.com/spreadsheets/d/14xJCC-7HeyT0kMnIz_qMir1u4qIOURAWST0dJohcpXM/edit#gid=0)

[Отчёт о проведённом тестировании](https://github.com/BekkerV8/Diplom/blob/master/Result.md)

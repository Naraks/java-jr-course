# Unit 4 Обобщения (Generic) и их применение в некоторых коллекциях.


## Кратко об обощениях
### Что это такое
Обобщения параметризованные классы, вы инициализируйте параметры классов уже при его применении.

### Основная цель создания
Цель работа с коллекциями, чтобы ошибки находились на этапе компиляции.   
В целом позволяет не писать несколько реализаций одного и того же кода для разных типов данных.  

### Материалы для изучения
Хорнстман 207-229

## Optional
Одним из ярких применений обобщений является класс Optional, позволяющий избежать множества ошибок по работе с null.  
[Oracle docs](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)

## Упражнения
### Duel
Создайте обобщенный класс Duel, который можно проинициализировать 2 противниками.  
Напишите его методы: 
* битва до поражения одного из противников, возвращающий победителя в cхватке.  
* Метод возвращающий более здорового противника,   
* Метод возвращающий более сильного противника.   
* Метод возвращающий более защищенного противника.   
* Параметры должны наследовать базовый интерфейс.   

### Weapon *
Спроектируйте общий интерфейс для оружия.   
Подумайте как его применить для класса Warrior.


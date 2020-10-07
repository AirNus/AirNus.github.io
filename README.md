# [ИДБ-17-05](https://github.com/stankin/design-part-1/wiki/list-idb-17-05) Мазитов Айнур

# Лабораторная 1

Предложение: Заварить чай

![none](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/01_A0.png?raw=true)

Предложение: Бариста Заваривает Чай по Заказу из Кипятка и Чайных листьев с помощью Чайника.

## Class diagram
[Текст](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/PlantUML_code%20%E2%80%94%20laba1ClassD.txt) и
[рисунок](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/JSwn2i903CRnkVSKePE2J-1Kprbq41mbt8Ksz7efkIiTn7StfOlhnvzVqfMAMfSfkJ9odb5nWf2m5FYuncCOUvKbnwiaKNWDNCar5rLPzyKdIomKZQJ_qzVjIkjHsMwqW0KUXiAJS9RgRZZImGidplrxnKfwWlkc7CzROi30aI2mXaIkenpjoHy0.png?raw=true) диаграммы классов
 
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/JSwn2i903CRnkVSKePE2J-1Kprbq41mbt8Ksz7efkIiTn7StfOlhnvzVqfMAMfSfkJ9odb5nWf2m5FYuncCOUvKbnwiaKNWDNCar5rLPzyKdIomKZQJ_qzVjIkjHsMwqW0KUXiAJS9RgRZZImGidplrxnKfwWlkc7CzROi30aI2mXaIkenpjoHy0.png?raw=true)

## Usecase diagram
 [Текст](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/PlantUML_code%20%E2%80%94%20laba1UseCase.txt) и
 [рисунок](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/Lab1_2_2.png?raw=true) диаграммы прецедентов
 
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Labs1/Lab1_2_2.png?raw=true)

# Лабораторная 2

## IDEF0 diagram

Контекстная:

![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/01_A0.png?raw=true)

### На диаграмме изображен процесс работы кофейни

Средний уровень:
    
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/02_A0.png?raw=true)

### A1 Менеджер получает на вход отзывы клиентов и подтверждение выполнения заказа от мойщика. А на выходе получаются новые заказы и деньги.
### А2 Мойщик получает заказ в виде инструкции а на вход получает ресурсы и посуду. Исходя из заказа готовит ингредиенты(чайные листья) и посуду(чайник) на выход.
### А3 Бариста получает заказ в виде инструкции и ресурсы полученные от мойщика. Готовит по рецепту заказа и выдает заказ посетителю.
### А4 Посетитель получает свой заказ(чай). Оставляет отзыв и грязную посуду.

## DFD-диаграмма (блок:Управлять):
    
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/03_A1.png?raw=true)

### Менеджер получает отзывы в виде шкалы оценок (1-5 звезд) и заносит их в базу данных через форму редактирования заказа.

## DFD-диаграмма (блок:Подготовить):
    
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/04_A2.png?raw=true)

### Мойщик получает веб форму с данными по заказу, подтверждает получение и готовит необходимые ингредиенты.

## Usecase diagram
 [Текст](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/PlantUML_code%20%E2%80%94%20laba2UseCase.txt) и
 [рисунок](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/Lab2_usecase_diagram.png?raw=true) диаграммы прецедентов
 
![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab2/Lab2_usecase_diagram.png?raw=true)

# Лабораторная 3

## Диаграмма последовательности

![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab3/laba3.png?raw=true)

## ER-диаграмма

[Текст](https://github.com/AirNus/AirNus.github.io/blob/master/Lab3/PlantUML_code.txt) и [рисунок](https://github.com/AirNus/AirNus.github.io/blob/master/Lab3/ERD_Diagramm_3_laba.png?raw=true) для диаграммы классов

![none](https://github.com/AirNus/AirNus.github.io/blob/master/Lab3/ERD_Diagramm_3_laba.png?raw=true)

Заказ является записью в БД, которая относится к информационным потокам, и состоит из: Рецепта, Отзыва клиента и Товара, который попал в заказ.

# Лабораторная работа 4-6

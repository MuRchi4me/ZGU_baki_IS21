# ZGU_baki_IS21
Репозиторий для лабораторных работ по дисциплине "Базы данных"
========================
## Лекции
[Лекционные материалы](https://drive.google.com/drive/folders/1rHI2UryIMo35Q-lCUZYopw8V5Hnf5e9z?usp=share_link)

## Лабораторная работа № 0

Лабораторная работа №0 выполняется в ErwinProcessModeler. Программа для работы с физическйо и логической БД. Два варианта установки: новая версия с оффициального сайта и получение студенческой лицензии, либо использование триальной версии. Скачивание старой версии с гугл диска.

Практические задания и лабораторные работы можно выполнять в группах до двух человек.

## Практическая часть 1
Реализовать idef0 модель работы автомойки. Желательно в этой программе. Пример тут

Отчет о практической части содержит PDF/JPEG-файл с вашей функциональной моделью и отправляется пул реквестом в этот репозиторий в папку Pr0_idef0 (Пример students/Petrov_Vasya/Pr0_idef0 ). Шаблон названия пул реквеста "ЗГУ Номер_группы Практическая работа ФИО". Пример: "ЗГУ ИС21 Практическая работа №1 Филимонов Филипп".

## Практическая часть 2
Перед выполнением задания необхордимо выполнить практикум в соответствии с инструкциями из папки "Практические работы". После выполнения заданий, указанных в тексте практикума, составить функциональную модель, по одному из вариантов рассмотренных на занятии. Варианты:

Процесс производства меховых шуб. В процессе существуют заказы, проекты, подбор материалов, рассчет материалов, заказ материалов, рассчет производственных мощностей, поставка товара, производство. (чет)

Процесс заказа товара в интернет магазине. Выбор - заказа - оформление доставки - доставка - получение. (нечет)

(текстовое описание работы с программой) тут

(программа) тут

(видео-лекция) Пример и объяснение того, как сделать функциональную модель, можно посмотреть тут

Отчет о практической части содержит PDF-файл с вашей функциональной моделью и отправляется пул реквестом в этот репозиторий в папку students/k3340/Petrov_Vasya/Pr1_dfd. Шаблон названия пул реквеста "ИТМО ФСПО Номер_группы Практическая работа ФИО". Пример: "ИТМО ФСПО К3340 Практическая работа №1 Филимонов Филипп".

## Типовик (Дополнение к лабороторной по написанию запрсов на выборку)
Дедлайн - конец семестра.
Требуется выполнить курс "Оператор Select (версия 2021)" на сайте http://learnsql.ru/. Курс содержит 60 заданий на различные темы. Задания могут относиться к разным темам. При выполнении заданя в меню "Темы для изучения", доступны ссылки на методрические материалы по необходимым для выполнения задания темам.

## Лабораторная работа №2
Тема: SQL. Таблицы.
Цель работы: Получение практических навыков работы с СУБД и языком SQL
(создание и изменения таблиц).
Задание:
1) В созданной на предыдущей лабораторной работе базе данных дополните таблицы
ограничениями CHECK, DEFAULT, NOT NULL, UNIQUE, PRIMARY KEY,
FOREIGN KEY;
2) внести изменения в схему базы, используя операторы ALTER TABLE; и DROP
TABLE;
3) создайте новую таблицу (не менее трех полей);
4) добавьте в нее новый столбец;
5) удалите второй столбец из новой таблицы;
6) удалите все таблицу;
Отчет по лабораторной работе должен содержать:
1. Фамилию и номер группы учащегося, задание
2. Коды операций
3. Принтскриты всех выполненных операторов


## Лабораторная работа №3
Тема: SQL. Операторы модификации данных.
Цель работы: Получение практических навыков работы с СУБД и языком SQL
(операторы insert, update, delete, truncate).
Задание:
1) внести данные с таблицы, созданные на предыдущих лабораторных работах,
используя оператор INSERT (не менее 3 строк у каждую таблицу);
2) изменить данные в таблицах, используя оператор UPDATE (не менее 3
изменений);
3) внесите данные в одну из таблиц из другой таблицы (если нет подходящих данных
создайте дополнительную таблицу и нанесите данные в нее);
4) удалить часть данных из заполненной таблицы, используя оператор DELETE;
5) удалить оставшуюся часть данных с просмотром удаленных полей, используя
оператор DELETE и инструкцию RETURNING;
6) удалите данные из другой таблицы, использую TRUNCATE;
7) восстановите данные в таблицах, использую свои коды из пункта 1 (чтобы для
следующей лабораторной работы таблицы были заполнены).
Отчет по лабораторной работе должен содержать:
1. Фамилию и номер группы учащегося, задание.
2. Коды операций.
3. Принтскриты всех выполненных операторов.

## Лабораторная работа №4
Тема: SQL. Запросы.
Цель работы: Получение практических навыков работы с СУБД и языком SQL
(оператор SELECT).
Задание:
1) разработать запросы к базе данных, созданной и заполненной на предыдущих
лабораторных работах, следующих видов:  
a. запрос с условием на числовые данные (>,<,=, between);  
b. запрос с условием на текстовые данные (LIKE, IN);  
c. запрос с вычисляемым полем;  
d. запрос к нескольким таблицам (без явного указания JOIN);  
e. запрос с агрегирующей функцией (AVG, SUM, COUNT, MIN, MAX);  
f. запрос с группировкой (GROUP BY);  
g. запрос с сортировкой (ORDER BY);  
h. запрос с вложенным подзапросом (не менее 3 видов);  
i. запрос с оператором UNION;  
j. запрос с оператором INTERSECT;  
k. запрос с оператором EXCEPT;  
l. запрос с выражением CASE;  
m. запрос с оператором JOIN (пять видов);  
n. иерархический запрос.
2) Для каждого запроса подписать, что именно он возвращает с учетом предметной
области (запросы со смыслом, а не только синтаксически правильные операторы).
Отчет по лабораторной работе должен содержать:
1. Фамилию и номер группы учащегося, задание.
2. Коды операций.
3. Принтскриты всех выполненных операторов.

## Лабораторная работа №5
Тема: SQL. Индексы и представления.
Цель работы: Получение практических навыков работы с СУБД и языком SQL
(операторы create index, create view, alter view, drop index, drop view).
Задание:
1) Разработать представления к базе данных, созданной и заполненной на
предыдущих лабораторных работах, следующих видов:
a. простое нематериализованное;
b. материализованное неизменяемое;
c. простое изменяемое (невозможно изменить неотображаемые в
представлении строки);
d. простое изменяемое (можно изменить неотображаемые в представлении
строки).
2) Выполнить изменение данных в базовых таблицах через изменяемые преставления
(три разных оператора модификации).
3) Обновить данные в материализованном представлении.
4) Разработать индексы к базе данных, созданной и заполненной на предыдущих
лабораторных работах, следующих видов:
a. простой в целой таблице;
b. составной частичный к таблице;
c. уникальный к материализованному представлению;
d. с заданной сортировкой составной к таблице.
5) Переименовать одно из представлений.
6) Удалить один из индексов и одно представление.
Отчет по лабораторной работе должен содержать:
1. Фамилию и номер группы учащегося, задание.
2. Коды операций.
3. Принтскриты всех выполненных операторов.

## Лабораторная работа №6
Тема: SQL. Функции, процедуры.
Цель работы: Получение практических навыков работы с СУБД и языком SQL
(операторы create function, create procedure, alter function, drop function).
Задание:
1) Разработать в базе данных, созданной и заполненной на предыдущих лабораторных
работах, следующие виды функций:
a. функция с пустыми входными параметрами, результат которой скалярное
выражение;
b. функция со скалярным аргументом, результат которой соответствует типу
существующей таблицы;
c. функция с выходными аргументами, определенными с помощью OUT;
d. функция, результат которой определен с помощью RETURNS TABLE.
2) В функциях использовать ветвление, циклы, обработку ошибок и т.д.
3) Объяснить логику работы каждой функции (что она делает).
4) Создать процедуру.
5) Переименовать одну из функций.
6) Удалить одну из функций.
Отчет по лабораторной работе должен содержать:
1. Фамилию и номер группы учащегося, задание.
2. Коды операций.
3. Принтскриты всех выполненных операторов.


## Сдача работ


Все отчеты сохраняются в **pdf** (документы и презентации).

Все студенческие работы хранятся в папке **Students**
Для сдачи работы необходимо:
1. Зарегиться на гите.
2. Сделать форк репозитория с заданиями в свой аккаунт (на странице https://github.com/IgorSergeevichISIT/ZGU_baki_IS21 кнопка fork справа, сверху).
3. Установить гит на компьютер.
4. Открыть папку, где хранятся Ваши проекты. В контекстом меню нажать "Open Git Bash here". Склонировать форкнутый репозиторий на компьютер (git clone https://github.com/IgorSergeevichISIT/ZGU_baki_IS21).
5. В файловой системе Вашего компрьютера, в склонированном репозитории создать в папке students/группа Вашу личную папку в формате Фамилия_Имя латиницей (Пример **students/Petrov_Vasya**).
6. В личной папке сделать подпапку с текущей работой в формате lr_номер (Пример **students/kPetrov_Vasya/Lr1**).
7. Записать в папку отчетные материалы.
8. Сделать коммит, описать его адекватно (Пример "был добавлен файл перезентация_петров.pdf"). Набрать команлы git add и git commit -m "название комита".
9. Сделать push в Ваш форкнутый репозиторий (git push).
10. Сделать пул-реквест в мой репозиторий из вашего форкнутого, описать его адекватно.
Пока пользуйтесь [этой](https://vk.com/@efimchik_post_edu-tfm-2019-1) инструкцией, у нас нет веток с заданиями, как тут, но Вам поможет. Скоро запишу ролик.
Все работы сдаются средствами создания Pull Requests в папку students в этом репозитории.
**Прошедшие работы тоже необходимо запулреквестить.**

Еще один мануал о том, как сделать Pull Request, описан [тут](https://rustycrate.ru/%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%B0/2016/03/07/contributing.html).


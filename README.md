## Домашние задания к лекциям:
1) ## ["Проектирование БД "](Homework_1)
Реализуйте сущности продукты, категории продуктов, цены, поставщики, производители, покупатели и покупки
Свои решения для этой схемы приветствуются
В проекте должны быть :
  * Схема
  * Документация
  * Примеры бизнес-задач которые решает база
  * Рекомендации к использованию репликации
  * Рекомендации к резервному копированию
2) ## ["Компоненты современной СУБД"](Homework_2/homework_2.txt)
Научиться применять индексы в реальном проекте :
 * Проводим анализ возможных запросов\отчетов\поиска данных
 * Предполагаем возможную кардинальность поля
 * Создаем дополнительные индексы - простые или композитные
 * На каждый индекс пишем краткое описание зачем он нужен (почему по этому полю\полям)
 * Думаем какие логические ограничения в БД нужно добавить - например какие поля должны быть уникальны, в какие нужно добавить условия, чтобы не нарушить бизнес логику. Пример - нельзя провести операцию по переводу средств на отрицательную сумму
 * Создаем ограничения по выбранным полям
3) ## ["Внутренняя архитектура СУБД PostgreSQL "](Homework_3)
Создать кластер PostgreSQL в докере или на виртуальной машине, запустить сервер и подключить клиента :
 * Развернуть контейнер с PostgreSQL или установить СУБД на виртуальную машину
 * Запустить сервер
 * Создать клиента с подключением к базе данных postgres через командную строку
 * Подключиться к серверу используя pgAdmin или другое аналогичное приложение
4) ## ["DDL: создание, изменение и удаление объектов в PostgreSQL"](Homework_4)
Используя операторы DDL создайте на примере схемы интернет-магазина :
 * Базу данных
 * Табличные пространства и роли
 * Схему данных
 * Таблицы своего проекта, распределив их по схемам и табличным пространствам

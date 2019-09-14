# TrainMySQL
Lessen2:
=====================================================================================================================================================================
1 Добавлен .my.conf для задания
[Установите СУБД MySQL. Создайте в домашней директории файл .my.cnf, задав в нем логин и пароль, который указывался при установке.]

2. Добавлен файл c_db_tbl.sh по 2-3 заданиям:
[Создайте базу данных example, разместите в ней таблицу users, состоящую из двух столбцов, числового id и строкового name.] 
[Создайте дамп базы данных example из предыдущего задания, разверните содержимое дампа в новую базу данных sample.]
	+ создание схемы
	+ создание и наполнения таблицы
	+ создание экспорта схемы
	+ импорт схемы
Примечание:
Запуск файла ./c_db_tbl.sh user database password userdump databasedump passworddump
где
	user - пользователь MySql, пример -> root
	database - новая БД, пример из задания 2-> example
	userdump - БД для импорта, пример из задания 3->sample

3. Добавлен файл c_dump_help_limit.sh по 4 заданию
[Ознакомьтесь более подробно с документацией утилиты mysqldump.
Создайте дамп единственной таблицы help_keyword базы данных mysql. Причем добейтесь того, чтобы дамп содержал только первые 100 строк таблицы.]
Примечание:
Запуск файла ./c_dump_help_limit.sh user password row_count
где
	user - пользователь MySql, пример -> root
	password - пароль для user
	row_count - количество строк экспорта(дампа) для таблицы mysql.help_keyword 	

Lessen1:
=====================================================================================================================================================================
1. Добавлен create_tbl.sql создания:
	+ Таблица постов 
	+ Таблица типов постов
	+ Таблица типов статусов: активна, удалена, архивирована, сохранена в закладках
	+ Таблица лайков
	+ Таблица типов лайков: медиафайлы, посты и пользователи
	+ Таблица действий пользователей: лайк, пост, медиафайл и т.д.
	+ Таблица типов действий пользователя

 


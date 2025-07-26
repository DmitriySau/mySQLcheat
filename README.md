# mySQLcheat 
SHOW DATABASES  -  Показать все базы данных
CREATE DATABASE имя - Создать новую базу данных
USE имя_базы - Выбрать базу данных для работы
DROP DATABASE имя - Удалить базу данных
SHOW TABLES - Показать все таблицы в текущей базе
DESCRIBE имя_таблицы или DESC имя_таблицы - Показать структуру таблицы
CREATE TABLE имя (поля) - Создать новую таблицу
DROP TABLE имя - Удалить таблицу
ALTER TABLE имя ADD COLUMN поле тип - Добавить новый столбец
ALTER TABLE имя DROP COLUMN поле - Удалить столбец
ALTER TABLE имя MODIFY COLUMN поле новый_тип - Изменить тип столбца
INSERT INTO таблица (поля) VALUES (значения) - Вставить новую запись
SELECT * FROM таблица - Выбрать все записи из таблицы
SELECT поля FROM таблица WHERE условие - Выбрать записи по условию
SELECT DISTINCT поле FROM таблица - Выбрать уникальные значения
UPDATE таблица SET поле=значение WHERE условие - Обновить записи
DELETE FROM таблица WHERE условие - Удалить записи по условию
DELETE FROM таблица - Удалить все записи из таблицы
SELECT * FROM таблица ORDER BY поле ASC/DESC - Сортировка записей
SELECT * FROM таблица LIMIT число - Ограничить количество записей
SELECT * FROM таблица WHERE поле LIKE 'шаблон' - Поиск по шаблону (%)
SELECT COUNT(*) FROM таблица - Подсчет количества записей
SELECT SUM(поле) FROM таблица - Сумма значений в поле
SELECT AVG(поле) FROM таблица - Среднее значение поля
SELECT MAX(поле) FROM таблица - Максимальное значение
SELECT MIN(поле) FROM таблица - Минимальное значение
SELECT * FROM таблица1 JOIN таблица2 ON условие - Объединение таблиц
SELECT * FROM таблица1 LEFT JOIN таблица2 ON условие - Левое объединение
SELECT * FROM таблица1 RIGHT JOIN таблица2 ON условие - Правое объединение
SELECT * FROM таблица WHERE поле IN (значения) - Поиск среди значений
SELECT * FROM таблица WHERE поле BETWEEN значение1 AND значение2 - Диапазон значений
SELECT * FROM таблица WHERE поле IS NULL - Поиск NULL значений
SELECT * FROM таблица WHERE поле IS NOT NULL - Поиск не NULL значений
GROUP BY поле - Группировка записей
HAVING условие - Фильтр для группировок
CREATE INDEX имя ON таблица (поле) - Создать индекс
DROP INDEX имя ON таблица - Удалить индекс
SHOW INDEX FROM таблица - Показать индексы таблицы
CREATE USER 'имя'@'хост' IDENTIFIED BY 'пароль' - Создать пользователя
DROP USER 'имя'@'хост' - Удалить пользователя
SHOW GRANTS FOR 'имя'@'хост' - Показать права пользователя

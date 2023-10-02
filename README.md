# Test task for Python Junior position  // Task made in learning purpose
Task taken from repo - [репозитория Hexlet](https://github.com/Hexlet/ru-test-assignments)

## Task: 
Часть No1 (обязательная)\
Создайте веб страницу, которая будет выводить иерархию сотрудников в
древовидной форме.\
 ● Информация о каждом сотруднике должна храниться в базе данных и
 содержать следующие данные:\
 ○ ФИО;\
 ○ Должность;\
 ○ Дата приема на работу;\
 ○ Размер заработной платы;\
● У каждого сотрудника есть 1 начальник;\
● База данных должна содержать не менее 50 000 сотрудников и 5 уровней
иерархий.\
● Не забудьте отобразить должность сотрудника.

Часть No2 (опциональная)
1. Создайте базу данных используя миграции Django / Flask.
2. Используйте DB seeder для Django ORM / Flask-SQLAlchemy для заполнения
базы данных.
3. Используйте Twitter Bootstrap для создания базовых стилей Вашей страницы.
4. Создайте еще одну страницу и выведите на ней список сотрудников со всей
имеющейся о сотруднике информацией из базы данных и возможностью
сортировать по любому полю.
5. Добавьте возможность поиска сотрудников по любому полю для страницы
созданной в задаче 4.
6. Добавьте возможность сортировать (и искать если Вы выполнили задачу No5)
по любому полю без перезагрузки страницы, например используя ajax.
7. Используя стандартные функции Django / Flask, осуществите аутентификацию
пользователя для раздела веб сайта доступного только для
зарегистрированных пользователей.
8. Перенесите функционал разработанный в задачах 4, 5 и 6 (используя ajax
запросы) в раздел доступный только для зарегистрированных пользователей.
9. В разделе доступном только для зарегистрированных пользователей,
реализуйте остальные CRUD операции для записей сотрудников. Пожалуйста
заметьте, что все поля касающиеся пользователей должны быть
редактируемыми, включая начальника каждого сотрудника.
10. Осуществите возможность загружать фотографию сотрудника и отобразите ее
на странице, где можно редактировать данные о сотрудник. Добавьте
дополнительную колонку с уменьшенной фотографией сотрудника на
странице списка всех сотрудников.
11. Осуществите возможность перераспределения сотрудников в случае
изменения начальника (бонусом может быть то, что вы сможете это
осуществить с применением встроенных механизмов/парадигм, предлагаемых
Django ORM / Flask-SQLAlchemy ORM).
12. Реализуйте ленивую загрузку для дерева сотрудников. Например, показывайте
первые два уровня иерархии по умолчанию и подгружайте 2 следующих
уровня или всю ветку дерева при клике на сотрудника второго уровня.
13. Реализуйте возможность менять начальника сотрудника используя drag-n-drop
сразу в дереве сотрудников.
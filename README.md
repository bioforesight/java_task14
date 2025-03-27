# Задание 14. Добавить в проект класс Message
* Добавить в проект класс Message с полями int id, String title, String text, LocalDateTime time. Создать класс контроллера для обработки CRUD запросов к списку объектов Message по аналогии с объектами Person.

* Классы должны располагаться следующим образом:

{корневой пакет}.controller.PersonController.java
{корневой пакет}.dto.Person.java
{корневой пакет}.controller.MessageController.java
{корневой пакет}.dto.Message.java
{корневой пакет}.Application.java
   
* Требования к API:

Person:

GET /person - Возврат списка объектов Person
GET /person/{id} - Возврат объекта Person по id
POST /person - Добавление объекта Person
PUT /person/{id} - Изменение объекта Person по id
DELETE /person/{id} - Удаление объекта Person по id
Поля объекта Person:

    int id;
    String firstname;
    String surname;
    String lastname;
    LocalDate birthday;
 
Message:

GET /message - Возврат списка объектов Message
GET /message/{id} - Возврат объекта Message по id
POST /message - Добавление объекта Message
PUT /message/{id} - Изменение объекта Message по id
DELETE /message/{id} - Удаление объекта Message по id
Поля объекта Message:

    int id;
    String title;
    String text;
    LocalDateTime time;

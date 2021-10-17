## План автоматизации тестирования сценария перехода к форме записи и заполнения этой формы.

Настоящий план автоматизации предполагает проведение функционального тестирования
навигации к форме записи и заполнения самой формы валидными и невалидными данными
с использованием тестирования граничных значений, исследовательского тестирования.

### 1. Перечень автоматизируемых сценариев

[Сценарии приведены в таблице](https://docs.google.com/spreadsheets/d/17dGSegHTG0t-tZt_Y-NeAJXh80O77kiWNtDXVnhJvuo/edit?usp=sharing)

### 2. Перечень используемых инструментов с обоснованием выбора

* IntelliJ IDEA Community Edition - среда разработки
* Java OpenJDK version 11.0.12 - язык программирования
* Gradle - система сборки
* JUnit5 - инфраструктура модульного тестирования для Java
* Selenide - фреймворк для автоматизированного тестирования веб-приложений
* Lombok - библиотека, с помощью которой можно сократить количество шаблонного кода
* Faker - плагин для генерации тестовых данных
* Allure - фреймворк для создания отчетов

Обоснование выбора: данные инструменты являются бесплатными и
находятся в открытом доступе, 
все инструменты совместимы между собой, 
что позволяет упростить работу при написании авто-тестов.

### 3. Перечень необходимых разрешений/данных/доступов

* Необходимо разрешение на тестирование сайта.
* Доступ к базе данных и API сайта

### 4. Перечень и описание возможных рисков при автоматизации

* Риск нагрузить сайт и привести к сбоям в его работе.
* Риск нагрузить менеджеров по продажам, которые обрабатывают заявки.
* Риск сломать какую-то функцию и привести к денежным потерям, 
потому что реальный пользователь не сможет отправить заявку.
* Трудности с поиском правильных локаторов на страницах.

### 5. Перечень необходимых специалистов для автоматизации

Тестировщик автоматизатор

### 6. Интервальная оценка с учётом рисков (в часах)
* Подготовка - 16 часов
* Тестирование - 20 часов
* Времени на преодоление негативных последствий наступления рисков - 15 часов
* Анализ результатов - 16 часов
* Оформление отчетов - 8 часов

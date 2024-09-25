# Рефакторинг баз данных и приложений

### Студенты:
Клюева Яна P34101  
Лазеев Сергей P34131 

# Вкусно и просто

****

**Описание проекта**  
Проект представляет из себя сайт для поиска и хранения рецептов. У каждого
пользователя будет возможность просматривать чужие и добавлять свои рецепты.
Любой пользователь нашего проект сможет собрать собственную базу рецептов из 
своих и чужих идей!

**Сценарии использования**  
1. Регистрация и аутентификация пользователей
2. Создание, удаление, просмотр, редактирование своих рецептов
3. Просмотр ленты рецептов
4. Поиск рецепта по ингредиенту или названию
5. Добавление рецептов других пользователей в избранное

**Компоненты системы**  
* Веб-приложение на React TypeScript
* Backend-приложение на Kotlin и Spring Framework
* База данных PostgreSQL

****

# Этапы разработки проекта

****
### Этап 0. Планирование  
Требуется провести планирование, фиксацию основных моделей данных
и интерфейсов взаимодействия разрабатываемого приложения. Кроме того необходимо настроить
инструменты разработки. 

1. Спланировать архитектуру и контракты сервисов.
2. Настроить систему контроля версий, разделить разработку на ветки.
3. Настроить базу данных.

### Этап 1. MVP  
Необходимо разработать базовый UI, сделать базовый набор CRUD операций над
сущностями рецептов. А также реализовать регистрацию и аутентификацию пользователей.

1. Создать UI системы
2. Реализовать модуль регистрации и аутентификации
3. Реализовать модуль базовых операций над рецептами

### Этап 2. Доработка MVP
Добавить возможность просматривать рецепты других пользователей в "ленте" рецептов.
Добавить поиск рецепта по названию или ингредиентам. 

1. Доработать UI под требования
2. Доработать Backend

### Этап 3. Реализация дополнительного функционала
Добавить функционал раздела "избранное" для каждого пользователя. Добавить
фильтр нецензурной лексики при сохранении рецепта пользователем.

1. Доработать UI
2. Доработать Backend


****
# Общая информация 
Разработка будет вестись с помощью системы контроля версий git. Под проект
создан один репозиторий. Разработка Frontend и Backend частей будет вестись 
параллельно на двух разных ветках. Результаты работы будут вливаться в master-ветку.
Вся система будет развернута на Virtual Private Server.
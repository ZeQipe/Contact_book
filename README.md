# Контактный менеджер
Простое приложение для управления контактами, созданное на Python с использованием библиотек PyQt5 и vObject.

## Описание проекта
Контактный менеджер представляет собой инструмент для удобного управления списком контактов. Пользователь может добавлять, редактировать, удалять и экспортировать контакты. Проект разработан с использованием паттерна проектирования MVC (Model-View-Controller).

## Функциональность
Добавление контакта
Пользователь может добавить новый контакт, введя его имя, фамилию, номер телефона и адрес электронной почты.

### Редактирование контакта
Контакты могут быть отредактированы, позволяя пользователю изменить информацию о контакте.

### Удаление контакта
Пользователь может удалить выбранный контакт из списка.

### Поиск контакта
Реализован поиск контакта по имени или номеру телефона.

### Экспорт и импорт контактов
Поддерживается экспорт контактов в форматах CSV и VCF, а также импорт контактов из файлов CSV и VCF.

## Установка и запуск
Убедитесь, что на вашем компьютере установлен Python версии 3.x.
Установите необходимые библиотеки, запустив команду: pip install -r requirements.txt.
Запустите приложение, выполнив команду: python main.py.

## Структура проекта
- Core/: Основные модели и логика приложения.
- view/: Все файлы, отвечающие за пользовательский интерфейс.
- tools: Модули для обработки информации и реализации логики.
- ReadMe.md: Файл с описанием проекта.
- entry_point.py: Конфигурационные параметры приложения.
Разработчики
[Ваше имя] - Идея, разработка, тестирование.
Лицензия
Этот проект лицензируется в соответствии с условиями лицензии MIT.

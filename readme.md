# Инструкция по работе с git

## Что такое git?
Git одна из реализаций системы контроля версий. Git на данный момент является самой популярной реализацией. Самой популярной реализацией *Git* является [GitHub](https://github.com)
## Подготовка репозитория

Для того, чтобы создать репозиторий используется команда *git init*. Для этого необходимо написать в терминале в папке будующего репозитория команду *git init*.


## Создание "сохранений"
>>>>>>> savescreation

### Добавление файла к коммиту
Для добавления файла к коммиту ипользуется команда *git add*. Пишется она следующим образом: *git add <имя файла>* в терминале в папке с созданным репозиторием.
### Создание коммитов
Для создания нового "сохранения" используется команда *git commit. Используется она следующим образом: в терминале с папкой-репозиторием пишется *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать **обязательно**!!!
## Перемещение между сохранениями
Для перемещения между сохранениями используется команда *git checkout*. Для того, чтобы переместиться на указанный коммит в терминале в папке с репозиторием пишем *git checkout <номер коммита>*. **Номер коммита** берется их журнала изменений, о котором сказано выше. После перемещения на указанный коммит мы попадаем в состояние **detached head**. Чтобы вернуться к обычной работе пишем *git checkout master*.

## Журнал изменений

## Ветки в git

## Журнал сохранений
Для просмотра журнала используется команда *git log. Для этого в терминале в папке с репозиторием необходимо написать *git log*.

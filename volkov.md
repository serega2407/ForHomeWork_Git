![](logotip.jpeg)
# Работа с Git
# Проверка наличия установленного Git

В терминале выполняем команду git version- она выводит версию программы git; если выдаёт ошибку - git не установлен

## Установка Git

Загружаем последнюю версию гита с сайта https://github.com/ устанавливаем с настройками по умолчанию (симулятор нажатия кнопки next) 

## Настройка Git

1. git config --global user.name "@$username"
2. git config --global user.email "$useremail"

Чтобы проверить, запомнил ли Git наши данные, можно ввести команду git config --list
## Создание коммитов

### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и вы увидите были ли изменения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.

### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

### Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git
### Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

### Удаление веток
Для удаления ветки ввести команду *"git branch -d 'name branch'"*
### Диаграмма веток
Чтобы посмотреть диаграмма из символов ASCII, отражающей структуру веток в истории коммитов, вести команду *git log --graph*

### Добавление картинок и игнорирование файлов
Чтобы добавить картинку, надо ввести " ! [] () "

Для игнорирования файлов необходимо создать файл ".gitignore", затем добавить его с помощью команды "git add" и указать в файле то, что хотим игнорировать.

хочу видеть конфликт

Вот картинка конфликта

![](kon.png)
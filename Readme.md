# Инструкция по работе с GIT/

## Что такое GIT?

Git - одна из реализаций распеределенных систем контроля версий,имеющая как локальную версионность , так и версионность на сервере.
Является самой популярной системой контроля на сегодняшний день.

## Подготовка репозитория

Для того что бы создать репозиторий в указанной папке используется команда *git init*. Для этого достаточно написать команду *git init* в папке с будущим репозиторием.

## Создание фиксаций

### Создание коммитов

Для создания новой фиксации необходимо использовать команду *git commit*. Используется она следующим образом: в папке с репозиторием пишется команда *git commit -m "<сообщение к комимиту>"*. Все файлы коммита должны быть предварительно добавлены с помощью команды *git add*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Добавление файла к коммиту

Для того что бы добавить файл к новому коммиту (сохранению), необхаодимо использовать команду *git add*.
используется она следующем образом : в папке с репозиторием необходимо набрать команду *git add <имя файла>.

### Просмотр информации о изменениях

Для того что бы посмотреть информацию об изменениях сделаных в текущей ветке необходимо использовать команду *git status*. Для это достаточно использовать команду *git status* в папке репозитория.

## Перемещение между сохранениями

Для перемещения между коммитами необходимо ввести команду *git checkout*.Для этого необходимо в папке репозитория указать команду *git checkout <имя ветки>*.

## Журнал изминений

Для просмотра журанала изминений необходимо использовать команду *git log*. Для этого необходимо в папке с репозиторием необходимо написать *git log*.

## Ветки в GIT

Для просмотра веток в git необходимо воспользоваться командой *git branch*. Вводя данную команду мы увидим все имеющиеся ветки и ветку на которой мы находимся.

### Создание новой ветки

Для создания новой ветки применим команду *git branch* следующим образом: в папке с репозиторием напишем команду *git branch <имя новой ветки>.

### Переход между ветками

Для переключения между ветками применяем *git branch* следующим образом: в папке с репозиторием пишем команду *git branch <имя ветки на которую переходим>.

## Слияние веток и разрешение конфликтов

## Удаление веток

## Работа с удаленным репозиторием GitHab

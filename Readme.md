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

Для слияния веток после внесения неоходимых правок приминяют команду *git merge*. Для этого необходимо перейти на ту ветку в которую будет производиться перенос данных и после этого указываем ту ветку которую притягиваем командой *git merge <имя ветки которую надо влить>.
При слиянии веток возможно создание конфликтов между существующей версией и версией вливаемой. В случае возникновения пользователь долже принять решение о том какую версию правок оставить: 1 . Версия правок из другой ветки, 2. версия правок ветки в которой находится пользователь, 3. Принять правки из обеих веток.

## Удаление веток

Для удаления лишних, отработанных веток приминяется команда *git branch*, в папке с репозиторием необходимо написать *git branch -d <имя ветки>.

## Работа с удаленным репозиторием GitHab

В данном пункте будут указаны несколько команд используемые для работы с удаленным репозиторием.

Для того что бы клонировать удаленный репозиторий на свой компьютер необходимо ввести команду *git clone* в папке куда планируете следующим образом: *git clone <адрес файла удаленного репозитория>*

Для того что бы скачать все из удаленного репозитория приминяют команду *git pull* следующим образом в папке с репозиторием вводят *git pull <адрес удаленного файла>*.
Одновременно со скачиванием файла, команда *git pull* проведет *merge* слияние с локальным репозиторием.

Для передачи версии локального репозиторя на удаленный репозиторий приминяют команду *git push* следующим образом: в папке с репозиторием *git push <адрес удаленного репозитория>.***ВАЖНО требуется АВТОРИЗАЦИЯ на внешнем репозитории***.

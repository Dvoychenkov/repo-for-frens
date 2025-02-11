#### Что такое Git
Система контроля версий (VCS) хранит историю изменений в проектах и помогает разработчикам.

Git — самый популярный продукт VCS, который используется в командной работе.

* **Git** позволяет сохранять и «склеивать» труд разных программистов, облегчая работу над проектами.
Системы контроля версий помогают разработчикам контролировать изменения в проектах и сохранять историю.

**Git** является примером системы контроля версий и помогает хранить, изменять и анализировать историю проекта.

Для выделения важных моментов или ключевых идей можно использовать *курсив* или **жирный шрифт**. А маркированные списки помогут структурировать информацию:

- **Основные функции Git:**
  - хранение истории изменений;
  - контроль версий;
  - совместная работа над проектами.


#### Установка и настройка Git

Установка и настройка Git важна для работы с командной строкой.

Для Windows Git уже установлен в составе пакета Git for Windows.

Для macOS можно установить Git с помощью команды ```/usr/bin/git``` или через менеджер пакетов Homebrew.

Для Linux нужно использовать терминал и выбрать команду установки для своей версии Linux.

Настройка Git включает указание имени пользователя и электронной почты с помощью команды git config.

Глобальные настройки хранятся в файле ```.gitconfig``` в домашней директории.


#### Основные команды

Инициализация репозитория
```git init``` (от англ. initialize, «инициализировать») — инициализируй репозиторий.

Подготовка файла к коммиту
```git add todo.txt``` (от англ. add, «добавить») — подготовь файл ```todo.txt``` к коммиту;
```git add --all``` (от англ. add, «добавить» + all, «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы;
```git add .``` — подготовь к коммиту текущую папку и все файлы в ней.

Создание коммита
```git commit -m "Комментарий к коммиту."``` (от англ. commit, «совершать», «фиксировать» + message, «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены.

Просмотр информации о коммитах
```git log``` (от англ. log, «журнал [записей]») — выведи подробную историю коммитов.

Просмотр состояния файлов
```git status``` (от англ. status, «статус», «состояние») — покажи текущее состояние репозитория.

#### И ещё чуток шпаргалки из уроков
1. Хеш, лог и HEAD
2. Зачем нужны статусы файлов и как читать git status
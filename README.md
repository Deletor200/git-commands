## Шпаргалка для Git

    `&&` – выполнение нескольких команд сразу  
    — Дважды нажатый tab показывает все команды или директории начинающиеся на введенные в консоль символы

    `pwd` – просмотр текущей директории  
    `cd` – перемещение по директориям  
        `~` – домашняя директория  
        `..` – родительская директория  
        `.` – текущая директория  
    `ls` – посмотреть содержимое директории  
        `-a` – просмотр скрытых файлов
    `touch` – создать файл | несколько файлов(через пробел)  
    `mkdir` – создать директорию | несколько файлов(через пробел)  
        `-p` – создать структуру директории(несколько папок)  
        `~/` и `../../` – можно использовать для задания расположения директории  
    `cp` *что_копировать что_копировать куда_копировать*  
    `mv` – перемещений файлов и папок  
    `cat` – чтение файлов  
    `rm` – удаление файлов  
        `-r` – удаление папок со всем содержимым(рекурсивное удаление)  
    `rmdir` – удаление директорий(пустых)

    `git init` – сделать текущую папку Git-репозиторием  
    `rm -rf .git` – разгидить папку  
        `-f` – удалить сообщения о подтверждении удаления файла  
    `git status` – проверить состояние репозитория  
    `git add` – подготовить файлы к сохранению в git  
        `--all` – все файлы  
    `git commit` -m '*...*' – сделать коммит  
        `-m` – ключ-сообщение  
    `git log` – посмотреть историю коммитов  
    `clip <` *путь* – скопировать содержание файла  
    `git remote add` *имя URL* – привязать удалённый репозиторий к локальному  
    `git remote -v` – убедиться, что репозитории связаны  
        `-v`/`--verbose` – показать больше информации о выводе  
    `git push` **(`-u` *имя_репозитория имя_ветки(main, master)*) – отправить изменения на удалённый репозиторий  
        **() - первая отправка  
        `-u` – связывает ветку с удалённым репозиторием  
`git clone` *URL* – клонировать репозиторий
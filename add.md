### git add

Это одна из ключевых команд Git
Чтобы добавить отслеживание новых файлов, необходимо использовать команду `git add <filename> <filename>` для добавления нескольких файлов по имени.

Добавить отслеживание новых файлов
В случае если у вас много файлов для добавления, можно воспользоваться командой `git add .` ,
 которая добавляет отслеживание для всех новых файлов из текущей директории. А команда `git add -A` добавляет ещё и удалённые файлы, не только из текущей директории, но и из всего локального репозитория.
 
 Команда `git add` добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита. По умолчанию `git commit` использует лишь этот индекс, так что вы можете использовать `git add` для сборки слепка вашего следующего коммита.

[На главную](./readme.md)
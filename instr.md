# Инструкция для работы с Git и удаленными репозиториями

```sh
## Git - это
Одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории.
```
## Подготовка репозитория 
 * Для создания репозитория необходимо выполнить команду *`git init`* (появиться скрытая папка .git)

## Создание коммитов
 * Для добавления изменений в коммит необходимо изпользоваиь команду *`git add`* (необходимо добавить <имя файла>). 

 * Для того чтобы сохранить коммит используется команда *`git commit -m`* (можно добавить <комментарий>).

 ## Просмотр состояния репозитория
  * Для посмотра  состояния репозитория используется команда *`git status`* (будут видны все изменения).

## Информация по  изменениям коммитов
 * Для просмотра различий по внесенным изменениям в еще не проиндексированных файлах необходима использовать команду *`git diff`*.
 * Для просмора истории изменения коммитов неоходимо использовать команду *`git log --oneline`*.
## Просмотр промежуточных вариантов
 * Для просмотра промежуточного варианта необходима спользовать команду *`git checkout`* (вести ссылку на соответсующий коммит).
  * Для возврата к последнему сохраненному варианту репозитория необходима команда *    git checkout master`*.
```sh
ПРИМЕЧАНИЕ:
  1. Для выбора (перемещения) необходимой команды git можно использовать клавиши со стрелками.
  2. Для написания названия файла достаточно написать 3 перых буквы и нажать tab.
  3. Для написания ссылки на коммит достаточно указать первых 4 символа. 
  ```
# Добавим как добавлять картинки в Markdown
Это яблоко
![Яблоко](apple.jpg)
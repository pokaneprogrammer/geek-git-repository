# Руководство по работе с GIT

## Инициализация нового репозитория

### Для инициализации нового репозитория введите команду
'''
   git init
'''

## Добавление файла в репозиторий

Для добавления файла в репозиторий введите команду
'''
git add <имя файла>
'''

Для сохранения измененного файла введите команду
'''
git commit -m <имя файла>
'''

Для внесения изменений в последний коммит введите команду
'''
git commit --amend -m <новое название коммита>
'''

Для просмотра списkа всех коммитов введите команду
'''
git log
'''

Для перемещения между ветками введите команду
'''
git checkout <название коммита>

## Коммит версии

Для фиксации изменений введите команду
'''
git commit -m <сообщение>
'''

## Создание новой ветки

Для создания новой ветки введите команду 
'''
git branch <имя ветки>
'''

## Перенос основания ветки

Для переноса основания текущей ветки на последний коммит другой ветки нужно выполнить команду
'''
git rebase <имя ветки>
'''

## Вливание одной ветки в другую

Чтобы влить одну из существующих веток в текущую нужно выполнить команду
'''
git merge <имя вливаемой ветки>
'''

## Клонирование репозитория

Для того, чтобы склонировать на свой компьютер репозиторий с git-хостинга нужно получить ссылку на данный репозиторий и использовать команду
'''
git clone <ссылка на репозиторий>
'''
## Отправка изменений на git-хостинг

Для отправки текущей ветки нужно ввести команду
'''
git push
'''

## Отчистка от незафиксированных изменений
Для отмены незафиксированных изменений в файлах проекта введите команду
'''
git reset --hard
'''

## Добавили новую ветку

Secondbrench
'''
git checkout -b <имя ветки>

Отправили изменения

С помощью команды
'''
git push
'''

## Изменить коммит на github

Команда
'''
Edit this file
'''

## Добавили ветку

Thirdbranch
'''
git checkout -b <название ветки>
'''

## Отправка измений репозитория на внешний репозиторий

Для отправки текущей ветки нужно ввести команду
'''
git push
'''

## Убрать незафиксированные изменения в файлах проекта

Введите команду
'''
git reset --hard
'''

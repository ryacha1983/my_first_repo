﻿# my_first_repo

## Работа с удаленными репозиториями.
 Копировать внешний репозиторий на свой ПК можно командой git clone.

Команда git clone составная: она не только
загружает все изменения, но и пытается слить 
все ветки на локальном компьютере и в
удаленном репозитории.

git pull
Эта команда позволяет скачать все 
из текущего репозитория и автоматически
сделать merge с нашей версией
Эта команда позволяет отправить нашу
версию репозитория на внешний
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ 
на внешнем репозитории.


git push
Эта команда позволяет отправить свою версию репозитория во
внешний репозиторий поможет команда git
push. При первом её использовании нужна авторизация.

## Как настроить совместную работу

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. 
 GitHub при создании нового репозитория подскажет, как это можно сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, 
вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с другого компьютера”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

## В новой ветке!!! 
pull request

➜ команда для предложения изменений
➜ запрос на вливание изменений в репозиторий
В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают
команду pull request. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала
пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем
клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет
изменения командой push в свой аккаунт на GitHub и даёт команду pull request. 

## КОНФЛИКТ
Как сделать pull request
Делаем   (ответвление) репозитория fork
Делаем git clone   версии репозитория СВОЕЙ
Создаем новую ветку и в НЕЕ вносим свои изменения
Фиксируем изменения (делаем коммиты)
Отправляем свою версию в свой GitHub
На сайте GitHub нажимаем кнопку pull request

еще конфликт

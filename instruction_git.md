# **Инструкция по работе с Git**

## Общая информация о Gil

Git - это очень полезный продукт, который позволяет легко наладить версионирование любого проекта.

## Создание нового репозитория 

Чтобы (инициализировать) новый репозиторий в текущей папке необходимо в терминале выполнить команду:

    git init

## Проверка состояния репозитория

Чтобы проверить текущее сосотояние Git, есть ли изменения, которые нужно закоммитить, в текущей папке необходимо в терминале выполнить команду:

git status

## Добавление изменений к индексу

Чтобы добавить содержимое рабочего каталога в индекс (staging area) для последующего коммита необходимо выполнить команду:

git add

Чтобы добавить отслеживание новых файлов, необходимо использовать команду:

 git add <filename> <filename> для добавления нескольких файлов по имени


 
## Фиксация изменений

Чтобы зафиксировать и сохранить все данные, добавленные в индекс с помощью git add необходимо выполнить команду:

git commit

Чтобы добавить коммит, необходимо ввести команду:

 git commit -m "Комментарий к коммиту"

## Журнал изменений

Необходимо использовать перед переключением версий файлов в git

## Переключение между версиями

Для работы нужно указать не только нужный нам коммит, НО и вернуться в тот, где работаем сейчас:

git checkout master

## Отличия между файлами

Чтобы увидеть разницу между текущим и сохраненным файлом используем команду:

git diff

*Перед переключение версий файла git используется команда, чтобы увидеть количество изменений: git lof*

# Ветвление

Ветвления нужны, например, для работы над созданием сайтов

### Просмотр существующих веток

Для просмотра существующих веток нужно ввестти команду:
git branch

НУЖНЫЙ ТЕКСТ НЕ ДЛЯ ОШИБКИ

## ДЗ доделать

## ДЗ готово

## Удаленные репозитории

Удаленные репозитории нужеы для

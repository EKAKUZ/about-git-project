# GIT
---
| Команда | Описание |
|---|---|
|**git config --global user.name "User Namovich"**| Настройка имени пользователя|
|**git config --global user.email username@yandex.ru**| Настройка почты пользователя|
|**git config --list**| Посмотреть текущее значение настроек|
|**git init**| Инициализируем GIT (делаем текущую папку репозиторием) |
|**git status**| Проверяем статус репозитория |
|**rm -rf .git**| Разыницилизируем GIT |
|**git add -all / git add .**| Подготавливаем к сохранению в репозитории все файлы |
|**git add _somefile_**| Подготавливаем к сохранению в репозитории конкретный файл |
|**git commit -m 'Мой первый коммит!'**| Сохраняем подготовленные файлы в репозиторий с комментарием 'Мой первый коммит!' |
|**git log**| Смотри историю коммитов |
|**git remote add origin _linkfromgithub_**| Связываем удаленный репозиторий с локальным |
|**git remote -v**| Проверяем связаны ли репозитории |
|**git push -u origin main / master**| Первый раз загрузили локальный репозиторий на GitHub |
|**git push**| Загружаем локальный репозиторий на GitHub |
|**git clone _linkfromgithub_**| Создаем копию удаленного репозитория на локальном компьютере |


- **_somefile_** - имя файла на вашем компьютере
- **_linkfromgithub_** - ссылка на репозиторий на GitHub

- **origin** - стандартный псевдоним, с помощью которого можно обращаться к главному удалённому репозиторию (обычно такой репозиторий один)

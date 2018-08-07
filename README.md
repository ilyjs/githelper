# Git Helper

Небольшая инструкция, мануал, напоминалка в основном для Андрея.

#### Инициализация локального репозитория
```
git init
```

#### Добавления удаленного репозитория
```
git remote add origin https://github.com/ilyjs/githelper.git
```

#### Добавление файлов в git
Добавление файла:
```
git add anyFile
```

Добавление только отслеживаемых файлов (которые были изменены)  :
```
git add -u
```
Добавление всех фалов в папке  :
```
git add folder/subfolder/*
```


[ru.stackoverflow.com](https://ru.stackoverflow.com/questions/431839/%D0%92-%D1%87%D0%B5%D0%BC-%D1%80%D0%B0%D0%B7%D0%BD%D0%B8%D1%86%D0%B0-%D0%BC%D0%B5%D0%B6%D0%B4%D1%83-git-add-add-a-add-u-%D0%B8-add)

[git-scm.com](https://git-scm.com/book/ru/v1/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C-%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9-%D0%B2-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B9)

#### Проверка статуса
```
git status
```

#### Коммит
```
git commit -m "any comment"
```


### Пуш
Отправка на удаленный репозиторий <br/>
`origin - имя удаленного репозитория` <br/>
`master - название ветки`
```
git push -u origin master
```

### Пул
Получение из удаленного репозитория <br/>
`origin - имя удаленного репозитория` <br/>
`master - название ветки`
```
git pull origin master
```

### Работа с ветками
Создание новой ветки:
```
git checkout -b name_new_branch
```
Переключится на ветку:
```
git checkout  name_branch
```
### Слияние
```
git merge name_branch
```

### Github pages
Github pages используется в ветке gh-pages

### Узнай больше

[Узнать больше](https://eax.me/git-commands/)




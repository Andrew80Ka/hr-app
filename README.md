# Проект 

## Работа над новым (простым) проектом
В адресе проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и
разместите в нее папку вашего проекта. Может получится что то похожее на это: D:\projects\hr-app

1. Содоаем структуру проекта на ПК
```sh
например...

app/
    css/
        style.css
    js/
        main.js
    index.html
    README.md
    .gitignore
```

2. На GitHub создаем новый RP
```sh
например...
    hr-app

    или любое др. имя

```

3. На ПК инициализируем  git
```sh
в папке с проектом инициализируем  git
    git init
    git add .
    git commit -m "first commit"
    git remote add origin https://github.com/....../hr-app.git
    git push -u origin master
```

4. Создаем новую ветку для работы
```sh

    git branch develop
    git checkout develop

```

### Начинаем работу над проектом

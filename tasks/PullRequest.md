# Задача сделать Pull Request для Lab_People

### 0. 

Переходим в папку проекта (если мы не в ней)

`cd путь/до/Lab_People/`

**1.** Создаем ветку dev и переключаемся на нее

git checkout -b dev 

**2.** Вносим изменения в файл index.js, потом проверяем:

`git status`
`git diff`

**3.** Оформляем коммит

`git add .`
`git commit -m 'название коммита'`

**4.** Отправляем коммит в удалённый репозиторий 

`git push origin dev`

**5.** Создаем пулл-реквест (Pull Request, PR) на сайте github в репозиторий lapatkindi/Lab_People
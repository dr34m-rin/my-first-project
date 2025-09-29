# Отчет по настройке GitHub

**Дата:** [29.09.2025]
**Команда:** [Мулюков Ринат]

## Выполненные действия:

### Создание репозитория на GitHub
- [x] Репозиторий my-first-project создан
- [x] Ссылка: https://github.com/dr34m-rin/my-first-project

### Связывание локального и удаленного репозитория
- [x] Команда git remote add origin выполнена
- [x] Ветка переименована в main
- [x] Код успешно отправлен (git push)

## Проблемы и решения:

### Проблема 1: Ошибка "remote origin already exists"
**Описание:** При выполнении "git remote add origin" появилась ошибка что remote уже существует
**Решение:** Выполнил команды:
```bash
git remote -v    # посмотрел какие репозитории привязаны
git remote remove origin   # удалил старую привязку
git remote add origin https://github.com/dr34m-rin/my-first-project.git  # добавил правильную
![
    
](<скрины/Source Conrol Panel Screen.png>) ![
    
](скрины/git-push.png) ![
    
](<скрины/Репозиторий в GitHub.png>) ![
    
](скрины/Структура.png)
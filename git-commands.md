### Основные GIT команды:

1. Инициализация репозитория в папке
git init

2. Проиндексировать все файлы в директории
git add .

3. Cоздание коммита с сообщением
git commit -m "commit name"

4. Посмотреть историю коммитов
git log

5. Связать локальный и удаленный репозиторий
git remote add origin

6. Переименование текущей ветки
git branch -M main

7. чтобы добавить изменения в удаленный репозиторий. после origin указывается название ветки (обратите внимание у вас main или master)
git push -u origin main

8. Создать удаленную ветки и залить в нее код с локальной
git push origin

:: 1. Перейти у клонований репозиторій користувача 2
cd D:\assets\OPI_Korol_IPZ12\lab7_Korol\lab7_user2_git\lab7startgit

:: 2. Додати файли у Git
git add .

:: 3. Створити коміт
git commit -m "Add files from lab2"

:: 4. Відправити на GitLab
git push -u origin master

:: 5. Перейти у перший локальний репозиторій
cd D:\assets\OPI_Korol_IPZ12\lab7_Korol\lab7_start_git

:: 6. Оновити локальний репозиторій (отримати зміни з GitLab)
git pull origin master

:: 7. Далі для будь-яких змін у файлах:
git add .
git commit -m "Опис змін"
git push origin master

:: 8. Щоб отримати останні зміни з GitLab у будь-якому локальному репозиторії
git pull origin master

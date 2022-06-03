TXT

1. Создать внешний репозиторий c названием TXT.
repositories - new

2. Клонировать репозиторий TXT на локальный компьютер.
git clone ключ ssh

3. Внутри локального TXT создать файл “new.txt”.
cd txt
touch new.txt

4. Добавить файл под гит.
git add .

5. Закоммитить файл.
git commit -m "add file new.txt"

6. Отправить файл на внешний GitHub репозиторий.
git push

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
cat >> new.txt
Full Name - Don Simon
Age - 34
Pets - 1
Salary - 1000000
ctrl + D

8. Отправить изменения на внешний репозиторий.
git commit -am "Add changes file"
git push

9. Создать файл preferences.txt
touch preferences.txt

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
cat >> preferences.txt
Favorite movie: RocknRolla,
Favorite TV-show: Top Gir,
Favorite food: Bolognese,
Country to which would like to visit: USA
ctrl + D

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.
cat > skills.txt
Skills: Linux, Git, GitHub, GitBash, API.
ctrl + D

12. Сделать коммит в одну строку.
git add .
git commit -m "Add changes preferences and skills"

13. Отправить сразу 2 файла на внешний репозиторий.
git push

14. На веб интерфейсе создать файл bug_report.txt.
Add file / Create new file

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes "Add new file"

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Edit this file

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes "Add changes file"

18. Синхронизировать внешний и локальный репозиторий TXT
git pull

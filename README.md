# TXT

 1. Создать внешний репозиторий c названием TXT.
#Open github

#Repositories-New-TXT-Create repository

 2. Клонировать репозиторий TXT на локальный компьютер.
#Open TXT-Code- Copy
#Open gitbash

git clone https://github.com/Kris02169/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
cd TXT
touch new.txt

 4. Добавить файл под гит.
add new.txt

 5. Закоммитить файл.
git commit -m "New file"

 6. Отправить файл на внешний GitHub репозиторий.
git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
cat >> new.txt
Name: Kristina
Age: 26
Pets: 0
Salary: 500
ctrl+c

 8. Отправить изменения на внешний репозиторий.
git add new.txt; git commit -m "Update"; git push
 
9. Создать файл preferences.txt
cat > preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
cat >> preferences.txt
Movie: Meet Joe Black: Sooner or Later Everyone Does
Serial: How a need your mother
Food: Cake
Season: Summer
ctrl+c

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 cat > skills.txt
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum
ctrl+c

 12. Сделать коммит в одну строку.
 git add .; git commit -m "New files"

 13. Отправить сразу 2 файла на внешний репозиторий.
 git push

 14. На веб интерфейсе создать файл bug_report.txt.
#Add file -Create new file - bug_report.xml

 

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 #Commit new file

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
#bug_report.json-edit this file

Bug_id: 1
Title: The "pay" button is missing
Severity: major
Priority: high
Precondition:
1.Payment page.
2.Platform and device don't matter.
Step to reproduce:
1.Log in
2.Add item to cart.
3.click the pay button.
AR: The "pay" button is missing
ER: You can click on "pay" button.
Attachments: https://drive.google.com/file/

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Commit canges

 18. Синхронизировать внешний и локальный репозиторий TXT
git pull

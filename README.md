# JSON

1. Создать внешний репозиторий c названием JSON. 
2. Клонировать репозиторий JSON на локальный компьютер. `git clone https://github.com/ElenaChadushkina/JSON.git`
3. Внутри локального JSON создать файл “new.json”. `cd JSON && touch new.json`
4. Добавить файл под гит `git add new.json`
5. Закоммитить файл. `git commit -m "JSON"`
6. Отправить файл на внешний GitHub репозиторий. `git push`
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
`cat >> new.json`
<pre>{
"First name":"Lena",
"Middle name":"Mikhailovna",
"Last name":"Chadushkina",
"Age": 32,
"Pet": 1,
"Salary":"1000$"
}</pre>
8. Отправить изменения на внешний репозиторий. `git add . `--> `git commit -m "new.json2"` --> `git push`
9. Создать файл preferences.json  `touch preferences.json`
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
`vim preferences.json` --> `i`
<pre>{
"Favorite_movie":"The Pursuit of Happyness",
"Favorite_series":"Game of Thrones",
"Favorite_food":["kebab",
	"pizza",
	"grilled cheese"
],
"Favorite_time_year":"Summer",
"Country":"Indonesia"
}</pre>


 `Esc` --> `:wq`


 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON `vim sklls.json` -->i`
<pre>{
"Basic_testing_theory":[
	"What is testing",
	"Bug reports",
	"Test documentation",
	"SDLC",
	"STLC",
	"Design Test Techniques"
],
"HTTP":[
	"Methods",
	"Status code",
	"Structure of requests and responses"
],
"Data_exchange_formats":[
	"JSON",
	"XML"
],
"API_testing":[
	"Postman",
	"JS",
	"Autotests API"
],
"Traffic_sniffing":[
	"Charles",
	"Fiddler"
],
"Dev_Tools":[
	"Google Chrome",
	"Firefox"
],
"VPN":[
	"How it works",
	"How to use it",
	"Tool options"
],
"Mobile_testing":[
	"iOS",
	"Android",
	"Guidelines",
	"XCode",
	"Android Studio",
	"ADB"
],
"Terminal": "GitBash",
"SQL":[
	"The basics",
	"Postgres",
	"Redis"
],
"Load_testing":"Jmeter",
"Python":[
	"The basics",
	"Creating a client server application"
]
}</pre>
 
 `esc :wq`
 
12. Отправить сразу 2 файла на внешний репозиторий. `add . && git commit -m "preferences and skills"` --> `git pish`
13. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
14.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
15.  На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 <pre>{
 "Bug-ID": "01",
 "Title": "Ошибка авторизации пользователя при вводе валидного логина и пароля",
 "Project": "Сайт Форум Хомячки",
 "STR": [
   "1. Открыть страницу авторизации https://forumhomyachki.com/authorization",
   "2. Ввести валидный логин и пароль (test@com.ru, 123456)",
   "3. Нажать кнопку 'Войти'"
   ],
 "Actual result": "Система отображает сообщение об ошибке 'При входе произошла ошибка, попробуйте позднее' ",
 "Expected result": "Авторизация прошла успешно, произошел переход в раздел 'Мой профиль'",
 "Environment":{
   "OS": "Windows 10 PRO 64-bit operating system, x64 processor",
   "Browser": "Microsoft Edge Версия 115.0.1901.200 (Официальная сборка) (64-разрядная версия)"
 },
 "Severity": "Critical",
 "Priority": "High",
 "Status": "New",
 "Author": "Чадушкина Елена"
}</pre>
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
17. Синхронизировать внешний и локальный репозиторий JSON `git pull`

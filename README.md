# JSON



**1. Создать внешний репозиторий c названием JSON.**

 `В GitHub нажать: Repositories, New, Create repository.`
 
 
 ---
 
 
**2. Клонировать репозиторий JSON на локальный компьютер.**  

 `git clone ссылка на репозиторий https://github.com/AnastasiiaChyzhykova/JSON.git`
 
 
 ---
 
 
**3. Внутри локального JSON создать файл “new.json”.**    

`touch new.json`


---


**4. Добавить файл под гит.**     

 `git add new.json`
 
 
---


**5. Закоммитить файл.**

 `git commit -m "Название коммита"`
 
 
 ---
 
 
**6. Отправить файл на внешний GitHub репозиторий.**    

 `git push origin название ветки, куда хотим выставить код (например: main)`
 
 
 ---
 
 
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**  

  `cat>> new.json`  

`{
        "name": "Anastasiia",
        "surname": "Chyzhykova",
        "age": 27,
        "number_of_pets": 0,
        "salary": "1400$"
}`


---


**8. Отправить изменения на внешний репозиторий.** 

 `git add new.json , git commit -m "Название коммита", git push origin название ветки`
 
 
---


**9. Создать файл preferences.json**

 `touch preferences.json`
 
 
---


**10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**

 `cat>> preferences.json`

`{
	"avorite_movie ": "Harry Potter ",
	"favorite_series": "Sherlock",
	"favorite_food": "borsch",
	"favorite_season": "spring",
	"the_country_you_would_like_to_visit": "Greece"
}`
	
	
---
	
	
**11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**

 `cat> skills.json`

`{
    "skills": {
        "theory": [
            "types of testing",
            "testing methods",
            "SDLC",
            "STLC"
        ],
        "documentation": [
            "check list",
            "test case",
            "test plan",
            "bug report"
        ],
        "client_server_architecture": [
            "client",
            "server",
            "database",
            "data transfer protocols",
            "status codes"
        ],
        "programs": [
            "Postman",
            "Charles",
            "Fidler",
            "Android Studio",
            "XCode",
            "Jmeter"
        ],
        "SQL": [
            "Create",
            "Delete",
            "Drop",
            "Insert Into",
            "Select",
            "Join"
        ]
    }
}`


---


**12. Отправить сразу 2 файла на внешний репозиторий.**

 `git add .
 git commit -m "Описание коммита"
 git push origin название ветки`
 
 
 ---
 
 
**13. На веб интерфейсе создать файл bug_report.json.**

 `add file
 create new file
 commit new file`
 
 
 ---
 
 
**14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

 `edit this file
 commit changes`
 
 
 ---
 
 
**15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**

 `edit this file (bug_report.json)
 commit changes`

`{
	"bug_id": 155,
	"severity": "minor",
	"priority": "medium",
	"environment": [
	   "Windows 10 Pro",
	   "Chrome 112",
	   "Firefox 112"
	   ],
	"bug_title": "Clicking on the 'Instagram' icon on the [About us] page in the footer of the website will take you to the 'Instagram Home Page' (instagram.com)",
	"STR": [
	   "Navigate to ourwebsite.com",
	   "Go to the page [About us]",
	   "Move down to the page footer",
	   "Click on the 'Instagram' icon"
	   ],
	"AR": "The 'Home Page' of Instagram opens",
	"ER": "The company's page on Instagram opens",
	"Attachment": "Link",
	"Author": "Anastasiia Chyzhykova"
 }`
 
 
 ---
 
 
**16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

 `ommit changes`
 
 
 ---
 
 
**7. Синхронизировать внешний и локальный репозиторий JSON**
 `it pull oridgin main (название ветки)`
 
 
 ---

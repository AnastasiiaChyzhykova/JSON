# JSON



**1. Create a remote repository called JSON.**

 `On GitHub push: Repositories, New, Create repository.`
 
 
 ---
 
 
**2. Clone the JSON repository to the local computer.**  

 `git clone link to repository https://github.com/AnastasiiaChyzhykova/JSON.git`
 
 
 ---
 
 
**3. Create a "new.json" file inside the JSON context.**    

`touch new.json`


---


**4. Add the file to Git.**     

 `git add new.json`
 
 
---


**5. Commit the file.**

 `git commit -m "Commit name"`
 
 
 ---
 
 
**6. Send the file to a remote GitHub repository.**    

 `git push origin main (the name of the branch where we want to put the code)`
 
 
 ---
 
 
**7. Edit the content of the "new.json" file - write information about yourself (name, age, number of pets, future desired salary). Write everything in JSON format.**  

  `cat>> new.json`  

```JSON
{
        "name": "Anastasiia",
        "surname": "Chyzhykova",
        "age": 27,
        "number_of_pets": 0,
        "salary": "1400$"
}
```


---


**8. Send changes to a remote repository.** 

```
 git add new.json,
 git commit -m "commit name",
 git push origin branch name
 ```
 
---


**9. Create a preferences.json file.**

 `touch preferences.json`
 
 
---


**10. In the preferences.json file, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in JSON format.**

 `cat>> preferences.json`

```JSON
{
	"avorite_movie ": "Harry Potter ",
	"favorite_series": "Sherlock",
	"favorite_food": "borsch",
	"favorite_season": "spring",
	"the_country_you_would_like_to_visit": "Greece"
}
```
	
	
---
	
	
**11. Create a file sklls.json, add information about skills that will be learned at the course in JSON format.**

 `cat> skills.json`

```JSON
{
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
}
```


---


**12. Send two files at once to the remote repository.**

```
 git add .
 git commit -m "commit name"
 git push origin branch name
 ```
 
 
 ---
 
 
**13. Create the bug_report.json file at the web interface.**

```
 add file,
 create new file,
 commit new file
 ```
 
 
 ---
 
 
**14. Make Commit changes (save) changes at the web interface.**

```
 edit this file,
 press the button "commit changes"
```
 
 
 ---
 
 
**15. Modify the bug_report.json file at the web interface and add the bug report in JSON format.**

`edit this file (bug_report.json)`

```JSON
{
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
 }
 ```
 
 
 ---
 
 
**16. Make Commit changes (save) changes at the web interface.**

 `press the button "commit changes"`
 
 
 ---
 
 
**17. Synchronize remote and local JSON repository.**

 `git pull oridgin main (branch name)`
 
 
 ---

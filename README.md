### :large_orange_diamond: XML
 _________________________________________________________________________________
 1. Создать внешний репозиторий c названием XML.            - [XML](https://github.com/EvgeneyKEO/XML.git)

 2. Клонировать репозиторий XML на локальный компьютер.     - `git clone https://github.com/EvgeneyKEO/XML.git`

 3. Внутри локального XML создать файл “new.xml”.           - `touch new.xml`

 4. Добавить файл под гит.                                  - `git add .`

 5. Закоммитить файл.                                       - `git commit -m "add new file"`

 6. Отправить файл на внешний GitHub репозиторий.           - `git push`

 7. Отредактировать содержание файла “new.xml” - написать 
информацию о себе (ФИО, возраст, количество
 домашних животных, будущая желаемая зарплата). 
Всё написать в формате XML.                                  - `vim new.xml ---> input data ---> esc ---> enter ":wq"`

 8. Отправить изменения на внешний репозиторий.             - `git commit -am "update file" && git push` [new.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/new.xml)

 9. Создать файл preferences.xml                            - `touch preferences.xml` 

 10 В файл preferences.xml добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
 любимое время года, сторона которую хотели бы посетить)
 в формате XML.                                              - `vim preferences.xml ---> input data ---> esc ---> enter ":wq"`

 11 Создать файл skills.xml добавить информацию о скиллах
 которые будут изучены на курсе в формате XML		      - `cat >> skills.xml ---> input data ---> ctrl + c`

 12 Сделать коммит в одну строку.                            - `git add . && git commit -m "Add new files"` 

 13 Отправить сразу 2 файла на внешний репозиторий.	      - `git push` 
								[preferences.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/preferences.xml) 
								[skills.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/skills.xml)

 14 На веб интерфейсе создать файл bug_report.xml.           - `Add file --> Create new file --> Name: bug_report.xml` 
								[bug_report.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/bug_report.xml)

 15 Сделать Commit changes (сохранить) изменения 
на веб интерфейсе.					      - `Commit new file`

 16 На веб интерфейсе модифицировать файл bug_report.xml, 
добавить баг репорт в формате XML. 		     	      - `Choose bug_report.xml --> Edit this file` 

 17 Сделать Commit changes (сохранить) 
изменения на веб интерфейсе.			      	      - `Commit changes`

 18 Синхронизировать внешний и локальный репозиторий XML.    - `git pull`

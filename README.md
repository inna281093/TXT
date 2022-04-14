1. Создать внешний репозиторий c названием TXT.
 - открываем GitHub и создаем репозиторий. Копируем ссылку на репозиторий.
 Repositories->New->Repository name->Public->Add a README file->Create repository
 Repositories->Repository name->Code->Clone

 2. Клонировать репозиторий TXT на локальный компьютер.
 - git clone (ссылка на репозиторий)

 3. Внутри локального TXT создать файл “new.txt”.
  - cd TXT
  - touch new.txt


 4. Добавить файл под гит.
 - git add new.txt

 5. Закоммитить файл.
 - git commit -m "add 1 file"

 6. Отправить файл на внешний GitHub репозиторий.
 - git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 - vim new.txt

	name: Inna Gennadyevna Boikova,
	age:28,
	pets: 1 dog Bright,
	Salary: 400$

 8. Отправить изменения на внешний репозиторий.
 - git commit -am "change file new.json"
 - git push

 9. Создать файл preferences.txt
 - touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 - vim preferences.txt
   favorite film: The Silence of the Lambs,
   favorite series: Supernatural,
   favorite food: BBQ,
   favorite season: summer,
   country: Switzerland

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 - vim sklls.txt
    skill 1: GIT,
    skill 2: Postman,
    skill 3: Charles,
    skill 4: other

 12. Сделать коммит в одну строку.
 - git add . | git commit -m "2 files"
 
 13. Отправить сразу 2 файла на внешний репозиторий.
 - git push
 
 14. На веб интерфейсе создать файл bug_report.txt.
 - add file
 - create new file 
 - commit new file
 
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  - commit changes
 
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 - edit this file 	
	Identifier:1,
  	Summary:Site layout on the first page is not recommended with layout placement,
	Descriprion:Actual result and Expected result,
	Actual result:The layout of the site on the first page does not match the layout of the application. More than 5 pixel spacing,
	Expected result:The layout of the site on the first page matches the layout when overlaying. Run up to 5 pixels.,
	For more details see attachment:https://www.screencast.com/t/hkQkQ8CeueY8,
	Steps to reproduce:1:Open website in Chrome,
	      		         2:Install and open PerfectPixel browser plugin,
              		   3:Drag the layout of the first page of the site in jpg format into the plugin window,
              		   4:Set the parameters in the plugin x=1, y=1, scale=0.24,
              		   5:Apply a layout layer to the layout of the site according to the edges of the main block,
              		   6:Hold down Shift + use arrow keys to change position by 10px,
	Severity:minor,
	Priority:low

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  - commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT
 -git pull

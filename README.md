<div align="center">

# Git Homework 2 "TXT"

</div>

 1. Создать внешний репозиторий c названием TXT.  
 `https://github.com/mranolegprivate/JSON`
 
 2. Клонировать репозиторий TXT на локальный компьютер.  
 `git clone git@github.com:mranolegprivate/TXT.git`
 
 3. Внутри локального TXT создать файл “new.txt”.  
 `touch new.txt`
 
 4. Добавить файл под гит.  
 `git add .`
 
 5. Закоммитить файл.  
 `git commit "new txt"`
 
 6. Отправить файл на внешний GitHub репозиторий.  
 `git push`
 
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
 `vim new.txt`
 ```txt
 An Oleg Romanovich
 Age - 35
 Animals - 2
 Salary - 5000$
 ```
 
 8. Отправить изменения на внешний репозиторий.  
 `git commit -am "new txt 2com"`  
 `git push`
 
 9. Создать файл preferences.txt  
 `touch preferences.txt`
 
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.  
```txt
   favorite_movie - Avatar
   favorite_series - The Mandalorian
   favorite_food - Sangepsal
   favorite_season - summer
   country_to_travel - Singapore
```

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
`vim skills.txt`  
```
   Git Linux Terminal
   Testing Theory
   Client server
   SQL
   Postman
   Charles Fiddler Sniffing
   Web Services
   DevTools
   Mobile Testing
   Web Testing
   Load testing
```

 12. Сделать коммит в одну строку.  
`git commit -am "skills"`

 13. Отправить сразу 2 файла на внешний репозиторий.  
`git push`

 14. На веб интерфейсе создать файл bug_report.txt   
 В репозитории нажать  `Add file` далее `Create new file` в поле "Name your file..." ввести `bug_report.txt`

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Нажать кнопку `[Commit new file]`

 16. На веб интерфейсе модифицировать файл `bug_report.txt`, добавить баг репорт в формате TXT.  
```bug
 ID - HW-2
 Title - What?Where?When?
 Severity - Medium
 Priority - High
 Precondition - Preparation steps
 Environment - Devices
 STR - Steps to reproduce
 ER - Expected result
 AR - Actual Result
 Attachment - link
```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 Нажать кнопку `[Commit changes]`

 18. Синхронизировать внешний и локальный репозиторий TXT  
`git pull`

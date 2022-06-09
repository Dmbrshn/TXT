# TXT
 1.  Создать внешний репозиторий c названием TXT: 
 
    На GitHub выбрать вкладку "Repositories", нажать "New", в окне "Repository name" написать "TXT", поставить галочку напротив "Add a README file", нажать "Create repository"
 2.  Клонировать репозиторий TXT на локальный компьютер: 
   
    git clone https://github.com/Dmbrshn/TXT.git
 3.  Внутри локального TXT создать файл "new.txt": 
   
    cd TXT && touch new.txt
 4.  Добавить файл под гит: 
    
    git add new.txt
 5.  Закоммитить файл: 
    
    git commit -m "new file"
 6.  Отправить файл на внешний GitHub репозиторий: 
    
    git push
 7.  Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT: 
    
    vim new.txt , i , набираем нужный текст, :wq  
 8.  Отправить изменения на внешний репозиторий:
    
    git add new.txt && git commit -m "Edit file" && git push
 9.  Создать файл preferences.txt:
    
    touch preferences.txt
 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT:
    
    vim preferences.txt , i , набираем нужный текст, :wq 
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT:
    
    touch skills.txt && vim skills.txt , i , набираем нужный текст, :wq 
 12. Отправить сразу 2 файла на внешний репозиторий:
    
    git add . && git commit -m "preferences and skills" && git push
 13. На веб интерфейсе создать файл bug_report.txt:
    
    В Репозитории "TXT" нажать "Add file" , выбрать "Create new file" , в поле "Name" написать "bug_report.txt" 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    
    Нажать "Commit new file"
 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT:
    
    В Репозитории "TXT" выбирать файл "bug_report.txt" , нажать на иконку "карандаш" , набираем текс 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
 
    Нажать "Commit changes"
 17. Синхронизировать внешний и локальный репозиторий TXT:
 
    git pull

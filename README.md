# JSON
GIT Homework 1

Для выполнения задания у вас должен быть установлен для Windows - GitBash.
Создан аккаунт в GitHub
Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.

Как отправить ДЗ на проверку.
 1. Создайте текстоовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash

`Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.`

## JSON

 4. **Создать внешний репозиторий c названием JSON.**

      `Создаем внешний репозиторий на github "JSON"`

 5. **Клонировать репозиторий JSON на локальный компьютер.**
 
     Копируем ссылку на репозиторий, заходим в локальную папку гита, прописываем в консоле

      `git clone https://github.com/ViktorTih/JSON.git`

 6. **Внутри локального JSON создать файл “new.json”.**
   
`cd JSON`
`touch new.json`

 7. **Добавить файл под гит.**

`git add .`

 8. **Закоммитить файл.**

`git commit -m "new.json"`

 9. **Отправить файл на внешний GitHub репозиторий.**

`git push`

 10. **Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**

`vim new.json`

`i`
 >{

  >"Фио":"Тихонов_Виктор_Иванович",

  >"Возраст": 44,

  >"Количество_домашних_животных": 1,

  >"Будущая_желаемая_зарплата":800

 >}

`Esc :wq`

`Enter`

 11. **Отправить изменения на внешний репозиторий.**
  
 git commit -am "add_new.json"
 git push

 12. **Создать файл preferences.json**
  === touch preferences.json
 13. **В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**
 === 
vim preferences.json
 i
 {
        "Любимый_фильм" : "Терминал",
        "Любимый_сериал" : "Шерлок",
        "Любимая_еда" : "драники, борщ, мясо",
        "Любимое_время_года" :"лето",
        "Страна_которую_хотел_бы_посетить" : "Испания"
 }
Esc :wq

14. **Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
 ===
touch skills.json
vim skills.json
 i
 {
  "skills":[
  "Git Linux Terminal",
  "Testing Theory", 
  "Client server", 
  "SQL", 
  "Postman", 
  "Charles Fiddler Sniffing", 
  "Web Services",     
  "DevTools", 
  "Mobile Testing", 
  "Web Testing", 
  "Load testing"
  ]
}
Esc :wq
 15. **Отправить сразу 2 файла на внешний репозиторий.**
  ===
git add . && git commit -am "add_preferences_skills"
git push


 16. **На веб интерфейсе создать файл bug_report.json.**
  === 
 Add file -> Create new file -> в поле в поле Name your file вводим "bug_report.json"

 17. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
  === нажать Commit new file

 18. **На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**

нажать "bug_report.json" 
нажать "Edit this file"

{
   "id" : "уникальный_номер_дефекта", 
   "severity" : "серьезность_дефекта",
   "Environment" : "окружение_на_котором_обнаружен_дефект",
   "Title" : "что?где?когда?)",
   "Steps" : "шаги_для_воспроизведения_дефекта",
   "Expected_Result" : "ожидаемый_результат",
   "Actual_Result" : "фактический_результат",
   "Attachment" : "ссылка_на_видео_или_фото_дефекта"
}

 19. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 
   нажать Commit changes

 20. **Синхронизировать внешний и локальный репозиторий JSON**
 === 
входим в папку локального репозитория "JSON"  и в terminal вводим команду git pull 

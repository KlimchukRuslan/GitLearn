# Навчальний репозиторій

## Це тестовий репозиторій для навчання роботи з Git.

### Base commands Git

**git config --global user.name "Ruslan Klimchuk"** *- налаштування файлу конфігурацій для гіт середовища*

**git config --global user.email "some_mail@gmail.com"** *- налаштування файлу конфігурацій для гіт cередовища*

**git config --global core.editor "'C:\Program Files\Sublime Text\sublime_text.exe' -w"** *- налаштування редатора коду за замовчуванням*

**git config --list --show-origin** *- файл з конфігураціями в гіт*

**git init** *- ініціалізація репо* 

**git status** *- перегляд стану(статусу "змінений, індексований, збережений") файлу*

**git add** *- додавання файлів в індексовані. (add . - додасть всі файли в індексовані)*

**git commit** *- Створення коміту з визиванням текстового редактора*

**git commit -a -m "Add second output"** *- Зміна стану файлу й закомічування його ( -а - добавляємо всі файли в директорії а потім комітимо їх \ -m - замінює текстовий редактор і дає змогу відразу написати коміт)*

**git commit - m "Some commit..."** *- коміт без використання редактора*

**git log** *- виводить список всіх комітів* 

**git show** *- вивід детальної інформації про коміт*

**git branch -m master main** *- зміна назви гілки з master в main(на 	віддаленому репозиторії основна гілка main а в локальному master)*

**git remote add origin https://github.com/KlimchukRuslan/GitLearn.git** *- підключння віддаленого репозиторію*

**git remote -v** *- вивід підключених репозиторіїв*

**git push -u origin main** *- надіслати зміни на віддалений репозиторій в origin гілку(основну на git) з локальної main.*

**git revert 862f1e6** *- відкат коміту*

**git clone https://github.com/KlimchukRuslan/GitLearn.git** *- клонує віддалений репозиторій з гіт на локальну машину*

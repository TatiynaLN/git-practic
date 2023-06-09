# git-practic

Прежде чем приступить к выполнению практического задания, убедись что выполнены следующие пункты:
Полностью просмотрен блок видеолекций
Скачен и установлен Git
Создан собственный репозиторий на GitHub*
Есть понимание, как ты будешь с ним общаться: 
через терминал, SmartGit или как-то ещё
Изучены рекомендации по подготовке к практике из данной статьи

Как избежать проблем с кодировкой
Рекомендуем для работы с текстом использовать Notepad++, Sublime Text, 
и после каждого изменения сохранять текст с кодировкой UTF-8
Notepad++: Encoding -> Encode in UTF-8.
Sublime Text: File -> Save with Encoding -> UTF-8.
После выполнения задания проверьте 
корректность кодировки следующим образов:
1. Перейти на страницу своего GitHub репозитория
2. Нажми кнопку "Commits"
Текст должен отображаться корректно

ПРАКТИЧЕСКОЕ ЗАДАНИЕ 

Практическое задание
После каждого коммита выполняйте push и в конце не удаляйте ветку feature
Так преподаватель сможет отследить выполнение всех пунктов задания 
Иначе работа не будет принята
Для выполнения задания необходимо:
Клонировать на свой локальный компьютер пустой репозиторий
Добавить в свой локальный репозиторий (прямо в master) файл Potter.txt, содержащий список книг (именно в том виде, как оно приведено ниже):

Harry Potter book
One The Philosopher's Stone (1997)
two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4etyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После добавить(push) файл Potter.txt в свой удалённый репозиторий на GitHub
Создать ветку feature, изменить в ней содержание файла Potter.txt на новое:
Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
chetyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения в ветку feature
Через master, изменить содержание файла Potter.txt на ещё один вариант:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После закоммитить (commit) изменения в ветку master и 
сделать push в удалённый репозиторий
Снова перейти в ветку feature и вмерджить в неё master
Разрешить мердж-конфликт таким образом, чтобы в ветке feature 
появился правильный вариант Potter.txt:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки feature
Изменить файл в ветке feature добавив в него «:» в конце самой 1-ой строки:

Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки feature
Через master изменить содержание файла Potter.txt на ещё один вариант:

Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4 The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

После этого закоммитить (commit) изменения ветки master
Вмерджить feature в master и обновить Potter.txt, разрешить конфликт в ветке master так, чтобы в результате получился правильный вариант текста:

Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

Залить(push) изменения ветки master в удалённый репозиторий
Перед отправкой своего решения преподавателю проверь, что после каждого коммита выполнен push и не удалена ветка feature 
Тогда преподаватель сможет проверить работу и проставить оценку

​

КАК ОТПРАВИТЬ ЗАДАНИЕ НА ПРОВЕРКУ

1.После выполнения задания, перейди к следующему блоку курса: 
"Практическое задание".

2. В части "Ответ" напиши сообщение: "Ссылка на выполненное задание", 
вставь ссылку на свой проект и нажми кнопку "Отправить".

Внутри практического задания в поле ответ напиши: "Ссылка на проект: ссылка ", 
и нажми кнопку "Отправить"
После оценки задания преподавателем, тебе на почту придет сообщение о проверке, либо дополнительные вопросы для выполнения
Не забудь пройди итоговый тест, так как оценка за прохождение курса состоит 
из средней за выполнение практического задания и тестирования
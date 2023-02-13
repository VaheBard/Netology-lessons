# Netology-lessons
>  Система контроли версией: в нашем случае git и github(конспект)


  В разработке не редко, а точнее часто, случается такое что возникает момент когда нужно вернутmся к предидущей версии программы(причем не важно насколько ранней).
Например в.1, в.2,...,в.20. Системы которые позволяют нам вернутся к болле ранним версиям проекта называются VCS(Version Control System). Одна из ключевых функций таких систем 
является то что на любом этапе разработки мы можем создавать новые версии, каждой версии присвоивая определенный номер(идентификатор), а потом по ним смтореть 
что и когда там изменилось. Такие системы дают возможность параллельно разрабатывать и потом соеденить(слить) в одну ветку, работы разных программистов. Также есть 
возможность отслеживать в истории какой автор какие изменения внес в проекте. Еще ондо из главных преимуществ таких систем является то что можно делать резервную 
копию проекта.
Одна из таких систем является git. git, это распределенная система контроли версией, это означает что система существует не только на одном компе а может существовать
на нескольких, таким образом можно организовать и параллельную и командную работу.

> Установить git можно [здесь](https://git-scm.com/).

### Прежде чем начать работу с git нам необходимо настроить его.
Открываем на нужной папке, правой кнопкой мыши Git Bash Here, откроется терминал. Тут сначала нужно ввести имя автора и его почта
```
# вводим данные автора
git config --global user.name "Authors name"
git config --global user.email "Authors email"
# для просмотра данных
git config --global user.name
git config --global user.email
```
### Следущим этапом установливаем редактор по умолчанию(для случай если мы с помощью git будем редактировать файлы)
```
git config --global core.editor nano
```

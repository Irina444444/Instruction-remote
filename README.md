## Задание для итоговой викторины.

Склонируйте, пожалуйста, этот репозиторий к себе на ПК. 
Это необходимо для прохождения итоговой викторины.

В этом репозитории несколько веток (bracnh1 и branch2), для того, чтобы видеть все ветки в своей локальной версии, вам необходимо набрать в терминале следующие команды:

 ``` git checkout branch1 ```
 
 ``` git checkout branch2 ```
 
 ``` git checkout main ```
 
Для хранения удаленных репозиториев можно использовать GitHub
GitHub представляет собой специальный сервис Microsoft для хранения архивов кодов 
Помимо GitHib существует множество других удаленных хранений, однако на данный момент GitHub  является наиболее популярным среди разработчиков
Для копирования удаленного репозитория на локальный диск используется команда git clone ....ссылка на репо
После копирования удаленного репо на локальный необходимо ввести команду cd (что означает change directory)
Затем в скопированном репозитории можно работать - вносить изменения, создавать файлы, удалять файлы и т.д. 
Для того, чтобы отправить локальный репозиторий на свой удаленный эккаунт в GitHub следует использовать команду git push
Обратите внимание - вы не можете отправить изменения к склонированному чужому репозиторию 
В данном случае командой get push я отправляю изначально скопированный чужой репо с моими правками на мой удаленный эккаунт в GitHub 

Смоделируем ситуацию, при которой я работаю с данным удаленным репо с другого компютера и у меня происходят какие изменения на данном репо на эккаунте GetHub. 

Следующий шаг, который я должна сделать - выкачать эти изменения в свой локальный репо, связанный с удаленным репо

Таким образом, изменнеия, произошедшие с репо на удаленном эккаунте в GitHub при помощи команды git pull выкачаны на локальный репозиторий
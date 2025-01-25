`useradd -m -s /bin/bash student` создает нового пользователя 

`passwd student` задаем пароль для нового пользователя

`su student` переключение на пользователя

`groupadd students` создаем новую группу студентов

`usermod -aG students student` добавляем студента в группу

`chmod 770` владелец и группа имеют права на чтение, запись и выполнение

`chown student ./dir1` изменяет владельца папки dir1 на student




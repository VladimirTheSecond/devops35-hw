#Уласовец Владимир, 28.09.23
#devops-35

Итак, мы создали файл файл .gitignore в директории terraform.

Теперь при копировании в github будут проигнорированы (не скопированы): 
локальные папки терраформ, которые хранятся на этой машине,
логи терраформ,
временные файлы, которые не нужно хранить в гите.
Файлы, которые могут содержать секреты или пароли, либо другую чувствительную информацию, которую нельзя раскрывать третьим лицам.
Файлы, которые нужны только локально и не имеют смысла вне конкретной машины.
Конфигурации cli (командной строки).
Additional text to have this file modified.

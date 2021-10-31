# devops-netologysecond line


# Игнорируем папки и все что в них вложено .terraform
** / .terraform / *

# Игнорируем файлы с данными расширениями
* .tfstate
* .tfstate. *

# Игнориуем файл логов
crash.log

# Игнорируем все файлы .tfvars
* .tfvars

# Игнорировать данные файлы

override.tf
override.tf.json
 и все файлы в наименовании которых упонминается
* _override.tf
* _override.tf.json

# Работает наоборот принужительно индексирует(для настройки исключений???)
!example_override.tf

# Игнорируем файлы 
.terraformrc
terraform.rc

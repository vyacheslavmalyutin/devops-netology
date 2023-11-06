# devops-netology
Public repo for DevOps track (Netology)

First addon

## Terraform
Создан каталог `terraform` для размещения в нем в дальнейшем материалов при изучении Terraform.  
Внутри каталога `terraform` создан файл `.gitignore` со следующими правилами исключения файлов и каталогов из индекса git:
 - любые каталоги `.terraform`, включая их содержимое;
 - файлы, оканчивающиеся на `.tfstate` или содержащие в названии `.tfstate.`;
 - файлы `crash.log` и файлы, начинающиеся на `crash.` и заканчивающиеся на `.log`;
 - файлы, оканчивающиеся на `.tfvars` или `.tfvars.json`;
 - файлы `override.tf` или `override.tf.json`, а также файлы, оканчивающиеся на `_override.tf` или `_override.tf.json`;
 - файлы `.terraformrc` или `terraform.rc`.

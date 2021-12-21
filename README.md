#игнорирование дерриктории/папки .terraform
## Local .terraform directories
**/.terraform/*

# Игнорирование файлов с  определенным расширением и его вариациями
*.tfstate
*.tfstate.*

#Игнорирование файлв crash.log
##Crash log files
crash.log 

# Игнорировать все файлы формата .tfvars
*.tfvars

# Игнорирование файлов и варианты этих файлов с определенным форматом в название
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# НЕ Игнорировать файл 
# !example_override.tf

# Включить tfplan в исключения при выполнение команды: terraform plan -out=tfplan
# example: *tfplan*
    
# Игнорирование файлов с  определенным расширением и фалй terraform.rc
.terraformrc
terraform.rc
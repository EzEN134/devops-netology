# devops-netology
Нетология (обучение).

**/.terraform/*: Игнорировать все поддиректории .terraform внутри проекта.

*.tfstate и *.tfstate.*: Игнорировать файлы состояния Terraform (.tfstate и .tfstate.*).

crash.log и crash.*.log: Игнорировать файлы журналов сбоев.

*.tfvars и *.tfvars.json: Игнорировать файлы переменных Terraform (.tfvars и .tfvars.json), которые, вероятно, содержат чувствительные данные.

override.tf, override.tf.json, *_override.tf, *_override.tf.json: Игнорировать файлы, связанные с переопределением ресурсов Terraform.

!example_override.tf: Отменить игнорирование файла example_override.tf. Этот файл будет добавлен в систему контроля версий.

*tfplan*: Игнорировать файлы планов Terraform (например, terraform plan -out=tfplan).

.terraformrc и terraform.rc: Игнорировать файлы конфигурации CLI Terraform.

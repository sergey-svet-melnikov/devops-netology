# terraform.gitignore

+ Игнорировать все папки .terraform во всех подкаталогах
+ Игнорировать все файлы с расширением tfstate и содержащие целиком tfstate между точками в имени (справа и слева от tfstate) 
+ Игнорировать все crash.log и содержащие в начале имени до точки crash и в конце имени после точки log
+ Игнорировать все файлы с расширением tfvars и tfvars.json
+ Игнорировать файл ovverride.tf, override.tf.json, все файлы имеющие в конце имени _override.tf и _override.tf.json
+ Игнорировать файлы .terraformrc и terraform.rc


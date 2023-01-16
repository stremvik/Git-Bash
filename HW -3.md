- ## 1) Определить имя папки, в которой вы находитесь:  `pwd`
- ## 2) Создать папку с именем test1: `mkdir test1`
- ## 3) Перейти в папку test1: `cd test1`
- ## 4) Создать файл 1,2 и 3 внутри каталога test1: `touch file_1.txt file_2.txt file_3.txt`
- ## 5) Проверить содержимое каталога test1: `cat file_1.txt`
- ## 6) Создать папку test2 внутри домашней директории: 
  ## `cd ..` 
  ## `mkdir test2`
  ## `ls` - проверить, что папка создалась
- ## 7) Удалить папку test2: `rmdir test2`
- ## 8) Удалить файл 2: 
  ## `cd test1` 
  ## `rm file_2.txt` 
- ## 9) Создать папку test3 и добавить в нее два файла: 
  ## `cd ..`
  ## `mkdir test3` 
  ## `cd test_3`
  ## `touch file_4.txt file_5.txt`
- ## 10)  Удалить папку test3
  ## `cd ..`
  ## `rm -R test3`
- ## 11) Создать папку test4: `mkdir test_4`
- ## 12) Переместить файлы 1 и 3 в папку test4: `mv test1/{file_1.txt,file_3.txt} test4`
- ## 13) Добавить в файл 1 три строки со словами line
   ## `cd test4` 
   ## `cat > file_1.txt`
   ## line
   ## line
   ## line
   ## `Ctrl C`
-  ## 14) Посмотреть содержимое файла 1: 
   ## `cat file_1.txt`
-  ## 15) Добавить в файл 3 три строки со словами line: 
   ## `cat > file_1.txt`
   ## line
   ## line
   ## line
   ## `Ctrl C`
 - ## 16) Просмотрите содержимое двух файлов (1 и 3) сразу: `cat file_1.txt file_3.txt`
- ## 17) Используя один из редакторов замените все строки: 
   ## `nano file_1.txt` 
   ## line
   ## offline
   ## deadline
   ## `Ctrl O`
   ## `Ctrl X`
   или
   ## `vi file_3.txt`
   ## online
   ## liner
   ## bye
   ## `Insert`
   ## `Esc`
   ## `:wq`
# Задание №2
- ## 1) Создать папку test 3: `mkdir test_3`
- ## 2) Добавить в него три файла 4, 5 и 6, в каждом из которых должно быть по 4 строки row1, row2, row3, row4:
  ## `cat > file_4.txt`
  ## row1
  ## row2
  ## row3
  ## row4 
  ## `Ctrl C`
  ## `cat > file_5.txt`
  ## row1
  ## row2
  ## row3
  ## row4 
  ## `Ctrl C`
  ## `cat > file_6.txt`
  ## row1
  ## row2
  ## row3
  ## row4 
  ## `Ctrl C`
- ## 3) Найдите строку row2 в файле 5:
  ## `grep row2 file_5.txt`
- ## 4) Найдите строку row в папке test3: `grep row *`
- ## 5) Посчитайте сколько строк с содержимым row в файле 6: `grep -c row file_6.tx`
- ## 6) Найдите файл 5 внутри папки test3: `find . -name file_5.txt`
- ## 7) Используя команду find, удалите файл 5: `find .-name "file_5.txt" -delete -print`
- ## 8) Используя команду echo, добавьте слово test в файл 4: `echo "test" >> file_4.txt`
- ## 9) Замените слово test в файле 4 на fail: 
  ## `nano file_4.txt`  
  ## заменить test  на fail
  ## `Сrtl O`
  ## `Ctrl X`
- ## 10) Добавьте в файл 4 слово test так, чтобы сохранилось        содержимое:  `cat >> file_4.txt`
  ## test 
  ## `Enter`
  ## `Сtrl C`
- ## 11) Просмотрите все процессы для юзеров не только в консоли, которые происходят в системе: `ps aux`
- ## 12) Убейте процесс 666 в консоли: `kill 666`
- ## 13) Узнайте доступность ресурса artsiomrusau.com, используя ping: `ping artsiomrusau.com`
- ## 14) Отправьте 5 пакетов на сайт artsiomrusau.com: `ping -n 5 artsiomrusau.com`
- ## 15) Используя GET и команду curl, получите информацию о зарегистрированных питомцах на https://petstore.swagger.io/: `curl https://petstore.swagger.io/v2/pet/10`


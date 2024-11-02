1. Переместиться между директориями.
`cd ..\`

2. Вывести список файлов в директории
`ls`

3. Вывести список Всех файлов в директории
`ls -a`

4. Создать папку с подпапками
`mkdir -p task1/num4`

5. Внутри папки создать файлик и записать в него что-нибудь
`echo "aboba" >> task1/num4/aboba.txt`

6. Переместить файл из одно директории в другую
`mv task1/num4/aboba.txt task1.6`

7. Скопировать файл из одной директории в другую
`cp task1.6/aboba.txt task1`

8. Переименовать файл
`mv aboba.txt abobus.txt`

9. Сравнить содержимое файла
`diff abobus.txt task1.6/aboba.txt`

10. Отсортировать содержимоей файла по возрастанию и убыванию
`sort abobus.txt`
`sort -r abobus.txt`

11. Удалить все папки и файлы.
`rm -rf task1`
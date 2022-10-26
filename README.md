# Linux-terminal-BASH-commands

В данном репозитории я указала основные команды Bash-terminal, с которыми я могу работать. Конечно же это только небольшая часть)))


1. Посмотреть где мы находимся
pwd

2. Создать папку GitBash 
mkdir GitBash

3. Сменить папку
cd путь/к/папке

4. Создать 5 папок
mkdir new{1..5}, если не нужно конкретное наименование папки, а только порядковый номер папок, то mkdir {1..5}

5. Открыть файл file.txt, папку gitbash или страницу по URL 
open file.txt
open gitbash
open https://github.com/MarinaShnyakina

6. Создать 1 файл c расширением .txt
touch file1.txt

7. Создать 3 файла с расширением .json
touch file{1..3}.json

8. Вывести списком содержание папки bash5
ls bash5

9. Выйти из папки на уровень выше
cd ../
 
10. Скопировать файл file2.txt из bash1 в bash2
cp bash1/file2.txt bash2/

11. Переместить file1.json в bash3
mv file1.json bash3

12. Найти файл по имени file5.txt
find file5.txt

13. Найти файлы, в которых содержится " tf" в названии
find *tf*

14. Удалить файл newFail2
rm newFail2

15. Удалить пустую папку TestBash5
rmdir TestBash5

16. Удалить папку TestBash3 со всем ее содержимым 
rm -R TestBash3

17. Вывести 3 первых строки из текстового файла file5.txt
head -3 путь/file5.txt

18. Вывести 2 последних строки из текстового файла file5.txt
tail -2 путь/file5.txt

19. Вывести весь текст файла file5.txt
less путь/file5.txt

20. Отображение даты и времени
date

21. Создание файла test2.txt c текстом "Hello, my friend!"
cat > test2.txt
Hello, my friend!

22. Добавление нового текста "How are you?" в текстовый файл test2.txt
cat >> test2.txt
Новый текст "How are you?" добавится к тому, что уже есть и получится:
Hello, my friend!
How are you?

23. Объединить файлы test2.txt и tf_3.txt, в один новый файл tf_10.txt
cat test2.txt tf_5.txt > tf_10.txt

24. Очистить файл tf_4.txt от содержимого без удаления самого файла
 > tf_4.txt

25. Найти строки в файлах где есть комбинация букв "sec" в текущей папке
grep -r "sec"

26. Найти все строки во всех файлах где нет комбинации "second" 
grep -r -v "second"

27. Вывести в терминал строку "Great job, Marina!!"
echo "Great job, Marina!!"

28. Очистить окно терминала
clear


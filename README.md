# Необходимо создать игрушечный интерпретатор.

## Цель - получить представление о том, как работают командные интерпретаторы.

Программа должна в бесконечном цикле считывать с stdin полный путь к
исполняемому файлу, который необходимо запустить и аргументы запуска.
Дождавшись завершения процесса необходимо вывести на stdout код его завершения.

Необходимо использовать прямые системные вызовы для порождения новых процессов,
запуска новых исполняемых файлов и получения статуса завершения системного
вызова.

Все возвращаемые значения системных вызовов должны быть проверены и в случае
обнаружения ошибок необходимо выводить текстовое описание ошибки.

На входе могут быть некорректные данные.

Дополнительные баллы - поддержка переменных окружения.

Язык имплементации - C или C++.

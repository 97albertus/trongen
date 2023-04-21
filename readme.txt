Генератор адресов для TRON, имплементация GoLang

Установка
Скачайте файл trongen в отдельную папку.
Откройте папку с файлом в терминале - cd путь/к/папке

Использование MacOS
./trongen tron --prefix=xxxx --suffix=xxx --concurrency=x

Использование Windows
trongen.exe tron --prefix=xxx --suffix=xxx --concurrency=x

prefix - символы в начале адреса, должен начинаться с латинской 'TT'
suffix - символы в конце адреса 
concurrency - количество конкурентных процессов, по умолчанию равно количеству ядер процессора

Программа возвращает .json-файл с address и private key, импортируемый в пользовательский кошелек.

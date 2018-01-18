# sysops


cd /etc/




grep idenis * - вывод всех файлов в директории /etc с именим idenis 




grep idenis * 2>/dev/null - вывод без ошибок




grep -l  idenis * 2>/dev/null  - вывод всех файлов в которых встречается idenis


grep -lR idenis * 2>/dev/null - рекурсивный вывод 



grep -ilR idenis * 2>/dev/null
 - игнорировать случаи различия

ps aux



ps aux | grep cron - выбрать cron 




ps aux | grep cron | grep -v grep  -  выбрать не совпадающие строки

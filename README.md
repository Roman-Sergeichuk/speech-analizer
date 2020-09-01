# Speech-analyzer by Roman-Sergeichuk

## Скрипт для анализа записанных телефонных разговоров.
Позволяет отличить автоответчик от человека, а также положительные ответы человека от отрицательных.
Записывает результаты обработки в лог-файл и при необходимости - в базу данных (PostgreSQL). 
## Запуск скрипта:
Для работы скрипта требуется установка ряда сторонних модулей, таких как tinkoff-voicekit-client, psycopg2 и prompt. Для их установки можно воспользоваться командой "make install".
Для запуска скрипта запустите файл "run.py".
## Демонстрация работы скрипта и SQL-запроса:
[![asciicast](https://asciinema.org/a/QUZzCel8frq8iGmecO3OF7YYs.svg)](https://asciinema.org/a/QUZzCel8frq8iGmecO3OF7YYs)
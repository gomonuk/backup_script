Этот скрипт:
1. Проходит по списку айпишников, создает папку для каждого свича по айпишнику. 
2. Проверяет доступность свича, наличие файла и папки.  
3. Сохраняет конфиг на свиче.
4. Скачивает конфиг на TFTP сервер.
5. Проверяет есть ли разница между двумя последними файлами в папке.
6. Если разница есть, то измененные строки добавляются в отчет.
7. Если разницы нет, то последний скачанный файл удаляется, таким образом в папке хранятся уникальные файлы.
8. Отчет с информацией об общей информации о процессе, и изменениями в конфиге.  

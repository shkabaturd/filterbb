# filterbb
Этому скрипту на вход подается путь к файлу конфигурации nginx,
созданному с помощью комманды "nginx -T > nginx_confi_dump".
На выходе получаем хешмапу где ключи - это названия файлов с конфигами
а значения - список всех эндпоинтов, на которые настроено проксирование.
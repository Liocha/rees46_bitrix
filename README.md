# Модуль REES46 для 1С Битрикс

## Инструкция по установке

https://rees46.ru/docs/ru/setup/cms-plugins/bitrix.html

## Как готовить обновление

1. Вносим изменения в коде.
2. В каталоге update создаем каталог с номером новой версии и кладем в него файл description.ru, где пишем, что обновилось. В кодировке windows-1251.
3. В файле install/version.php указываем новую версию модуля в соответствии с предыдущим пунктом. А также дату.
4. Создаем каталог X.Y.Z и кладем в него только измененные файлы и папки (включая install/version.php). При этом description.ru кладется просто в корень.
5. Архивируем каталог в X.Y.Z.zip.
6. Загружаем файл в этом разделе: http://partners.1c-bitrix.ru/personal/modules/edit_update_module.php?module=mk.rees46

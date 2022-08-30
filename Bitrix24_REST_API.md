# Пример разбор API запросов для Bitrix24

### Документация к Bitrix24 https://dev.1c-bitrix.ru/rest_help/rest_sum/index.php

## Авторизация и получение Access Token (использовал вебхук)

Для получения вебхука использую демо тариф на 15 дней

![Demo tarif](./bitrix_img/DemoTarif.png)

после этого перехожу на вкладку разработчик->другое->входящий вебхук

Здесь в настройках можно искать нужные методы но я смотрел в документации потому что из доступных методов есть устаревшие

Верхняя или нижня строка Url и есть вебхук с продолжением енд пойнтов

![WebHuk example](./bitrix_img/WebHuk1.png)

нужно задать права а затем сохранить(без прав у вас не будет доступа к задачам)

![WebHuk2 example](./bitrix_img/WebHuk2.png)

После этого запускаю Advanced REST client и с помощью запроса вытаскиваю определённую задачу

![GetTask example](./bitrix_img/GetTask.png)

Завожу новую задачу:

![AddTask example](./bitrix_img/PutTask.png)

Как мы видим задача создалась:

![AddTask example](./bitrix_img/PutTask2.png)

Изменяю существующую задачу:

![UpdTask example](./bitrix_img/UpdateTask.png)

Удаляю задачу:

![DelTask example](./bitrix_img/DelTask.png)

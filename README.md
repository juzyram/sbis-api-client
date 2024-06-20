# Описание
sbis-api-client — это Python-библиотека, предназначенная для удобной работы с API СБИС. Она предоставляет простой и интуитивно понятный интерфейс для взаимодействия с различными сервисами СБИС, такими как документооборот, бухгалтерия, CRM и другие.

# Возможности (в разработке)
* Подключение и аутентификация к API СБИС (✔️)
* Отправка запросов к различным сервисам СБИС (❌)
* Получение и обработка данных в удобном формате (❌)
* Работа с документами, контрагентами, задачами и другими объектами (❌)
* Поддержка всех доступных методов API СБИС (❌)

# Установка
Вы можете установить sbis-api-client через pip:
```sh
pip install sbis-api-client
```

# Пример кода
```py
from sbis_api_client import SbisClient
# Все данные являются тестовыми
client = SbisClient(
        clientId="7760676789310629",
        secret="RWHREDMVWJDHYFZO0CM83MHF",
        secretKey="B9PT47e2j3JGwsswHAzHaU5ssyzoqHsIYFHLjtZYQhlqV8U7eIkF5VIYluyrGwugVv7g1dWRcbSnoCzk10gq961GdzfpUD7INYZiS0wR8K1lrbVwkMjvqi"
    )

client.authenticate() # Авторизация
client.data()  # Данные клиента
client.logout() # Выход
```

# Лицензия
Этот проект распространяется под лицензией MIT. Подробности см. в файле LICENSE.

# Обратная связь
Если у вас возникли вопросы или предложения по улучшению библиотеки, пожалуйста, откройте issue в репозитории на GitHub или свяжитесь с автором (discord: @juzyram)

# Получение информации об артикуле 

Метод возвращает список производителей и наименования товара по его артикулу. Получение данных выполняется с сервера Кроссов Docpart. Для одного артикула может быть возвращено несколько вариантов производителей.

Операция: **КаталогПроизводителиПоАртикулу**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|


# Получение списка категорий каталога

Метод возвращает список категорий каталога. Если передано значение параметра parent_id, то будут возвращены только категории, для которых категория с идентфиикатором parent_id является родительской. 

Операция: **КаталогПолучитьКатегории**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|


# Добавление новой категории каталога

Операция создает новые категории каталога. Можно создавать нексколько категорий, передав массив в параметре data.

Операция: **КаталогДобавитьКатегории**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|

# Получение списка товаров категории

Метод возвращает список товаров категории каталога. Если передано значение параметра category_id, то будут возвращены только товары из указанной категории. 

Операция: **КаталогПолучитьТовары**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|


# Добавление товара в категорию

Метод добавляет новые товары в категорию каталога

Операция: **ТоварыДобавить**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|


# Изменение данных карточки товара

Метод выполняет изменение данных товара

Операция: **ТоварыИзменить**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|

# Удаление товара с сайта

Метод выполняет полное удаление всей информации о товаре с сайта без возможности восстановления. 

Операция: **ТоварыУдалить**

Параметры запроса:

|**Параметр** |**Пример заполнения** |**Описание** |
|---|---|---|
|ПараметрыЗапроса *|Структура|Структура отбора для получения заказов|
|НастройкиПодключения|Структура, Ссылка на элемент справочника имНастройкиПодключенияСайтов|Настройки подключения к сайту|

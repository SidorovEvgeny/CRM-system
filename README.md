# CRM-system
Евгений Сидоров

Для запуска CRM:<br>
1. запустите сервер из папки `crm-backend` командой `node index.js`, обязательно в отдельной папке.<br>
2. в папке `crm-frontend` запустите установку зависимостей командой `npm i`<br>
3. запустите сборку командой `gulp`<br>

Это примитивная CRM для учета клиентов в компании,<br>
основной функционал которой это:<br>
- добавление нового клиента в базу данных<br>
- изменение персональных данных клиента<br>
- удаление клиента из базы<br>
- сортировка клиентов<br>
- поиск клиентов<br>

При добавлении нового клиента можно заполнить следующие поля:<br>
- имя<br>
- фамилия<br>
- отчество<br>
- номер телефона<br>
- почта<br>
- facebook<br>
- vk<br>
- другое<br>
(всего контактов должно быть не более 10 штук)<br>

При изменении данных существующего клиента можно редактировать теже данные, что и при добавлении.<br>

При удалении клиента всплывает модальное окно с подтверждением удаления.<br>

При сохранении нового клиента на сервер, ему присваевается:<br>
- ID<br> 
- дата и время создания новой записи<br>
- дата и время внесения последних изменений<br>

Так же в таблице реализована сортировка клиентов,<br> 
по возрастанию, убыванию при нажатии в шапке таблицы на соответствующие значения:<br>
- id<br>
- фио<br>
- дате и времени создания новой записи<br>
- дате и времени внесения последних изменений<br>

При поиске по списку клиентов,<br>
поиск происходит по всем данным указанным у клиента,<br>
при совпадении данных подходящий клиент отображается в таблице.<br>

Контактные данные заменены соответствующими изображениями,<br> 
при наведении на которые появляется подсказка с контактом.

В этом проекте основной упор делался на JS, меньше уделялось внимания визуальной части.

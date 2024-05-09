1. ОПИСАНИЕ
   
Веб-сервер, который реализует функциональность простейшего планировщика задач. Это аналог TODO-листа. 
Планировщик хранит задачи, каждая из них содержит дату дедлайна и заголовок с комментарием. Задачи могут повторяться по заданному правилу: например, ежегодно, через какое-то количество дней, в определённые дни месяца или недели. Если отметить такую задачу как выполненную, она переносится на следующую дату в соответствии с правилом. Обычные задачи при выполнении будут просто удаляться. 

3. ОСОБЕННОСТИ
   
API содержит следующие операции:
- добавить задачу;
- получить список задач;
- удалить задачу;
- получить параметры задачи;
- изменить параметры задачи;
- отметить задачу как выполненную.

3. ОСОБЫЕ УКАЗАНИЯ
   
- В директории `tests` находятся тесты для проверки реализованного API.
- Директория `web` содержит файлы фронтенда.

4. ЗАПУСК ПРИЛОЖЕНИЯ
   
- Склонируйте приложение;
- Запустите приложение go run main.go.
- Для запуска сервера перейдите на http://localhost:7540/

5. ЛИЦЕНЗИЯ

Этот проект лицензирован согласно условиям лицензии MIT. См. файл LICENSE для получения дополнительной информации.

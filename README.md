# Открытый формат портфеля инвестора и трейдера

Формат позволяет импортировать портфель из одного приложения учета инвестиций в другое.

Перечень проектов, поддерживающих открытый формат:
1. [JAL](https://github.com/titov-vv/jal)
2. [Izi-invest](https://izi-invest.ru/)
3. [Investbook](https://github.com/spacious-team/investbook)

Если вы хотите поддерживать импорт и экспорт данных в открытом формате:
1. Реализуйте экспорт и импорт.
2. Проверьте экспортируемые данные на соответствие требованиям схемы [json-schema.json](json-schema.json), 
   при необходимости создайте Pull Request на доработку схемы.
3. Создайте Pull Request для добавления в список из предыдущего абзаца ссылки на свое приложение.

# Валидация данных
Для валидации вашего json объекта с данными используйте, например, онлайн ресурс https://json-schema.hyperjump.io
или https://jschon.dev и схему из файла [json-schema.json](json-schema.json).

Пример данных с комментариями представлен в файле [data-example.json](data-example.json).

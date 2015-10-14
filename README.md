#ТЗ
####1. Введение 
1.1. Наименование программы: KinoKino

1.2. Назначение и область применения программы: Программа предназначена для получения информации о фильмах/сериалах и оповещений о обновлении информации о них

####2. Требования к программе 
2.1. Требования к функциональным характеристикам программы

Программа должна обеспечить выполнение следующих функций:
Поиск фильма/сериала;
Отображение названия, даты выхода (даты выхода новых серий);
Добавление фильма/сериала в список отслеживания;
Просмотр списка отслеживания;
Удаление фильма/сериала из списка отслеживания;
Отображение недавно появившихся (месяц) фильмов/сериалов;
Уведомление пользователя о изменениях информации о фильмах/сериалах из списка отслеживания;
Получение списка фильмов/сериалов с конкретным актёром;
Наличие справки о программе с перечисление функций и методов их использования;

Добавление фильма/сериала в базу данных вручную;
Добавление недавно появившегося фильма/сериала автоматически;
Обновление базы данных фильмов/сериалов каждый день в определённое время;
Хранение и управление клиентской и серверной базами данных;

База данных клиента содержит поля: id фильма/сериала, название;

База данных сервера содержит поля: id фильма/сериала, название, тип(фильм или сериал), ссылка на страницу, дата последнего обновления, список основных актёров;

для типа фильм: дата выхода;

для типа сериал: дата выхода, кол-во сезонов, кол-во вышедших серий;




2.2. Отказы программы из-за некорректных действий пользователя:
Пользователь имеет право только получать информацию и добавлять фильмы/сериалы из базы данных в список отслеживания

####3. Условия эксплуатации программы 

3.1. Требования к информационным структурам и методам решения:
База данных сервера работает под управлением MySQL
База данных пользователя(список отслеживаемых фильмов/сериалов) работает под управлением SQLite

3.2. Требования к исходным кодам и языкам программирования 
Программа пишется на языке Java EE7

####4. Стадии и этапы разработки программы
4.1. Стадии разработки программы:
Разработка технического задания;
Рабочее проектирование

4.2. Этапы разработки программы:
На этапе разработки должно быть выполнено: разработка программы, тестирование программы

4.3. Содержание работ по этапам 

На этапе разработки технического задания должны быть выполнены перечисленные ниже работы: 
1. постановка задачи; 
2. определение и уточнение требований к техническим средствам; 
3. определение требований к программе; 
4. определение стадий, этапов и сроков разработки программы;
5. согласование и утверждение технического задания. 
На этапе разработки программы должна быть выполнена работа по программированию (кодированию) и отладке программы. 

На этапе испытаний программы должны быть выполнены перечисленные ниже виды работ: 
1. разработка, согласование и утверждение и методики испытаний; 
2. проведение испытаний; 
3. корректировка программы по результатам испытаний. 

####5. Порядок контроля и приемки 
5.1. Виды испытаний 
????


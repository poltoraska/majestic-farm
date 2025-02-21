# Курсовая работа по РКИС

Группа 3834:

Жидких Игорь - Backend;  
Каратеева Дарья - База данных;  
Савина Екатерина - Телеграм бот;  
Якушев Евгений - Frontend.

# Описание работы:

Тема: Проектирование и разработка программного модуля информационной системы «Фермерское хозяйство» (учет пчел, меда и цветов для меда).

# Структура страниц сайта:

 1. Главная страница - краткий обзор текущего состояния фермы (пчелы, мед, цветы для меда, отчёты)
Что отображается:

✅ Статистика по количеству пчелиных семей и посевных площадей.  
✅ Графики (например, объем собранного меда, прирост пчелиных семей).  
✅ Кнопки навигации к основным разделам.

Элементы интерфейса:

🔹 Меню навигации (слева или сверху).  
🔹 Карточки с ключевыми показателями (напр. "Пчелиных семей: 50", "Цветов для меда: 20 га").  
🔹 Диаграммы и графики (например, прирост пчел и урожайность медовых цветов).

 2. Раздел "Учёт пчел" - управление данными о пчелиных семьях (добавление, удаление и редактирование)
Что отображается:

✅ Таблица с пчелиными семьями (ID, кол-во пчел, здоровье, медовый сбор).  
✅ Фильтр по состоянию здоровья, количеству пчел.  
✅ Кнопки «Добавить», «Редактировать», «Удалить».

Элементы интерфейса:

🔹 Таблица с пчелиными семьями (с возможностью сортировки и поиска).  
🔹 Фильтры (по состоянию здоровья, количеству пчел).  
🔹 Кнопка «Добавить пчелиную семью» (открывает форму).  
❓ Кнопка «Подробнее» (переход на детальную страницу семьи).

3. Раздел "Учёт меда" - ведение учёта собранного меда.
Что отображается:

✅ Таблица с объемом собранного меда (ID, тип меда, объем, дата сбора).  
✅ Фильтры по типу меда, дате сбора, объему.  
✅ Кнопки «Добавить», «Редактировать», «Удалить».

Элементы интерфейса:

🔹 Таблица с медом (с возможностью сортировки и поиска).  
🔹 График урожайности меда по сезонам.  
🔹 Кнопка «Добавить мед» (открывает форму).  
❓ Детальная страница меда (показаны параметры, история сборов).

4. Раздел "Учёт цветов для меда" - ведение учёта посевных культур, выращиваемых для меда.
Что отображается:

✅ Таблица с цветами (ID, вид, площадь, дата посева, дата цветения).  
✅ Фильтры по виду цветов, площади, дате посева.  
✅ Кнопки «Добавить», «Редактировать», «Удалить».

Элементы интерфейса:

🔹 Таблица с посевами (с возможностью сортировки и поиска).  
🔹 График цветения и сбора меда по культурам.  
🔹 Кнопка «Добавить цветок» (открывает форму).  
❓ Детальная страница культуры (показаны параметры, история изменений).

5. Раздел "Отчёты" - анализ данных по пчелиным семьям, меду и урожайности цветов.
Что отображается:

✅ Динамика роста пчелиных семей.  
✅ Графики по собранному меду за сезоны.  
✅ Таблицы с анализом затрат и прибыли.

Элементы интерфейса:

❓ Диаграммы и графики (например, сбор меда по месяцам).  
❓ Возможность выбора периода анализа (фильтры).  
❓ Сравнительный анализ сезонов.  
❓ Кнопка «Скачать отчет» (PDF, Excel).

6. Авторизация и профиль пользователя.
Что отображается:

✅ Поля ввода логина и пароля.  
✅ Кнопка «Войти».  
✅ Возможность смены пароля в профиле.

Элементы интерфейса:

🔹 Страница входа (форма с логином/паролем).  
🔹 Профиль пользователя (имя, роль, смена пароля).  
🔹 Выход из системы.

# Цветовая схема и стилистика:

Цветовая гамма:

1. Натуральные цвета из библиотеки Google Material You (желтый, золотистый, зеленый, коричневый) - ассоциация с пчелами, медом и сельским хозяйством.
2. Фон светлого цвета, заголовки и кнопки оранжевые или зеленые.

Шрифты:

1. Простые, легко читаемые (например, Roboto, Open Sans).
2. Размер текста: заголовки 16-20px, текст 14px.

Иконки: Google Material You.

# Frontend разработка.

Задачи:

1. Создать и настроить проект (React, HTML, CSS и JS);
2. Сверстать главные страницы;
3. Сделать адаптивный дизайн;
4. Добавить интерактивные элементы и анимации.

# Backend разработка.

Задачи:

1. Обеспечить обработку запросов от фронтенда и телеграм бота;
2. Обработать бизнес логику (Вычисление продуктивности пчелиных семей, сбора меда и посевов цветов для меда);
3. Реализовать взаимодействие с базой данных для учёта меда, пчел и цветов.

# Разработка базы данных.

Задачи:

1. Разработать СУБД;
2. Продумать структуру таблиц (пчелиные семьи, мед, цветы для меда, пользователи, отчеты);
3. Написать SQL-запросы (Обновление, удаление, создание данных);
4. Реализовать связи между таблицами;
5. Распределить роли и пользователей.

# Разработка телеграм бота.

Задачи:

1. Разработать бота для внесения в базу данных новых пчелиных семей и удаление существующих;
2. Запрос данных для добавления включает: количество пчел, здоровье, медовый сбор;
3. Запрос данных для удаления включает ID пчелиной семьи;
4. Настроить авторизацию пользователей.

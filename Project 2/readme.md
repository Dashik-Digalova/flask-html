
       
### Часть 2

Создайте модель Преподаватель

- Установите и подключите SQLAlchemy
- Опишите модель для преподавателя
- Проверьте, что первичный ключ, типы и констрейнты в порядке

Создайте модель Бронирование

- Опишите модель Бронирование
– Свяжите модель отношениями с Преподавателем (one to many)
- Проверьте, что первичный ключ, типы и констрейнты в порядке

Создайте модель Заявка на подбор

- Опишите модель 
- Проверьте, что первичный ключ, типы и констрейнты в порядке


Импортируйте данные

- Напишите скрипт, который запишет мок-данные из JSON в базу
- Запишите данные
- Проверьте, что все заимпортировалось
- Выкиньте файл, он вам больше не понадобится

Доработайте роут преподавателя

- Замените получение данных из файла на выполнение запроса в БД
– Когда преподавателя не существует, выбросьте 404


Доработайте роут цели, например, "для переезда"
    
– получите преподавателей с помощью запроса с фильтром и сортировкой


Доработайте роут главной

- Замените получение данных из файла на выполнение запроса в БД


Доработайте роут и страницу бронирования с обратной связью

– Перепишите форму с помощью WFT Forms
– Валидируйте форму: все поля должны быть заполнены
– Замените запись в файла на запись в базу

Доработайте роут и страницу заявки на подбор

– Перепишите форму с помощью WFT Forms
– Валидируйте форму: все поля должны быть заполнены
– Замените запись в файла на запись в базу


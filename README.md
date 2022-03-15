# DEAD-Hotels
#   Системная и программная инженерия💚💚💚💚💚💚<img align="left" alt="HTML5" width="26" src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" />
# Практическая работа №1
## Тема: Web-приложение "Бронирование отелей"
### Роли:
| ФИО           | Роль         |Смайлик|
| ------------- |--------------|:---:| 
|Евгений Анваржонов|Разработчик, Тимлид|👨🏽‍💻|
|Данил Семенов|Тестировщик|👻|
|Дмитрий Миронов|Разработчик|👾|
|Артём Марданян|Технический писатель, Аналитик|🤖|


# Практическая работа №2
## Назначение системы
##### Мы все время от времени путешествуем, не важно - командировки, семейная поездка или же просто так распорядилась судьба. Приезжая в другое место понадобится жилье, но его нужно выбирать заранее. Звонить по объявлениям найденым на заборе никому не хочется, поэтому мы все идем в интернет. Множество сложных и непонятных сервисов найденых в интернете приводят вас в отчаяние? Наше Web-Приложение поможет вам. 
##### Оно инуитивно понятно пользователю, легко в эксплуатировании с современным интерфейсом.
##### В нем предоставлены следующие функции и функционал
  - Регистрация / авторизация
  - Разделение пользователей по ролям, предоставление для каждой роли разного уровня доступа к системе
  - Поиск отелей в нужном вам городе
  - Бронирование
  - Выбор времени приезда и отъезда
  - Редактирование выбранного отеля их владельцами

### Таблица 1 - User Story
| Кто           | Что хочет?         | С какой целью?|
| ------------- |:------------------:| --------------|
| посетитель    | зарегистрироваться на сайте | забронировать номер |
| посетитель    | редактировать профиль | смены личной информации на актуальную |
| посетитель    | редактировать пароль | из-за риска потери доступа к аккаунту |
| посетитель    | интуитивно-понятный интерфейс | проще было ориентироваться по сайту |
| посетитель    | кнопку поднятия к началу страницы | получить доступ к навигации сайта |
| посетитель    | иметь вкладу "понравившиеся" | хранить список любимых отелей |
| посетитель    | возможность добавлять отели в черный список | не отвлекали в будущем из-за отсутствия моей заинтересованности в них |
| посетитель | не регистрироваться на сайт | просто просмотреть возможные варианты |
| администратор  | зарегистрироваться на сайте | редактировать профиль отеля |
| администратор  | минималистичный интерфейс | проще было ориентироваться по сайту |

## Функциональные требования 
 - У пользователя должна быть возможность просматривать отели без регистрации;
 - Должна быть отдельная кнопка Регистрации/Входа;
 - Должен быть добавлен интерфейс с выбором Даты
 - Должен быть добавлен интерфейс с выбором Количества человек
 - Должен быть добавлен интерфейс с выбором города
 - Возможность добавления отелей во вкладку понравившиеся
 - Должна быть кнопка поднятия наверх, если пользователь пролистал далеко вниз страницу
 - Должен быть добавлен личный кабинет пользователя, где он может поменять свою аватарку, пароль, логин, email;
 - Добавление отелей в черный список
 - Отправление email сообщения пользователю после успешного бронирования отеля.

### Таблица 2 - Перечень функциональных тербований на основе User Story
| Кто           | Что хочет?         | С какой целью?|Функциональное требование|
| ------------- |:------------------:| --------------|-------------------------|
| посетитель    | зарегистрироваться на сайте | забронировать номер |выбор даты, выбор отеля, выбор количества людей|
| посетитель    | редактировать профиль | смены личной информации на актуальную |смена ФИО, смена фото, смена контактных данных|
| посетитель    | редактировать пароль | из-за риска потери доступа к аккаунту |смена пароля|
| посетитель    | интуитивно-понятный интерфейс | проще было ориентироваться по сайту |минималистичный понятный дизайн|
| посетитель    | кнопку поднятия к началу страницы | получить доступ к навигации сайта |быстрая прокрутка к началу страницы|
| посетитель    | иметь вкладу "понравившиеся" | хранить список любимых отелей |добаление желанных отелей с отдельный список|
| посетитель    | возможность добавлять отели в черный список | не отвлекали в будущем из-за отсутствия моей заинтересованности в них |скрытие нежелательных отелей|
| администратор  | зарегистрироваться на сайте | редактировать профиль отеля |добавление отелей, редактирование отелей, смена уровня доступа|
| администратор  | минималистичный интерфейс | проще было ориентироваться по сайту |минималистичный понятный дизайн|
| посетитель без регистрации| не регистрироваться на сайт | просто просмотреть возможные варианты |просмотр информации с ограниченным функционалом|

Далее можно увидеть скриншот распределенные задачи проекта в Jira Software:
### Рисунок 1 - распледеленные задачи
![image](https://user-images.githubusercontent.com/70753243/158281515-4a6db08e-e4d1-4a48-9422-bedf18f46c39.png)

# Практическая работа №3
## Целевая аудитория:
-пол: неважен
-возраст: от 25
-доход: выше среднего(от 50000 рублей)
-интересы: отдых, развлечения, работа

## Портрет пользователя
1) #### Николай, 27 лет.  
Место проживания: Санкт-Петербург.  
Семейное положение, количество детей: женат, 1 ребенок.  
Сфера занятости и уровень зарплаты: малый бизнес, 150 тысяч рублей.  
Должность, связанные с ней проблемы: руководитель собственной компании по производству бюджетной мебели.  
Потребности, желания, фобии: в связи с недавней женитьбой хочет отправится в отпуск с семьей, подальше от шумных мест, уровень отеля не ниже 3 звезд  

2) #### Евгенийй, 48 лет.  
Место проживания: Москва.  
Семейное положение, количество детей: женат, детей нет.  
Сфера занятости и уровень зарплаты: автосервис, 100 тысяч рублей.  
Должность, связанные с ней проблемы: слесарь, постоянная усталость.  
Потребности, желания, фобии: из-за тяжелой работы нуждается в отдыхе, отель обязательно с бюджетными номерами, но со спа  

3) #### Ольга, 35 лет.  
Место проживания: Киев.  
Семейное положение, количество детей: разведена, 2 ребенка.  
Сфера занятости и уровень зарплаты: малый бизнес, 130 тысяч рублей.  
Должность, связанные с ней проблемы: руководитель собственного салона красоты  
Потребности, желания, фобии: из-за постоянной работы периодически хочет отдохнуть у моря, желательно с нянькой для детей, боится высоты(не выше 4 этажа)  

4) #### Парье, 23 года  
Место проживания: Париж.  
Семейное положение, количество детей: не женат, детей нет.  
Сфера занятости и уровень зарплаты: модельное агенство, 250 тысяч рублей.  
Должность, связанные с ней проблемы: главный фотограф  
Потребности, желания, фобии: частые разъезды, может отменить бронирование в любой момент, уровень отеля не ниже 4 звезд, хочет самые верхние этажы с красивым видом  

### Рисунок 2 - Use case
![Image alt](https://github.com/DEAD-Hotels/DEAD-Hotels/blob/main/use_case_dead_hotels.png)

### Рисунок 3 - диаграмма последовательности пользователя
![image](https://user-images.githubusercontent.com/70753243/158282550-9c6d756b-7d35-466e-b353-cb594db7a5d0.png)

### Рисунок 3 - диаграмма последовательности администратора
![image](https://user-images.githubusercontent.com/70753243/158282826-c9711371-0fe9-4006-adf3-7b38e0fe911e.png)


# Практическая работа №4
### Таблица 3 - нефункциональные требования
| Тип требования           | Содержание требования         |
| ------------- |:------------------|
| Технические ограничения    | Веб-приложение должно  быть кроссбраузерным и одинаково функционировать в всех популярных браузерах: Google Chrome, Mozilla Firefox, Opera, Yandex.Браузер, Microsoft Edge, Safari | 
| Технические ограничения    | Веб-приложение должно  быть адаптировано под разные размеры окна браузера и под мобильные устройства | 
|Технические ограничения|Пользователь может пользоваться полным функционалом веб-приложения только после регистрации|
|Производительность|Полное резервное копирование базы данных клиентов должно производиться не менее чем 1 раз в неделю|
|Производительность|Snapshot базы данных заказов должен производиться не менее чем 1 раз в сутки|
|Производительность|При регистрации в личном кабинете пользователь будет ожидать 3 мс|
|Масштабируемость|При нагрузке в 10 запросов в секунду система должна выдавать пользователю ответ на запрос в пределах 5 с|
|Масштабируемость|При нагрузке в 1000 запросов будет подключаться дополнительный сервер|
|Масштабируемость|Максимальное количество записей пользователей в базе данных без потери производительности должно быть не более 5000|
|Надежность|Приложение должно иметь время uptime в год 99%|
|Надежность|Сайт должен быть доступен для пользователей из России 98% времени каждый месяц в рабочие часы|
|Надежность|Время на устранение критических сбоев – не более 20 минут в рабочие дни|
|Безопасность|Для хеширования пароля необходимо использовать алгоритм SHA3|
|Безопасность|Для защиты от злоумышленников и SQL инъекции будет использована надстройка над PreparedStatement- Hibernate|
|Безопасность|Для защиты от ботов используем re-captcha|
|Локализация|Веб-приложение должно адаптироваться под местный язык, местную валюту, местное законодательство|
|Локализация|Веб-приложение должно адаптироваться под местную валюту|
|Локализация|Веб-приложение должно адаптироваться под местное законодательство|
|Локализация|Формат даты при бронировании отеля должен соответствовать местному региону|

### Таблица 4 - матрица требований
| №           | Требования         | Суть |Автор|Ссылки|Критерий проверки|
| ------------- |:------------------:| --------------| --------------| --------------|-------------------------|
|1|Веб-приложение|||||
| 1.1    | Регистрация пользователя | “Приложение должно иметь функцию регистрации нового пользователя" |Миронов Д.С.||Регистрация нового пользователя|
|1.2|Авторизация пользователя| “Приложение должно иметь функцию авторизации пользователя"|Миронов Д.С.||Авторизация зарегистрированного пользователя в приложении|
|1.3|Услуга “бронирование номера”|“Приложение должно иметь возможность предоставления пользователю услуги бронирования номера в отеле”|Марданян А.С.||Бронирование номера|
|1.4|Услуга “редактирование профиля” |“Приложение должно иметь возможность предоставления пользователю услуги редактирования профиля”|Марданян А.С.||Изменение профиля|
|1.5|Услуга “редактирование пароля”|“Приложение должно иметь возможность предоставления пользователю услуги редактирования пароля”|Семёнов Д.Ю.||Изменение пароля|
|1.6|Отдельный раздел “понравившиеся”|“Приложение должно позволять пользователю сохранять любимые отели”|Анваржонов Ж.||Сохранение отеля|
|1.7|Услуга “добавление черный список”|“Приложение должно позволять пользователю скрывать нежелательные отели”|Марданян А.С.||Скрытие отеля|
|1.8||Услуга “бронирование номера”|“Приложение должно позволять пользователю бронировать номера”|Анваржонов Ж.||Сохранение брони|
|1.9|Услуга “бронирование номера с определенным числом людей”|“Приложение должно позволять пользователю бронировать номера с желаемым количеством людей”|Миронов Д.С.||Выбор количества людей|
|1.10|Услуга “бронирование номера в определенный день”|“Приложение должно позволять пользователю бронировать номера на определенную дату”|Семёнов Д.Ю.||Выбор даты|
|2|Веб-интерфейс|||||
|2.1|Авторизация пользователя| “Приложение должно иметь функцию авторизации пользователя"|Миронов Д.С.||Авторизация зарегистрированного пользователя в приложении|
|2.2|Авторизация пользователя| “Приложение должно иметь функцию авторизации пользователя"|Миронов Д.С.||Авторизация зарегистрированного пользователя в приложении|
|2.3|Услуга “бронирование номера”|“Приложение должно иметь возможность предоставления пользователю услуги бронирования номера в отеле”|Марданян А.С.||Бронирование номера|
|2.4|Услуга “редактирование профиля” |“Приложение должно иметь возможность предоставления пользователю услуги редактирования профиля”|Марданян А.С.||Изменение профиля|
|2.5|Услуга “редактирование пароля”|“Приложение должно иметь возможность предоставления пользователю услуги редактирования пароля”|Семёнов Д.Ю.||Изменение пароля|
|2.6|Отдельный раздел “понравившиеся”|“Приложение должно позволять пользователю сохранять любимые отели”|Анваржонов Ж.||Сохранение отеля|
|2.7|Услуга “добавление черный список”|“Приложение должно позволять пользователю скрывать нежелательные отели”|Марданян А.С.||Скрытие отеля|
|2.8||Услуга “бронирование номера”|“Приложение должно позволять пользователю бронировать номера”|Анваржонов Ж.||Сохранение брони|
|2.9|Услуга “бронирование номера с определенным числом людей”|“Приложение должно позволять пользователю бронировать номера с желаемым количеством людей”|Миронов Д.С.||Выбор количества людей|
|2.10|Услуга “бронирование номера в определенный день”|“Приложение должно позволять пользователю бронировать номера на определенную дату”|Марданян А.С.||Выбор даты|
|2.11|Возможность прокрутки к началу страницы|“Приложение должно позволять пользователю прокручивать страницу к самому началу”|Семёнов Д.Ю.||Прокрутка к началу страницы|
|2.12|Интуитивно-понятный интерфейс|||||
|3|Веб-приложение для администратора|||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||





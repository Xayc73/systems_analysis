# Нулевой урок

 ## Знакомство с требованиями к проекту



**Первый делом пробегаюсь по требованиям, задаю вопросы, выписываю заинтересовавшие моменты**

[US-010] что значит "автоматически попадают в систему"? О чем можно попросить помощи?
[US-030] Что такое проваленная задача? Задача, на которую исполнитель не пришел, или клиент не подписал отчет.
"Статусы задачи может менять только клиент." Почему это ставит Клиент?
Оплата вперед? Нет, в конце недели, но нужны данные оплаты
[US-040] "За каждые 10к скидка увеличивается на 1%" Это от 20К? От чего скидка? Падает стоимость услуг?
Откуда берутся матчеры (воркера)? - подают заявку
[US-070] Приложение? Есть ли ещё вебверсия или ещё потребители? Что за отчет и в каком формате?
[US-081] Интересное замечание про DDOS, и ожидаемое 1к заявок в день
[US-090] Есть менеджеры на платформе. Есть тесты для воркеров. Воркеру назначается индивидуальный список тестов
[US-100] Есть характеристики и прочая инфа у воркеров, после тестов.
[US-101] Что-то про код (типа ДНК) из характеристик для воркера, но странно, что нет уникальности. Зачем тогда он?
[US-110] Заказ проваливается автоматически, если воркер не пришел. А не "клиент" проставляет, как в US-030
Как узнать, что он пришел? - Он не нажал кнопку из US-070
Тут должен быть какой-то отслеживатель, что кнопку не нажали в нужное время
[US-111] "за созданную копию клиент опять платит по новой". В результате провала из US-110 тоже?
[US-112] Вообще не понял пункт
[US-120] Назначенные услуги: активные (в ожидании), завершенные, отмененные. Кажется не хватает "в работе" и не понятно, что с проваленными
[US-130] Для списка услуг должно быть доп указание, какие расходники будут необходимы
[US-140] Есть сотрудники отдела расходников, которые видят все активные услуги и расходники к ним.
Нужен отдельный статус для расходников активной услуги, выдано/нет
[US-150] Поштучное получение печенья под клиента. Интеграция с внешней системой подрядчика. Отправлять инфу по заказчику, который приобрел услугу.
Когда отправлять? Не испортится ли печенье? Успеет ли его забрать воркер со склада?
[US-160] У клиента должен быть номер телефона, чтобы ему звонить
[US-170] Есть менеджеры отдел по изучению качества работы. Им доступен только отмененные и проваленные услсги
[US-180] Есть форма для каждой отмененной или проваленной услуге
[US-190] Обработчик на оплату сумм за неделю. В какой момент проверяется способ оплаты?Что если оплата не может быть произведена?
Есть инвойсы (выплаты)
[US-200] Интеграция с внешним сервисом перевода денег
Есть штрафы для каждого воркера? Кто назначает? За каждую провальную задачу 40единиц
[US-220] Плюс по страничке для клиента и воркера
[US-240] Какой менеджер может зачислить деньги воркеру? Это отдельный инвойс? Мы получается должны выводить в интерфейсе деньги за заказ и такой приход. Кажется надо сохранять, вдруг ещё повышение ставок там будет на неделе
[US-250] Есть ставка для каждого нового заказа. Откуда и куда деньги?
"Ставки могут делать только менеджеры, которых будет не больше 15 голов" У которых? Что такое гол?
[US-251] Как дать возможность самим деньги делить? Что ещё за механизм такой?
Как деньги разработчикам перевести?
[US-260] Так автоматически распределяются или сами менеджеры из US-251?
[US-262] Как это в серой зоне у менеджера на бумажке? Зачем тогда это вообще?)
[US-270] "Все нотификации отправляются только на почту.". Серьезно?) Я бы поставил под сомнение
[US-271] "уведомления по каждому шагу". Нужен список шагов
[US-274] "После успешной или неуспешной оплаты также необходимо отправлять нотификацию со статусом оплаты для клиентов.". Хотя, это не отвечает, что делать при неуспехе

*Общие пожелания по системе*
-   Бизнесу необходим низкий ТТМ (Time To Market), чтобы конкурировать на рынке.
-   Общая нагрузка на систему не будет превышать 10 заказов в день и 100 клиентов. Воркеров будет около 20 котов.
-   Для бизнеса критично проверять новые гипотезы по отсеву котов и изменять уже существующие с максимальной скоростью и надёжностью."
Сюда же вынесу
[US-081] Интересное замечание про DDOS, и ожидаемое 1к заявок в день на трудоустройство воркеров

Что есть на платформе?
[US-090] Есть менеджеры на платформе. Есть тесты для воркеров. Воркеру назначается индивидуальный список тестов
[US-100] Есть характеристики и прочая инфа у воркеров, после тестов.
[US-140] Есть сотрудники отдела расходников, которые видят все активные услуги и расходники к ним.
[US-140] Нужен отдельный статус для расходников активной услуги, выдано/нет
[US-150] Поштучное получение печенья под клиента. Интеграция с внешней системой подрядчика. Отправлять инфу по заказчику, который приобрел услугу
[US-160] У клиента должен быть номер телефона, чтобы ему звонить по контролю качества
[US-170] Есть менеджеры, отдел по изучению качества работы. Им доступны только отмененные и проваленные услуги
[US-180] Есть форма для каждой отмененной или проваленной услуге
[US-190] Есть инвойсы (выплаты)
[US-200] Интеграция с внешним сервисом перевода денег
[US-220] Плюс по страничке для клиента и воркера за что у них списались или начислились деньги.
[US-240] Возможно какая-то отдельная сущность для начислений от менеджера. Хотя может и пихнуть это в инвойс.
[US-271] Кажется есть логируемые ивенты, для которых создаются оповещения



**Вынесу отдельно моменты, на которые мне удалось ответить из требований, а на какие - нет**
Часто, при получении ответа на вопрос, появляются ещё вопросы или размышления. Введу заметки:
С тегом [П] - предположение, как я понял
C тегом [ПИ] - предложение изменения
Отвеченные:
1. [US-010] "Кнопкой «запросить помощь»" По контексту - это запросить новую услугу
2. [US-030] Что такое проваленная задача? Задача, на которую исполнитель не пришел, или клиент не подписал отчет.
[П] Как понять, что клиент не подписал отчет? Воркер не прислал фотографию
[ПИ] А что, если на фотографии муть? Надо бы сделать галочку клиенту, чтобы он в приложении галочку ставил о закрытии заказа. А воркер бы просто добавлял фото. *Попробовать найти в тексте*
3. [US-030] "Статусы задачи может менять только клиент". Почему это ставит Клиент? Учитывая статусы (выполненная, отменённая, проваленная), может быть действительно это логичнее делать клиенту. Согласовывается с моим [ПИ]
4. [US-030] "Каждая выполненная или отменённая задача должна быть оплачена пользователем в полном объёме". Оплата вперед? Нет, в конце недели [US-190]
[П] Нужны данные для оплаты
5. [US-040] Откуда берутся воркеры? - подают заявку и проходят отбор [US-080]
6. [US-070] Что за отчет и в каком формате? Кажется, нам не важно. Его дают в отделе расходников [US-130], заполняется вручную, а нам нужна только фотография [US-030]
7. [US-110] Заказ проваливается автоматически, если воркер не пришел. В US-030 этот статус проставляет клиент. Так как же?
[П] Клиент сможет провалить заказ, только если он пришел в разряд "активных", т.е. воркер указал, что он пришел
8. [US-110] Как узнать, что воркер пришел? - Он нажал кнопку из US-070
[П] Тут должен быть какой-то отслеживатель, что кнопку не нажали в нужное время
9. [US-120] Какие статусы могут быть у услуги? Активные (в ожидании), завершенные, отмененные, проваленные
[П] Кажется не хватает "в работе"
10. [US-130] Где взять список расходников для услуги?
[П} Для списка услуг должно быть доп указание, какие расходники будут необходимы
11. [US-200] Есть штрафы для каждого воркера? Кто назначает? За каждую провальную задачу 40единиц
12.

Неотвеченные:
13. [US-040] "За каждые 10к скидка увеличивается на 1%" Это от 20К? От чего скидка? Падает стоимость услуг?
14. [US-070] Приложение? Есть ли ещё вебверсия или ещё потребители?
15. [US-101] Что-то про код (типа ДНК) из характеристик для воркера, но странно, что нет уникальности. Зачем тогда он?
16. [US-111] "за созданную копию клиент опять платит по новой". В результате провала из US-110 тоже?
17. [US-112] Вообще не понял пункт
18. [US-150] Когда отправлять заявку на печенье? Не испортится ли печенье? Успеет ли его забрать воркер со склада перед заказом?
19. [US-190] Обработчик на оплату сумм за неделю. В какой момент проверяется способ оплаты?Что если оплата не может быть произведена?
20. [US-250] Есть ставка для каждого нового заказа. Откуда и куда деньги? На бумаге?
21. [US-250]  "Ставки могут делать только менеджеры, которых будет не больше 15 голов" У которых? Что такое гол?
22. Как вообще работают ставки? Ведь пункты [US-250], [US-260], [US-261] противоречат друг другу

**Общее задание**
 - Смириться с абсурдом системы, которую придётся анализировать. Прочитать требования
 - Создайте описание системы, которое уйдёт разработчикам и по которому они будут писать код. Это описание должно быть описано так, как вы видите систему сейчас, до старта обучения. Не заморачивайтесь сильно с проработкой, не бойтесь ошибиться — мы это делаем, чтобы вы в конце обучения сравнили «было» и «стало».

**Описание должно состоять из:**
- Структуры системы
- Описания, почему были выбраны те или иные решения


**Мои комментарии после анализа требований**
Итак, у меня как оказалось много вопросов о том, как должно работать. Много корнер кейсов, которые можно опускать для создания общего решения. Много я хочу переделать на нормальный лад, но видимо, этого делать не нужно и смириться
По разделу "Общие пожелания по системе"
а) "Общая нагрузка на систему не будет превышать 10 заказов в день и 100 клиентов. Воркеров будет около 20 котов." и сюда же "Ожидаемое 1к заявок в день на трудоустройство воркеров"
Цифры кажутся чуть странными. Поскольку кажется воркеры будут простаивать с таким кол-вом задач в день. Обычно кол-во воркеров меньше, чем кол-во выполняемых задач. Да и в 10 задач со 100 клиентов я тоже не верю, хотя хз. Может их будет больше
С такими цифрами кажется, что хватит и любого монолита и не зачем делать микросервисы.
Чтобы не было "DDOS", надо делать либо какой-то RateLimiter, либо пользоваться прям специальными сервисами "защиты от DDOS"
б) "Бизнесу необходим низкий ТТМ (Time To Market), чтобы конкурировать на рынке."
Когда проект небольшой, то намного быстрее работать над одним проектом не теряя время на межсервисное деление. Когда команды начнут быть не в контексте друг друга, тогда пора будет в микросервисы
в) "Для бизнеса критично проверять новые гипотезы по отсеву котов и изменять уже существующие с максимальной скоростью и надёжностью."
Видимо было бы неплохо завести АБ-тестирование в систему, чтобы уметь "проверять" их теории. Ну и нужны метрики, кажется. А значит тут сервис по хранению и отображению метрик.

Итак, это система, которой пользуются клиенты, воркеры, менеджеры отдела качества, менеджеры трудоустройства и сотрудники отдела обеспечения.
Система - монолит
Система имеет две платформы - это веб (не точно) и приложение
Система имеет модули:
1. Найма воркеров
2. Поиска доступных услуг?
3. Матчинга исполнителей
4. Проведения заказа по флоу?
5. Проведения оплат
6. Отправки оповещений

Использование внутренних доп сервисов:
1. БД
2. АБ тестирование
3. Аналитика для проверки гипотез
4. API Gateway с возможностями rate-limits
Возможно кэширование, но хз, масштаб мал

Есть взаимодействие с внешними сервисами, а именно:
1. Сервис подрядчика по приготовлению печенья
2. Сервис процессинга платежей
3. Сервис отправки писем (возможный)
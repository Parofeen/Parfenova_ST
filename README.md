# Parfenova_ST
# Отчет о лабораторных работах
# студентка группы [ИДБ-18-08](https://github.com/Parofeen/Parfenova_ST/wiki) Парфенова А.С.

<details> 
  <summary><b> Лабораторные работы 1-3 </b></summary>
      
## Лабораторная 1

Создание диаграммы прецедентов и диаграммы IDF0 для индивидуального проекта.

Диаграмма IDF0.
![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE.png)

[Текст для создания диаграммы классов.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE_2.3.txt)

Диаграмма классов.
![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE_2.png)

[Текст для создания диаграммы прецедентов.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE_2.4.txt)

Диаграмма прецедентов.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE_3.png)


[Ссылка на модель, выполненную в программе RAMUS.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%9B%D0%B0%D0%B11/%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%BB%D0%B5%D0%B3%D0%BE.rsf)

## Лабораторная 2

Определение подсистемы и надсистемы.

Диаграмма IDF0.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/01_A0.png)

Сотрудник с помощью средств для работы выполняет заказ гостя по рецепту из продуктов в определенные часы работы, используя кухонное оборудование и соблюдая нормы САНПИНа, регламент.

Декомпозиция.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/02_A0.png)

**Блок А1:** Сотрудник с помощью средств для работы принимает заказ гостя в определенные часы работы, соблюдая нормы САНПИНа, регламент и передает его на приготовление.

**Блок А2:** Сотрудник готовит заказ с помощью кухонного оборудования из продуктов и полуфабрикатов по определенному рецепту в определенные часы работы с соблюдением норм САНПИНа, регламента, после чего блюдо подается. 

**Блок А3:** Сотрудник с помощью средств для работы подает готовое блюдо гостю в определенные часы работы, соблюдая нормы САНПИНа, регламент,также сотрудник предварительно проверяет на соответствие готовое блюдо и ранее сделанный заказ, после чего гость расплачивается и на выходе мы получаем оплату и выполненный заказ.

Диаграмма потоков (DFD) в блоке "Принятие заказа".

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/03_A1.png)

Сотрудник оформляет заказ в специальной форме, в которых он может косвенно взаимодействовать с базами данных сотрудников и заказов. Шаблон формы оформления заказов создаётся в в определенные часы работы, соблюдая нормы САНПИНа, регламент, заполняя форму данными заказа гостя. После оформления сотрудник сможет закрыть заказ, если это потребуется, а доступ к списку позволяет проверить правильность выполнения заказа.

Диаграмма прецедентов.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80_%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.png)

[Текст для создания диаграммы прецедентов.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80_%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.txt)


[Ссылка на модель, выполненную в программе RAMUS.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B12/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%80%D0%B5%D1%81%D1%82%D0%BE%D1%80%D0%B0%D0%BD%D0%B0.rsf)

## Лабораторная 3

Определение способов существования информации.

Диаграмма DFD.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/DFD%20(A3).png)

Сотрудник с помощью средства для работы открывает форму заказа, заполняет его информацией о номере стола, после чего (через какое-то время или сразу) заполняет заказ информацией о блюдах из БД: Меню. После заполнения автоматически обновляется БД: Заказы. 

Информация из заполненного заказа (блюда, стол, сотрудник, общая сумма заказа) передается в форму оплаты, где проверяется соответствие приготовленного и заказанного гостем, после чего происходит оплата и обновление информации о выполненности заказа в БД. 

Диаграмма последовательностей. 

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B01.png)

На диаграмме отражена работа функционального блока "Форма заказа": успешный процесс создания записи в БД.

[Текст для создания диаграммы.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B01.txt)

ER-диаграмма.

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B02.png)

Заказ- запись в таблице Заказы в базе данных, которая относится к информационным потокам. 

Атрибуты заказа: ID, Номер стола, Официант.

[Текст для создания диаграммы.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B02.txt)


[Ссылка на модель, выполненную в программе RAMUS.](https://github.com/Parofeen/Parfenova_ST/blob/main/%D0%BB%D0%B0%D0%B13/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%80%D0%B5%D1%81%D1%82%D0%BE%D1%80%D0%B0%D0%BD%D0%B0.rsf)

</details>

<details> 
  <summary><b> Лабораторные работы 4-6 </b></summary>

### Задачи
  
Открытые задачи

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D1%80%D0%B8%D1%81%D1%83%D0%BD%D0%BA%D0%B8/3.jpg)
  
Закрытые задачи

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D1%80%D0%B8%D1%81%D1%83%D0%BD%D0%BA%D0%B8/1.jpg)

### Канбан-доска

![](https://github.com/Parofeen/Parfenova_ST/blob/main/%D1%80%D0%B8%D1%81%D1%83%D0%BD%D0%BA%D0%B8/2.jpg)

### Наименование: Разработка программного модуля, преобразующего растровое изображение в ASCII-рисунок.
|Роль|Задача|Зависимость|Плановая оценка трудозатрат|Фактическая оценка трудозатрат|Фамилия|
|--|--|--|--|--|--|
|РП (Владелец продукта)|Регистрация участников проекта|1 ч|30 мин|Козарезов|
|РП (Владелец продукта)|Определить направление для разработки проекта|Регистрация участников проекта|1 ч|30 мин|Козарезов|
|РП (Владелец продукта)|Создание общего репозитория (добавление участников)|Регистрация участников проекта|30 мин|30 мин|Козарезов|
|РП (Владелец продукта)|Отчет Деловая игра (семинар 3-4)|Регистрация участников проекта|1 ч 30 мин|1 ч 30 мин|Козарезов|
|РП (Владелец продукта)|Формирование документации|1 ч 30 мин|2 ч|Козарезов|
|РП (Владелец продукта)|Отчет Деловая игра (лр 4)|Отчет Деловая игра (семинар 3-4)|1 ч|1 ч|Козарезов|
|РП (Владелец продукта)|Отчет Деловая игра (лр 5)|Отчет Деловая игра (лр 4)|1 ч|1 ч|Козарезов|
|РП (Владелец продукта)|Присутствие на собраниях|Проведение stand-up совещания|7 собраний|7 собраний|Козарезов|
|СП (Аналитик)|Написание системных требований|Формирование документации|2 ч|2 ч 30 мин|Крупенко|
|НИ (Архитектор)|Обсуждение с программистом архитектуры проекта|Присутствие на собраниях|1 ч|1 ч 30 мин|Салип|
|НИ (Архитектор)|Обсуждение с тестировщиком метода тестирования|Присутствие на собраниях|1 ч|Салип|
|НИ (Архитектор)|Разбиение задачи на подзадачи|Формирование документации|2 ч|1 ч 30 мин|Салип|
|НИ (Архитектор)|Присутствие на собраниях|Проведение stand-up совещания	7 собраний|7 собраний|Салип|
|КО (Тех.писатель)|Написание пользовательской документации|Формирование документации|4 ч|3 ч|Парфенова|
|КО (Тех.писатель)|Проверка покрытия документацией возможных потребностей пользователя|Формирование документации|4 ч|Парфенова|
|ВН (Дизайнер)|Разработка дизайна страниц, форм|Написание требований дизайнера|4 ч|4 ч 30 мин|Жикина|
|ВН (Дизайнер)|Присутствие на собрании|Проведение stand-up совещания|7 собраний|5 собрания|Жикина|
|ВН (Дизайнер)|Написание требований дизайнера|Написание системных требований|2 ч|2 ч 30 мин|Жикина|
|АД (Мастер)|Проведение stand-up совещания|1 ч 30 мин|1 ч 30 мин|Петруша|
|АД (Мастер)|Присутствие на собраниях|Проведение stand-up совещания|7 собраний|6 собраний|Петруша|
|БА (Тестировщик)|Тестирование системы|4 ч|Мавлоназаров|
|БА (Тестировщик)|Написание тест-кейсов	Тестирование системы|4 ч|Мавлоназаров|
|ПП (Программист)|Описание архитектуры|2 ч|2 ч|Крючков|
|ПП (Программист)|Подключение Firebase|Описание архитектуры|4 ч|4 ч|Крючков|
|ПП (Программист)|Разработка входа/регистрации|Разработка дизайна страниц, форм|6 ч|8 ч|Крючков|
|ПП (Программист)|Разработка страницы заметок|Разработка дизайна страниц, форм|6 ч|Крючков|
|ПП (Программист)|Присутствие на собрании|Проведение stand-up совещания|7 собраний|7 собрания|Крючков|

## Лабораторная 4

### Основной поток (main flow)
|Участник|Действие (activity)|Ожидаемый результат|
|--|--|--|
|КО (Тех.писатель)|Изучает функции приложения|Список функций, для которых необходимо документирование|
|БА (Тестировщик)|Проводит различные тесты|Список подзадач с именами тестов|
|ВН (Дизайнер)|Разрабатывает требования к дизайну приложения|Список требований к дизайну приложения|

### Исключения и альтернативы (main flow)
|Условие (риск)|Последствия|Реакция|
|--|--|--|
|Структура документации не соотвествует требованиям|Изучение возможных структур для пользовательской документации|Наиболее подходящая структура|
|Неточность документации из-за внесенных изменений в приложение|Проверка изменений|Документация в соответствии с исправлениями\доработками|
|Трудность восприятия пользователей|Использование в документации формализированного языка|Документация формализирована|

## Лабораторная 5
  
### Основной поток (main flow)
|Участник|Действие (activity)|Ожидаемый результат|
|--|--|--|
|КО (Тех.писатель)|Составление документации|Готовая документация для пользователей|
|БА (Тестировщик)|Проведение тестирования|Успешное прохождение тестов|
|ВН (Дизайнер)|Создание макета интерфейса|Макет интерфейса|

### Исключения и альтернативы (main flow)
|Условие (риск)|Последствия|Реакция|
|--|--|--|
|Изменение функций приложения|Изменение документации|Тестирование и изучение новых функций|
|Ошибка при проведении тестирования|Неточность прохождения теста|Переработка теста|
|Непрохождение тестирования|Ошибка в работе приложения|Передача результатов программисту|

## Лабораторная 6

### Основной поток (main flow)
|Участник|Действие (activity)|Ожидаемый результат|
|--|--|--|
|КО (Тех.писатель)|Проверка документации|Проверенная документация готовая к использованию|
|БА (Тестировщик)|Анализ результатов тестов|Отчет о проведении тестирования|
|ВН (Дизайнер)|Проверка дизайна приложения|Корректность дизайн приложения|

### Исключения и альтернативы (main flow)
|Условие (риск)|Последствия|Реакция|
|--|--|--|
|Нереалистичность макета|Невозможность программной реализации макета|Создание нового макета|
|Сложность восприятия дизайна приложения пользователем|Отказ пользователя от использоавания приложения|Корректировка дизайна|
|Муки творчества|Задержка в создании макета|Употребить ромашковый чай|
  
</details>

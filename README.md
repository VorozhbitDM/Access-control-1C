<p align="center"> 
<a href="https://ibb.co/nnwtLRp"><img src="https://i.ibb.co/s6gzVt7/123-transformed-1.png" alt="123-transformed-1" border="0"></a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/8.3-Yellow?style=plastic&logoColor=Yellow&label=1C&color=FFD700">
<img src="https://img.shields.io/badge/%D0%91%D0%A1%D0%9F-v3.1%2B-red?style=plastic&color=red"> 
<img src="https://img.shields.io/badge/release-v4.1-32CD32?style=plastic&color=1E90FF"> 
</p>

<p align="center">
<img src="https://img.shields.io/badge/KA_2.4%2F2.5_%7C_ERP_2.5_%7C_%D0%A3%D0%A2_11.4%20-Yellow?style=plastic&logo=adguard&logoColor=Yellow&label=tested&color=FFD700">
</p>

Обработка представляет собой набор инструментов для анализа и интерактивного управления правами доступа. Это не отчет, содержащий сводную информацию, а средство для непосредственного взаимодействия, предназначенное для решения задач в реальном времени.

Документация предоставляет полное описание функционала программы **Анализ и контроль доступа**. Используйте ее в качестве руководства для эффективного администрирования прав доступа в системе. Данная программа обеспечивает простоту настройки, мониторинга и анализа прав, а также автоматизацию ряда операций. 

[![link](https://img.shields.io/badge/Download-v4.1-Grey?style=for-the-badge&logo=github&labelColor=696969&color=1E90FF)](https://github.com/VorozhbitDM/Access-control-1C/raw/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D0%98%D0%9A%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8C%D0%94%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0_4.1%20release.epf) 

_______________________________________________________________________________________________________________________________
*(02.07.2024)*

💡 **Новое в версии 4.1:** 

- [x] Добавлен парсер запросов. <details><summary> Подробнее </summary> Полезная функция, когда у пользователя не выполняется запрос, и далеко не очевидно, на какую таблицу у него нет прав. Парсер позволит проанализировать таблицы, к которым запрос может обращаться и сразу отобразит, есть ли у пользователя данное право. 
  По умолчанию используется упрощенный режим, для вывода прав "Чтение" (для отчетов) и "Просмотр" (для проблем с динамическими списками). <img src="https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/a95e238a-1377-4668-9cec-105419a7d4e3">
При отключении упрощенного режима - открываются детальные настройки по отображению необходимых прав доступа для каждого объекта метаданных.

</details>

- [x] Добавлена проверка дополнительных прав в анализе связей объекта. <details><summary> Подробнее </summary> <img src="https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/bbc014f7-3597-4034-8caa-80ec1c5e91e0">

</details>

- [x] Изменена форма справки. <details><summary> Подробнее </summary> <img src="https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/c7feb7fb-e8a1-45e0-a7d5-0460c2e9058b">
</details>

- [x] Исправлены найденные ошибки.

_______________________________________________________________________________________________________________________________
### 📫 Как связаться со мной
[![tg](https://img.shields.io/badge/telegram-blue?style=plastic&logo=telegram&color=blue)](https://t.me/qiqtpp) [![gmail](https://img.shields.io/badge/gmail-Grey?style=plastic&logo=gmail&color=grey)](mailto:denqiqtp@gmail.com)

_______________________________________________________________________________________________________________________________

# 📑 Оглавление
   1. [Внешний вид программы](#внешний-вид-программы)
   2. [Основные возможности](#основные-возможности)
       1. [Выбор пользователя](#выбор-пользователя)
       2. [Выбор роли](#выбор-роли)
       3. [Выбор объекта метаданных](#выбор-объекта-метаданных)
   3. [Примеры анализа прав](#примеры-анализа-прав-пользователя)
       1. [Первый вариант](#первый-вариант)
       2. [Альтернативный пример](#альтернативный-пример)
   4. [Описание функций контекстного меню таблиц](#описание-функций-контекстного-меню-таблиц)
       1. [Группы доступа](#группы-доступа)
       2. [Профили групп доступа](#профили-групп-доступа)
       3. [Роли](#роли)
   5. [Дополнительный функционал](#дополнительный-функционал)
       1. [Сравнение ролей](#сравнение-ролей)
       2. [Запуск сеанса под пользователем](#запуск-сеанса-под-пользователем)
       3. [Мониторинг пользователя, основные показатели](#мониторинг-пользователя-основные-показатели)
       4. [Дополнительный функционал формы мониторинга](#дополнительный-функционал-формы-мониторинга)
       5. [Копирование / Сравнение](#копирование--сравнение)
       6. [Управление настройками пользователей](#управление-настройками-пользователей)
       7. [История назначения прав](#история-назначения-прав)
       8. [Автоматический поиск ошибок пользователей](#автоматический-поиск-ошибок-пользователей)
       9. [Настройки программы](#настройки-программы)
  6. [Заключение](#заключение)
  7. [Минимальные требования](#минимальные-требования)
  8. [Функционал в разработке](#функционал-в-разработке)
_______________________________________________________________________________________________________________________________

# Внешний вид программы:
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/ecbe3e5b-afd8-4b54-88e1-99b8bf7694f4)

________________________________________________________________________________________________________________________________

# Основные возможности:
  
  ## Выбор пользователя:
  
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/9ff855ba-e16e-406b-8380-1c36a834a095)

  +	Информация о наличии у пользователя выбранной роли, его участии в профиле и группе. 
  +	Визуализация связи пользователя с ролью, группой или профилем.
  +	Интерактивное взаимодействие с механизмами управления правами.
  +	После выбора пользователя отобразится кнопка, открывающая меню функций работы с пользователем.
    
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/7074550e-9a73-4900-aadb-d979bd8ac610)
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/3befa5a6-f4b1-4792-aadd-7878f4d45a97)

  ## Выбор роли: 

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/efb56629-e691-4f4b-b5f3-d9f4219006cb)

  +	Формирование дерева метаданных с отбором по объектам, на которые назначена выбранная роль.
  +	Улучшенная визуализация связей ролей с объектами.


  ## Выбор объекта метаданных:

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/d2e02f2c-c8b0-4ede-bfd6-d8530644d27e)

  +	Обзор ролей, профилей и групп доступа, связанных с выбранным объектом.
  +	Управление текущими правами доступа.
  +	Возможность комбинирования всех трех вариантов фильтров для достижения требуемого результата.
  +	Динамическое построение таблицы ролей с учетом выбранного объекта метаданных для актуальности информации.

________________________________________________________________________________________________________________________________
# Примеры анализа прав пользователя:

## Первый вариант

Программа предлагает начать работу с выбора пользователя, роли или объекта метаданных:

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/30df21b3-e0e1-4283-b77c-eb152b03da39)

После выбора пользователя, будет предложено выбрать объект метаданных:

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/88ad3578-866b-4874-b35d-ba35bfc0c8d2)

В результате видим все сформированные таблицы, которые показывают подробную информацию

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/db28cb31-726b-4943-be55-19548c52ce0a)

Чтобы добавить пользователя в группу, ПКМ по группе – «Включить в группу»

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/c598bab2-587e-45b7-8b6c-a5db02be2955)

Если фокус будет на группе, в которой пользователь уже состоит – отобразится кнопка «Исключить из группы»

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/e3434d2d-459a-4483-9e24-8c5d4c0aaf23)


## Альтернативный пример:

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/2506093f-c965-405c-8630-45d6e942d7e3)

Для демонстрации примера, мы выбрали пользователя и указали роль, после чего сформировалось дерево с 8 объектами, на которые назначена эта роль. После выбора интересующего объекта – формируется таблица с ролями, которые принадлежат этому объекту (имя объекта также отображается над таблицей ролей). После выбора роли, формируются таблицы групп доступа, ограничений доступа и профилей групп доступа. Флаги вначале строк означают, что пользователь состоит в группе доступа «Менеджеры по закупкам» и т.д. При выборе другой роли – таблицы, которые ниже будут переформированы.

________________________________________________________________________________________________________________________________

# Описание функций контекстного меню таблиц:

## Группы доступа:

  +	Просмотр списка пользователей в группе.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/b7d605b0-8af3-44bb-ba6b-f9284ceb129d) ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/c9f37f2c-b212-42db-b567-aeddfe44e511)

  +	Включение или исключение пользователя из группы.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/af8a528c-b40b-4ba6-928e-3a4a3fc7caf3)

  +	Открытие списка всех групп.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/61ab76d0-fe94-4983-aedd-6f18c604a60a)

  + Создание новой группы доступа (текущий пользователь будет автоматически указан в таблице «Участники группы», 
            будет открыт элемент на этапе его создания, для указания дополнительных данных, останется только его записать).

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/add0c6ee-513f-4b4e-8185-3870da6ead7d)


  ## Профили групп доступа:
  
  + Просмотр списка ролей в профиле.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/68e734d6-0edc-42fe-834c-4e98ad2b893a) ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/cf12b9b5-db7e-4b05-aed1-cfb5576b6830)

  + Конструктор создания нового профиля с возможностью копирования текущего профиля и исключением ненужных ролей.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/4a56cba3-c51b-4fbd-9dc1-2ac8232f0160) ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/654fb760-0919-4871-8651-b1f28dfcbb1d)

  + Создание нового профиля (текущая роль будет автоматически выбрана в таблице «Разрешенные действия», объект 
            не будет записан, предоставив возможность скорректировать данные под свои задачи).

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/8d009ef6-2c49-4bfd-98c3-bb12435cec34)


 ## Роли:

  + Просмотр списка пользователей с выбранной ролью.

  + Создание профиля и группы доступа, их связывание (если выбран пользователь – автоматически добавится в группу доступа, 
            объекты будут созданы и записаны автоматически).
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/e55e8a3b-c0a3-4f3f-bc25-9078b7fadf7e) ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/e3c57eb3-407e-449d-a3c1-3e2166650cce)


## Ограничения доступа:

  + Редактирование шаблона ограничений.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/b82474eb-1c9c-4a57-a22b-26c06a5e541f)

  + Добавление организации пользователя в шаблон (для КА и ЕРП).


## Дерево метаданных:

  + Подробный анализ ссылочной связи объекта с другими, включая владельцев, основания, движения, 
            измерения, ресурсы, реквизиты и регистраторы в зависимости от типа объекта, 
  с визуализацией наличия права «чтение» у пользователя на каждый объект.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/17c8b690-9457-42d9-8b0f-f559c1d85aa3)

_______________________________________________________________________________________________________________________________________________

# Дополнительный функционал

  ## Сравнение ролей
   
  + Построение таблицы по всем объектам метаданных, включающим выбранные роли.
  + Отображение суммирования прав доступа по всем ролям сравнения.
  + Позволяет проводить более глубокий анализ и сопоставление различий в правах доступа.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/5c1f4aa8-dc7d-4468-a440-7ed680cee16f)

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/c6615b85-606c-460c-9ea7-b220ca6625ad)



  ## Запуск сеанса под пользователем

  + Запуск сеанса под выбранным пользователем.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/b96db1ab-937d-4520-a30c-f99682998c56)

    
  + Пароль пользователя остается неизменным.
   
  ## Мониторинг пользователя, основные показатели

  + Отображение времени начала запуска сеанса пользователя.
  + Статус пользователя (онлайн/оффлайн).
  + Имя ПК, вид приложения, IP-адрес.
  + Дата последней активности, пользователь ОС, дата разрешения входа в 1С, почта.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/2b00a8cf-a822-4882-af51-e3c9f5031745)

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/e2208d5d-6daa-4d38-854b-38398e4f89b5)


   ## Дополнительный функционал формы мониторинга

  + Завершение сеанса пользователя.
  + Открытие журнала регистрации с отбором по выбранному пользователю.
  + Просмотр списка всех сеансов.
  + Открытие формы с датами запрета изменения данных с отбором по выбранному пользователю.
    
  ## Копирование / Сравнение

  + Полностью скопировать все права от одного пользователя другому, указав источник и приемника прав.
  + Сравнение прав двух пользователей с отображением различий по ролям, группам и профилям.
  + Формирование таблицы с источниками прав по совпадению организации и/или должности пользователя (для КА и ЕРП).


![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/ea3f555f-bf4e-40b0-9842-0e337ca51f76)


  ## Управление настройками пользователей

  + Максимально подробная детализация всех настроек пользователя.
  + Возможность очистки, сохранения и загрузки каждой из настроек.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/197ab749-2d83-4d5b-ba41-c5360dff04c5)


  ## История назначения прав
   
  + Подробная информация о назначении/исключении пользователей в различные группы доступа.
  + Фиксация истории работает только при выполнении вышеперечисленных действий через саму обработку.


![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/9afa1edd-fb13-4af2-ac46-84d568e6f532)


![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/ea51e1ce-2294-4117-b3aa-724e30161555)


  ## Автоматический поиск ошибок пользователей

  + Возможность перенести в основную форму пользователя и таблицу ошибки для дальнейшего анализа.
  + Форма автоматического поиска ошибок содержит информацию о времени возникновения, пользователе и таблице ошибки.
  + Подробный текст описания ошибки из журнала регистрации.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/30ab72f0-b995-4884-85e6-4b3b0cb06e8f)

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/d404cdd1-0d53-4276-a4ce-d9f3f60ccdda)


Результат сканирования (также кнопка открытия таблицы ошибок) отображается иконкой в основном окне программы.
 
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/887d37d9-dde2-4ef6-8ac9-b488a0b904e0)


Если есть ошибки, то увидим соответствующую иконку: ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/4ffa754f-20fc-4a96-9b0d-de336636df75)

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/a2553ae5-24d9-4717-9979-dfd71e2660b0)


 ## Настройки программы
   
  + Отключение предупреждений об опасных действиях.
  + Сворачивание таблицы профилей групп доступа при открытии формы.
  + Использование механизма автоматического поиска ошибок прав доступа.
  + Настройка периода поиска ошибок и автоматическое открытие окна с ошибками при открытии обработки.

![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/eb22ee4f-9c35-4400-8180-aa1d64321a55)

  + Фильтр отображаемых объектов в дереве метаданных.
  
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/417f034c-425f-40dc-846b-fa2c731b46ee)

  + Отображение организации и должности выбранного пользователя на основной форме обработки (для КА и ЕРП).
  > [!NOTE]
  > *В разработке*
  > + При использовании терминального режима работы пользователей, на главной странице обработке станет доступна функция очистки кэша выбранного пользователя в 1 клик.
> ![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/45fa9c4a-b102-4a58-8732-28bbf7cf0bbc)

  + Служебные функции для пересчета регистров и обновления зависимостей.
  
![image](https://github.com/VorozhbitDM/Access-control-1C/assets/170056560/78296ad8-6ee3-4287-827f-8f4503cb980a)

## Функционал в разработке
- [x] Добавить парсер запроса (вставляем текст запроса), он анализируется и показывает какие объекты метаданных задействованы и есть ли у исполнителя необходимые права для его выполнения. Учитываются поля составного типа, обращения через точку и т.д.
- [x] Добавить рассылку уведомлений об ошибках прав доступа в телеграм.
_______________________________________________________________________________________________________________________________________________
# Заключение
Описанные возможности обеспечивают высокий уровень гибкости и точности при анализе, настройке и мониторинге прав доступа пользователей. Используйте программу в качестве надежного инструмента для оптимизации процесса назначения прав, повышения безопасности системы и обеспечения согласованного управления правами доступа в вашей организации.

# Минимальные требования

1С 8.3 основанная на БСП, минимальной версии 3.1.

Программа была протестирована на следующих конфигурациях:

- 1С: Комплексная автоматизация 2.4, 2.5; 
- 1С: ERP Управление предприятием 2.5;
- 1C: Управление торговлей 11.4

Возможно, что подойдет и для других, основанных на БСП.

___________________________________________________________________________________________________





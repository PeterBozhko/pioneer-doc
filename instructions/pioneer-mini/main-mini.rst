Геоскан "Пионер Мини"
=================================

`Вернуться на сайт "Пионер"`_

.. _Вернуться на сайт "Пионер": https://www.geoscan.aero/ru/pioneer/

`Вернуться на страницу "Пионер Мини"`_

.. _Вернуться на страницу "Пионер мини": https://www.geoscan.aero/ru/products/pioneer/mini


| Геоскан "Пионер Мини" - это базовый учебно-методический комплекс для первого знакомства с автономными летательными аппаратами.

.. image:: media/pioneermini.png
   :align: center
   :width: 420

.. tip:: Для Пионера Мини вышло обновление позволяющее программировать квадрокоптер на Python. 
         Подробнее на странице :doc:`../../programming/python/python_main`.
               
               

**Пионер Мини** - квадрокоптер начального уровня. Он предназначен для комплексного обучения в рамках проведения уроков технологий или занятий по робототехнике в помещениях (Школах, ЦМИТов, Фаблабов, кружков, секций).

**Пионер Мини** разработан в рамках концепции STEM-образования, позволяя ученикам развиваться сразу в нескольких предметных областях – программировании, физике, математике.

Квадрокоптер может летать в помещении полностью автономно по написанной учениками программе, открывая широкие возможности для проведения учебных занятий и соревнований по робототехнике.

С "Пионером Мини" вы сможете:

*  Получить базовые навыки пилотирования;
*  Ознакомиться с устройством и принципом работы квадрокоптера;
*  Изучить на реальном примере физику полёта;
*  Научиться программировать электронные устройства;
*  Освоить новое интересное хобби.

Преимущества:

*  Полностью автономный полет по программе;
*  Учебно-методическое пособие для учителей и учеников;
*  Возможность управления с мобильных устройств;
*  Возможность установки дополнительных модулей;
*  Небольшой вес и размер, простая сборка;
*  Поворотная фото/видео камера;
*  Поддержка ультразвуковой (УЗ) и инфракрасной (ИК) систем навигации в помещении;
*  Широкие возможности для программирования благодаря ESP-32;
*  Возможность зарядки аккумулятора через micro-USB, не вынимая из коптера.

.. important:: Квадрокоптер предназначен для полёта в помещениях.



.. csv-table:: Технические характеристики
   :header: "Параметр", "Значение"

   "Тип", "квадрокоптер"
   "Продолжительность полета", "до 10 минут"
   "Скорость полета", до 15 км/ч
   "Масса квадрокоптера", "100 г"
   "Размеры", "134 x 164 x 38 мм"
   "Двигатели","коллекторные"
   "Аккумуляторная батарея","LiPo 1S 1100мАч"
   "Максимальная дальность полета","50 м"
   "Допустимая скорость ветра","до 5 м/с"
   "Камера"," 2Мп Разрешение видео: до 1200х1600"



Прочитайте это руководство, чтобы собрать и запустить "Пионер мини" в воздух. Раздел "Программирование" также поможет вам решать с с более сложные задачи.

.. important:: Перед осуществлением полета, обязательно обновите прошивку (если версия автопилота ниже, чем 1.6.7257) и параметры автопилота «Пионера Мини». Полет с устаревшей версией прошивки автопилота может быть небезопасен.
               Проверьте версию прошивки автопилота в Pioneer Station и при необходимости перейдите на страницу
               :doc:`settings/firmware_upgrade`.
             
.. note:: Технические характеристики, внешний вид и комплектация товара могут быть изменены производителем без предварительного уведомления.


.. toctree::
   :maxdepth: 2
   :caption: Содержание:

   const/mini-const_main
   settings/mini-settings_main
   flight/mini-flight

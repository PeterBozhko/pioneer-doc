FAQ
===============

Общие вопросы
-------------
**Если не включается пульт** - Проведите диагностику, согласно следующей инструкции: :ref:`Диагностика проблем пульта ДУ <rc_test>`

**Если при попытке взлета квадрокоптер заваливается в сторону** - 
Проверьте правильность установки моторов. Моторы должны быть расположены в соответствии с указаниями на раме. Белые и черные моторы располагаются по диагонали относительно друг друга.

**Если при увеличении газа квадрокоптер крутит винтами, но не взлетает** - Проверьте правильность установки воздушных винтов. Воздушные винты должны быть расположены в соответствии с указаниями на раме. Надписи на винтах должны быть сверху.

**Если при инициализации один или несколько моторов не крутятся** - Необходимо проверить надежность соединения моторов с платой.

**Если при запуске винтов с пульта квадрокоптер никак не реагирует** - Проверьте правильность настройки пульта и привяжите приемник к пульту еще раз.

**Если возникает ошибка OffsetError при обновлении ESP-32** - Откалибруйте акселерометр через Pioneer Station.

**Если квадрокоптер плохо управляется** - Необходимо проверить заряд аккумуляторных батарей квадрокоптера и пульта дистанционного управления.

**Если при подключении аккумулятора квадрокоптер никак не реагирует** - Проверьте целостность аккумулятора и уровень напряжения, он должен быть не ниже 6,6 В.

**Если в полете квадрокоптер сильно вибрирует** - Необходимо проверить правильность сборки рамы, защиты и крепления базовой платы. Также возможной причной может быть дефект пропеллера.

**Если при подключении к Pioneer Station список портов пуст** - проверьте USB кабель; скачайте и установите `драйвер виртуального порта`_ для вашей операционной системы.

.. _драйвер виртуального порта: https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

**Пустое окно при открытии вкладки параметров из файла в Pioneer Station** - Закройте программу и запустите файл run_extra.bat из папки, в которой установлена Pioneer Station. Альтернативное решение, нажмите на клавишу Enter, после скрытия окна, сохраните параметры на Автопилот как обычно.

**Если коптер ведёт себя нестабильно при полёте по программе** - в параметрах автопилота установите значение Copter_pos_aMax=1 и сохраните изменения. Этот параметр отвечает за плавность смены направления и скорости полёта квадрокоптера. 

**Если моторы начинают крутиться с большой задержкой после команды на запуск, и коптер неверно реагирует на движение стиков управления** - в меню пульта **Syst** выберите пункт **Stick.Adj** и двигайте стики так, чтобы они достигли всех крайних положений (в том числе диагональных). После этого нажмите **назад** и попробуйте выполнить полёт снова.

Частое задаваемые вопросы по квадрокоптеру Пионер Мини
------------------------------------------------------

**Если при управлении Пионером Мини со смартфона видео передается, а команды управления нет**  - Загрузите параметры автопилота как описано здесь: :doc:`instructions/pioneer-mini/settings/autopilot_parameters`

**Если при загрузке кода на квадрокоптер в Pioneer Station появляется ошибка: llegal command^ Lua script upload** - Нужно обновить прошивку и параметры автопилота до актуальной версии.

**Если квадрокоптер отклоняется в одну из сторон** - проверьте какой режим полета установлен в текущий момент на квадрокоптере, если это "althold" или "stabilize" это нормально. В этих двух режима стабилизация в горизонтальной плоскости отключена. Если вы летаете в режиме "Navigation", но квадрокоптер все равно сильно кренит в сторону проверьте загружена ли у вас актуальная прошивка автопилота и параметры.

**Если при подключении к квадрокоптеру приложение показывает предупреждение "Внимание! Возможно, версия прошивки STM на вашем дроне устарела"** - скачайте и установите на модуль автопилота актуальную версию прошивки. В процессе придерживайтесь следующей инструкции: :doc:`instructions/pioneer-mini/settings/firmware_upgrade`


**При подключении "Пионера Мини" к Pioneer Station выдает ошибку "Оборудование несовместимо с НСУ"** - для исправления ошибки следуйте инструкции: :doc:`mini-nsu`


**Квадрокоптер обрывает связь с WiFi** - Обновите прошивку контроллера ESP32. Для этого выполните действия описанные в разделе :doc:`instructions/pioneer-mini/settings/esp32-update`
Обратите внимание! При вопросе устройства о использовании сети следует ответить выбрав вариант "Использовать эту сеть" либо "Не отключаться" (в зависимости от устройства), чтобы телефон игнорировал отсутсвие подключения к сети интернет.

**Отсуствует видео с Пионер Мини** - проверьте реагирует ли квадрокоптер на команды Start и Stop с устройства. 
В случае если реакция отсутствует - обновите прошивку контроллера ESP-32. Для этого выполните действия описанный в разделе :doc:`instructions/pioneer-mini/settings/esp32-update`.
Если моторы заводятся но изображения нет - проверьте качество подключения шлейфа камеры либо установите камеру с аналогичной модели следуя инструкции. Если после переустановки изображение появилось, возможно снятая камера имеет дефект. В таком случае обратитесь в техническую поддержку.


.. toctree::
   :maxdepth: 1
   :caption: Содержание:

   mini-nsu

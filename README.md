# Вставка языковых констант в контент Joomla!

Контентный плагин для вставки значений языковых констант, например, в статье. Используется синтаксис `{langos LANGUAGE_CONSTANT}`.

### Идея
😎 Когда собираешь мультиязычный сайт на Joomla, сталкиваешься с дилеммой - модуль или материал, на разных языках, отличается всего лишь парой слов. Не создавать же для этого отдельный модуль!

👍 Этот плагин решает проблему! Создай языковые константы и вставь их в модуль или материал, используя шоттэг `{langos LANGUAGE_CONSTANT}`.

🙌 Всё просто - плагин выполняет функции, аналогичные программному вызову `echo JText::_('LANGUAGE_CONSTANT');`, только программировать в данном случае ничего не нужно 😉

### Установка

1. Скачай свежую версию плагина, с сайта разработчика https://webmasterskaya.xyz/products/joomla/plaginy/joomla-content-langos
2. Перейди в панель управления своего сайта 👉 Расширения 👉 Менеджер расширений 👉 Установка
3. Загрузи плагин, через форму, в панели управления и дождись завершения установки
4. Перейди по ссылке, указанной в сообщении, об успешной установке и активируй плагин

### Применение

1. Перейди в панель управления своего сайта 👉 Расширения 👉 Языки 👉 Переопределение констант
2. Выбери язык сайта, для которого ты хочешь создать константу
3. Нажми "Создать" и заполни обязательные поля -  `Языковая константа *` и `Текст` (если что-то непонятно - наведи курсор на название поля, чтобы получить подсказку)
4. Сохрани константу и проделай те же операции для второго языка (если это нужно)
5. Перейди к редактированию той страницы или модуля, где ты хотел вставить константу
6. В редактор текста вставь код `{langos LANGUAGE_CONSTANT}` _(!!! LANGUAGE_CONSTANT нужно заменить на название языковой константы, которую создали на шаге №3)_

Для корректной работы плагина в модуле типа HTML, не забудь включить опцию `Обработка плагинами` на вкладке `Основные параметры`, на странице редактирования модуля.

### Поблагодарить 💰

Если тебе хочется получать больше бесплатных расширений - подкинь "монетку" разработчику на кофе и печеньки.

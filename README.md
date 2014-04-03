## Задание разработчика интерфейсов в команду Яндекс.Картинок, Яндекс.Видео.

Реализуйте текстовую консоль для управления панелью закладок. Консоль должна представлять собой текстовое поле для ввода команд, поле для вывода результата выполнения.

**P.S. Если Вы считаете задание слишком сложным и/или непонятным, то напишите, пожалуйста, об этом автору репозитория на @yandex-team.ru. Спасибо! :)**

**Требования к консоли**:
  * поддержка команды `selectTab(tabIndex)` — выбор таба с индексом `tabIndex`;
  * поддержка команды `swapTabs(tabIndex1, tabIndex2)` — поменять местами в DOM табы `tabIndex1` и `tabIndex2`;
  * поддержка команды `showStat()` — показать статистику;
  * выполнение команд по нажатию клавиши "enter";
  * поддержка истории выполнения команд — клавиши "↑" и "↓"  должны переключать поле ввода между последними 10 командами;
  * сбор статистики по времени работы с консолью, времени просмотра каждого таба в рамках сессии.

**Результаты работы команд в консоли**:

    selectTab(2)
    Выбран таб №2 "контрол рейтинга".

    selectTab(100)
    Не удалось выбрать таб №100. Доступны табы с 0 по 3.

    swapTabs(0, 2)
    Поменяли табы №0 "список иконок" и №2 "контрол рейтинга" местами.

    showStat()
    Общее время работы со страницей: 1 минута 30 секунд
    Детализация времени просмотра табов:
      0 "список иконок": 1 секунда
      1 "текст": 59 секунд
      2 "контрол рейтинга": 30 секунд

**Примерный результат должен выглядеть так**:
![mockup](mockup.png)

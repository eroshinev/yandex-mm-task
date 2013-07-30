## Задание разработчика интерфейсов в команду Яндекс.Картинок, Яндекс.Видео.

Сверстайте три или более задания, предложенных по этой ссылке http://yuri.ya.ru/replies.xml?item_no=4484 :
  * задания должны представлять собой панель с закладками (tabs);
  * каждое задание должно быть оформленно в виде отдельного таба;
  * при обновлении страницы (F5) должен отображаться последний выбранный таб;
  * разрешается и приветствуется использование jQuery без сторонних плагинов.

Реализуйте текстовую консоль для управления панелью закладок. Консоль должна представлять собой текстовое поле для ввода команд, поле для вывода результата выполнения.

**Требования к консоли**:
  * поддержка команды `selectTab(tabIndex)` — выбор таба с индексом `tabIndex`;
  * поддержка команды `swapTabs(tabIndex1, tabIndex2)` — поменять местами в DOM табы `tabIndex1` и `tabIndex2`;
  * поддержка команды `showStat()` — показать статистику;
  * выполнение команд по нажатию клавишы "enter";
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

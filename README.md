
•	Loger
Реализовать программный модуль (класс Loger), позволяющий записыватьинформация о 
работе программы в лог-файле. Каждая запись информации в журнале должна 
содержать следующие поля: дата и время, тип сообщения (ошибка,исключение, тестовое 
сообщение, информационное сообщение, предупреждение), имятекущего пользователя, 
текст сообщения. При этом должна быть реализовананастройка данного класса. В данной 
настройке указывается маска записиинформация в лог-файл т.е. наличие информации в 
записях и наличиеполей полей. Настройка считывания из файла конфигурации (ini-
файла).
•	Автомобильная гонка
Игра «Автомобильные гонки».
Разработать игру "Автомобильные гонки" с использованием делегатов.
1. В игре использовать несколько типов автомобилей: спортивные, легковые,
грузовые и автобусы.
2. Реализовать игру «Гонки». Принцип игры: Автомобили двигаются от
старта к финишу со скоростями, которые изменяются в установленных пределах
случайным образом. Победителем считается автомобиль, пришедший к финишу
первым
Рекомендации по выполнению работы
1. Разработать абстрактный класс «автомобиль» (класс Car). Собрать в нем
все общие поля, свойства (например, скорость) методы (например, ехать).
2. Разработать классы автомобилей с конкретной реализацией конструкторов
и методов, свойств. В классы автомобилей добавить необходимые события
(например, финиш).
3. Класс игры должен производить запуск соревнований автомобилей,
выводить сообщения о текущем положении автомобилей, выводить сообщение об
автомобиле, победившем в гонках. Создать делегаты, обеспечивающие вызов
методов из классов автомобилей (например, выйти на старт, начать гонку).
4. Игра заканчивается, когда какой-то из автомобилей проехал определенное
расстояние (старт в положении 0, финиш в положении 100). 
окончании гонки (прибытии какого-либо автомобиля на финиш) реализовать с
помощью событий

•	Викторина
Создать приложение «Викторина».
Основная задача проекта: предоставить пользователю возможность проверить
свои знания в разных областях.
Интерфейс приложения должен предоставлять такие возможности:
■ При старте приложения пользователь вводит логин и пароль для входа.
Если пользователь не зарегистрирован, он должен пройти процесс регистрации.
■ При регистрации нужно указать:
• логин (нельзя зарегистрировать уже существующий логин);
• пароль;
После входа в систему пользователь может:
• стартовать новую викторину;
• посмотреть результаты своих прошлых викторин;
Необходимо также разработать утилиту для создания и редактирования
викторин и их вопросов. Это приложение должно предусматривать вход по логину и паролю.

•	Дом 
Реализовать программу “Строительство дома”.
 Реализовать:
- классы  House (Дом), Basement (Фундамент), Walls (Стены), Door (Дверь), Window (Окно), Roof (Крыша); Team (Бригада строителей), Worker (Строитель), TeamLeader (Бригадир), 
- интерфейсы 
IWorker, IPart.
Все части дома должны реализовать интерфейс IPart (Часть дома), для рабочих и бригадира предоставляется базовый интерфейс IWorker (Рабочий).
Бригада строителей (Team) строит дом (House). Дом состоит из фундамента (Basement), стен (Wall), окон (Window), дверей (Door), крыши (Part).
Согласно проекту, в доме должно быть 1 фундамент, 4 стены, 1 дверь, 4 окна и 1 крыша.
Бригада начинает работу, и строители последовательно “строят” дом, начиная с фундамента. Каждый строитель не знает заранее, на чём завершился предыдущий этап строительства, поэтому он “проверяет”, что уже построено и продолжает работу. Если в игру вступает бригадир (TeamLeader), он не строит, а формирует отчёт, что уже построено и какая часть работы выполнена.
В конечном итоге на консоль выводится сообщение, что строительство дома завершено и отображается “рисунок дома” (вариант отображения выбрать самостоятельно).

•	Карточная игра
Программа «Карточная игра!»
Создать модель карточной игры. 
Требования:
1.	Класс Game формирует и обеспечивает:
1.1.1.	Список игроков (минимум 2);
1.1.2.	Колоду карт (36 карт);
1.1.3.	Перетасовку карт (случайным образом);
1.1.4.	Раздачу карт игрокам (равными частями каждому игроку);
1.1.5.	Игровой процесс. Принцип: Игроки кладут по одной карте. У кого карта больше, то тот игрок забирает все карты и кладет их в конец своей колоды. Упрощение: при совпадении карт забирает первый игрок, шестерка не забирает туза. Выигрывает игрок, который забрал все карты.
2.	Класс Player (набор имеющихся карт, вывод имеющихся карт).
3.	Класс Karta (масть и тип карты (6-10, валет, дама, король, туз).

•	Словари
Создать приложение «Словари».
Основная задача проекта: хранить словари на разных языках и разрешать пользователю находить перевод нужного слова или фразы.
Интерфейс приложения должен предоставлять такие возможности:
■ Создавать словарь. При создании нужно указать тип словаря. Например,
англо-русский или русско-английский.
■ Добавлять слово и его перевод в уже существующий словарь. Так как у
слова может быть несколько переводов, необходимо поддерживать возможность создания нескольких вариантов перевода.
■ Заменять слово или его перевод в словаре.
■ Удалять слово или перевод. Если удаляется слово, все его переводы удаляются вместе с ним. Нельзя удалить перевод слова, если это последний
вариант перевода.
■ Искать перевод слова.
■ Словари должны храниться в файлах.
■ Слово и варианты его переводов можно экспортировать в отдельный файл
результата.
■ При старте программы необходимо показывать меню для работы с программой. Если выбор пункта меню открывает подменю, то тогда в нем
требуется предусмотреть возможность возврата в предыдуще

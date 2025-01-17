# EV3-Game-Of-Life
EV3 Игра "Жизнь" Карандаша и Самоделкина

Сегодня мы соберем и запрограммируем клеточный автомат под названием "Игра Жизнь" используя платформу LEGO Mindstorms EV3. Игра́ «Жизнь» (англ. Conway's Game of Life) придумана английским математиком Джоном Конвеем в 1970 году. Место действия этой игры — «вселенная» — это размеченная на клетки поверхность или плоскость. В нашей EV3-версии поле ограничено и верхняя граница поля «соединена» с нижней, а левая граница — с правой, что представляет собой эмуляцию поверхности тора, но на экране поле отображается в виде равномерной сетки. Каждая клетка на этой поверхности может находиться в двух состояниях: быть «живой» или быть «мёртвой» (пустой). Клетка имеет восемь соседей (окружающих клеток).
Распределение живых клеток в начале игры называется первым поколением. Каждое следующее поколение рассчитывается на основе предыдущего по таким правилам:
1) в пустой (мёртвой) клетке, рядом с которой ровно три живые клетки, зарождается жизнь;
2) если у живой клетки есть две или три живые соседки, то эта клетка продолжает жить; в противном случае (если соседей меньше двух или больше трёх) клетка умирает («от одиночества» или «от перенаселённости»)
Игра прекращается, если на поле не останется ни одной «живой» клетки, если при очередном шаге ни одна из клеток не меняет своего состояния (складывается стабильная конфигурация) или если конфигурация на очередном шаге в точности (без сдвигов и поворотов) повторит себя же на одном из более ранних шагов (складывается периодическая конфигурация).
Эти простые правила приводят к огромному разнообразию форм, которые могут возникнуть в игре.
Игрок не принимает прямого участия в игре, а лишь расставляет или генерирует начальную конфигурацию «живых» клеток, которые затем взаимодействуют согласно правилам уже без его участия (он является наблюдателем).
Алгоритм «смены поколения» последовательно просматривает все ячейки решетки и для каждой ячейки подсчитывает соседей, определяя судьбу каждой клетки (не изменится, умрет, родится).
Вскоре после опубликования правил, было обнаружено несколько интересных шаблонов (вариантов расстановки живых клеток в первом поколении), в частности планер (глайдер). Некоторые такие фигуры остаются неизменными во всех последующих поколениях, состояние других периодически повторяется, в некоторых случаях со смещением всей фигуры.

Подробнее http://karandashsamodelkin.blogspot.ru/2015/10/ev3_61.html

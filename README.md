# Drakon
Examples of python code 

## Fibonacci sequence


[Fibonacci](https://www.mathsisfun.com/numbers/fibonacci-sequence.html)

В математике треугольник Паскаля - это треугольный массив биномиальных коэффициентов, который возникает в теории вероятностей, комбинаторике и алгебре. В большей части западного мира он назван в честь французского математика Блеза Паскаля, хотя другие математики изучали его за несколько столетий до него в Индии,Персии,Китае,Германии и Италии.

Строки треугольника Паскаля обычно нумеруются, начиная с строки n = 0 вверху (0-я строка). Записи в каждой строке нумеруются слева, начиная с k = 0, и обычно располагаются в шахматном порядке относительно чисел в соседних строках. Треугольник может быть построен следующим образом: в строке 0 (самая верхняя строка) есть уникальная ненулевая запись 1. Каждая запись каждой последующей строки создается путем добавления числа вверху и слева с номером вверху и к справа, обрабатывая пустые записи как 0. Например, начальное число в первой (или любой другой) строке равно 1 (сумма 0 и 1), тогда как числа 1 и 3 в третьей строке складываются для получения цифра 4 в четвертом ряду.

Суммы диагоналий, дают нам суммы следующих последовательностей геометрических фигур:

![Fibonacci in Pascal](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Fibonacci_in_Pascal_triangle.png/330px-Fibonacci_in_Pascal_triangle.png)

Прерывистый луч, минус первое измерение (1 - нулевой объект\доп) - показан на рисунке выше в виде первой красной диагональю от левого верхнего угла.

0-мерная система (1 - точка) - самая верхняя синяя диагональ на рисунке выше.

1 луч в одномерной системе (1 ребро + 1 точка\доп)

1 проекция сиплекса\пакета молока на плоскость (1 грань\треугольник + 2 точки)

1 пакет молока\трехмерный симплекс и центральная точка объема с 4 ребрами (1 объем + 3 ребра + 1 ребро\доп)

1 четырехмерный симплекс\проекция 8 гиперобъемов на 4-х мерное пространство (1 гиперобъем + 4 грани +3 точки ). При таких измерениях проще говорит в терминах симметрии. Отражение гиперобъема через 4 грани и еще через 3 точки. Получаем тут группу Ли и связанную с ней решетку.

[д'Арийская Arifmetika](http://www.vixri.com/d/Nasledie%20slavjan%20i%20Ariev%20%20_X-Arijskaja%20arifmetika.pdf)

Страница 13 д'Арийской Арифметики - Умножение Ю. 

По крайнему примеру - берем 3 точки - они сами по себе образуют грань. Добавляем еще одну точку, тем самым у нас получился пакет молока с 4 гранями. Добавляем еще одну точку - на каждой грани пакета молока у нас выростает еще по одному пакету молока - всего 5 пакетов молока, которые образуют гиперобъем.
Если просуммировать все эти обекты то у нас получается 8 - элемент последовательности фибоначи. 

Но возникает вопрос - Как мы складываем треугольник с тетрайдером? 

Это геометрическое сложение: На самом деле мы складываем пакет молока с его 6 ребрами минус 3 ребра треугольника. Так как пакет молока и 6 ребер эквивалентны - мы можем их складывать. А вот коэффицент 3 это коэффицент двухмерного ПРОВОЛОЧНОГО треугольника из 3 точек при сложении с треугольниками пакета молока. А 4 это коэффицент плоского треугольника при сложении с 4-х мерным симплексом. Другими словами каждая точка в 4-х мерном пространстве имеет коэффицент 3. Каждая грань в 4-х мерном симплекс пространстве коэффицент 4.

Вот эта полная структура 4-х мерный тетрайдер и дает набор опорных точек в количестве 5 штук, которые и являются объемно временным ОВ умножением Ю (которое разобрано на странице 13 учебника д'Арийской арифметики). 

Все диагоналии без доп (то есть только синие диагоналии) относятся к нашему реальном миру (красные диагоналии относятся к мнимым физическим величинам): 

0 мерный квант это, возможно, наши мысли. Так считал [Плотников Николай Александрович](http://plotnikovna.narod.ru/), создатель [Системы физических величин](http://plotnikovna.narod.ru/01.jpg)

1-но мерный квант - пи-мезоны.

2-х мерный квант - время или свет

3-х мерный квант - звук и упругость. Это то что мы чувствуем руками и ушами.

![4-х мерный квант - магнитное поле](http://www.vlf.it/cumiana/last-supercoil.jpg)

4-х мерный квант - магнитное поле

![5-ти мерный квант электрическое поле](http://www.vlf.it/cumiana/last-geomar.jpg)

5-ти мерный квант электрическое поле

![6-ти мерный квант - слабое взаимодействие](https://e-finland.ru/media/cache/4b/8c/4b8cfcb72c502ab3610e1c2191eb3775.jpg)

6-ти мерный квант - слабое взаимодействие

Рентгеновское излучение - северное сияние это проекция излучения космических частиц высокой энергии (как рентген) на свет. Уловить нейтрино можно в - полкубических сантиметра газообразного Германия, который содержит всего 5-6 оставшихся после распада атомов со следами нейтрино. По сути это та же структура Алмазной решетки (Кремний) потому что они находятся в той же группе IV но разных периодах (в 3 и 5 ряду).

7-ми мерный квант - сильное взаимодействие - оно очень проницательное (проходит через все что угодно включая время) и поэтому не имеет материальных графиков - но служит полем носителем мыслей (не путать с 0-квантом/1-квантом)


![Кристалл](http://forum.holding.bz/uploads/images/4/569f3798546c0f2e64b86444f3dba3c4.png)

Вот что происходит, если из центра кристалла идет свет.У нас получается треугольник Паскалля 1 зона под ней 2 зона затем две зоны 3 затем зона 4, 6, 4 и так далее (вот тут все не точно - тут надо конкретнее разбираться, но пока такой задачи ребром не стоит, поэтому примем во внимаение что есть статистическая связь. Что распределения зон в кристалле и коэффиценты биномов в треугольнике Паскаля схожи по статистике)

![Кристалл2](http://sceptic-ratio.narod.ru/ma/km27/image034.jpg)

Суть всего этого очень простая. Если у нас есть регулрная двухмерная решетка, то фотон каждый раз при столкновении будет выбирать один из 2 путей. Соответственно числа в треугольнике паскаля это сколько фотонов попадет в итоге в каждый узел нашей регулярной структуры, если в каждом узле фотон переотражается (удваиватеся\копируется\использует время перед отправкой) в двух соседних направлениях (это и есть определение времени для двухмерных кристаллов). Скажем прямо, структура у нас это кристалл алмаза (бриллиант) и она отражает свет. 

Свет воздействует и на горы - потому что это совокупность кристаллических структур. 

Для трехмерных структур - фотон света будет в 3 направлениях переотражатся.

[2D Brillouin Zones](https://demonstrations.wolfram.com/2DBrillouinZones/)

[Cubic Lattice](https://mathworld.wolfram.com/CubicLattice.html)

[Программа на Питоне](https://github.com/hedhyw/BrillouinZones)

Cвязи Треугольника Паскаля и зон Брюльена есть некоторые неточности. Но с точки зрения физики Статистика Ферми-Дирака, биномиальные коэффиценты и треугольник Паскаля являются в чем то близкими понятиями. Так же можно проследить связь Треугольника Паскаля с законами Кирхгофа для электрического тока и теорией цепей Крона.

[История теории вероятностей](https://wikipedia24.ru/%D0%98%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F_%D1%82%D0%B5%D0%BE%D1%80%D0%B8%D0%B8_%D0%B2%D0%B5%D1%80%D0%BE%D1%8F%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9)



## Drakon file it is a tables of SQLite DB.

Look to SQLite Drakon db:

```sh
sqlite3 first6.drn
```

List of table

```sh
.tables
```

Show table item:

```sql
select * from items;
```

Examples of different select:

```sql
select text,x,y from items;

select a,b,color from items;
```

Show any SQL code for Drakon db (INCLUDE, CREATE):

```sh
.dump
```

![SQLite dump](http://homedevice.pro/wp-content/uploads/2020/12/SQLite.png)

CREATE TABLE - создать таблицу

INSERT INTO - вставить строчки в таблицу

Exit from SQLite DB:

```sh
.exit
```

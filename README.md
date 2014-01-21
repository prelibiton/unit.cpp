unit.cpp
========

In Bulgarian:

Задача 1. Нека отдел да наричаме обект, притежаващ следните характеристики:

* име (символен низ без интервали до 100 символа);

* идентификатор(естествено число)

* собствен бюджет (естествено число);

* опашка от подчинени отдели.

a) Да се реализира клас Unit, представящ отдел и метод addSubUnit([подходящ тип] unit, който добавя подчинен отдел към опашката от отдели;

Нека е даден следния език за описание на отдел:

<отдел> ::= {<име> <идентификатор> <бюджет> <вложени отдели>}

<име> ::= дума от малки латински букви, максимум 100 на брой

<идентификатор> ::= естестевено число

<бюджет> ::= ествествено число

<вложени отдели> ::= <празно> | <отдел> или <вложени отдели>

Разделителят между всеки два терминални символа е единичен интервал или единичен нов ред.

Пример за отдел, описан на този език:

{fmi 1 100

{mathematics 10 50} {statistics 2 10} {informatics 5 30

{bio 7 10} {web 3 10}}}

б) Да се реализира функция void writeBudgets(Unit name, int i), която записва в двоичния файл budgets.bin на (i-1)-ва позиция името и бюджета на подадения отдел. (Ако отделът няма подчинени отдели, целият му бюджет е равен на собствения му бюджет. Ако има, бюджетът на отдела е равен на собствения му бюджет плюс сумата от бюджетите на всички негови подотдели)

Бюджетът на fmi в горния пример е 210 (= 100 + (50 + 10 + (30 + (10 + 10))))))

в) В текстовия файл units.txt e дадено едно такова описание. Да се дефинира оператор за вход от файла (>>) за отдел.

In English:
Ok,It's homework,no big deal. :)

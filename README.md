# search_system
Неольшой учебный проект ядра поисковой системы, созданный для закрепления знаний и нввыков програмированния на C++.

Программа умеет:
- Принимать на вход "документы" (строки)
- Принмать "стоп-слова" (слова исключаемые из алгоритма подбора документов)
- Принимать запрос на поиск среди введеных ранее документов
- Выдавать результат с учетом релевантности документов


Пример ввода 

a an on the in is has been are with for from have be was                      # стоп-слова
4                                                                             # кол-во документов
a small curly guinea pig with grey hair has been found                        # документ №1
a young 50 year old crocodile wants to make friends                           # документ №2
a strange brown creature was seen in the box of oranges                       # документ №3
a strange animal with big ears is building a house for its friends            # документ №4
cheburashka with big ears likes oranges                                       # поисковой запрос

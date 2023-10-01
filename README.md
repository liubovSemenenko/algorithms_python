# Аlgorithms in Python
Repository with problem statements and their solutions

Ex.1 "Good sequence"

Последовательность точек на плоскости называется тривиальной, если она является строго упорядоченной по возрастанию или по убыванию расстояния до одной из точек этой последовательности.
Последовательность точек в трехмерном пространстве называется хорошей, если ни одна из последовательностей, полученных взятием проекции исходной на одну из базовых плоскостей (Oxy, Oyz и Oxz), не является тривиальной.
Дана последовательность из $n$ точек с целочисленными координатами в трехмерном пространстве. Необходимо найти такую нечетную перестановку ее индексов, что после ее применения последовательность становится хорошей.
Гарантируется, что решение существует.


Ex.2 "Complex numbers"

Обозначим через S(n) сумму цифр натурального числа n.
Будем говорить, что натуральное число n сложное, если не существует такого натурального числа k, что
n = {3k} / {S(k)^2}
Найдите наименьшее сложное число.


Ex.3 "Number_splitting"

Дано число n. Разбейте десятичную запись числа n на максимальное возможное количество различных чисел.
Использовать числа с незначащими нулями не разрешается.


Ex.4 "Wallets and coins"

Программист Петя очень любит складывать все имеющиеся у него деньги в кошельки и фиксировать, сколько денег лежит в каждом кошельке. Для этого он сохраняет в файле набор целых положительных чисел — количество денег, которое лежит в каждом из его кошельков (Петя не любит, когда хотя бы один из его кошельков пустует). Петя хранит все деньги в монетах, номинал каждой монеты — 1 условная единица.
Однажды у Пети сломался блок магнитных головок и ему пришлось восстанавливать данные с жесткого диска. Он хочет проверить, корректно ли восстановились данные, и просит вас убедиться, что можно ту сумму денег, которая у него была, разложить во все его кошельки, чтобы получились те же числа, что и в восстановленном файле.


Ex.5 "Interesting journey"

Не секрет, что некоторые программисты очень любят путешествовать. Хорошо всем известный программист Петя тоже очень любит путешествовать, посещать музеи и осматривать достопримечательности других городов.
Для перемещений из города в город он предпочитает использовать машину. При этом он заправляется только на станциях в городах, но не на станциях по пути. Поэтому он очень аккуратно выбирает маршруты, чтобы машина не заглохла в дороге. А еще Петя очень важный член команды, поэтому он не может себе позволить путешествовать слишком долго. Он решил написать программу, которая поможет ему с выбором очередного путешествия. Но так как сейчас у него слишком много других задач, он попросил вас помочь ему.
Расстояние между двумя городами считается как сумма модулей разности по каждой из координат. Дороги есть между всеми парами городов.


Ex.6 "Game with numbers"


Дана последовательность n положительных чисел a_1, a_2, …, a_n. Пока среди них есть различные, выполняется следующая операция: выбирается некоторое максимальное число и из него вычитается минимальное число.
Через сколько операций числа станут одинаковыми?


Ex.7 "Game"

Петя и Вася играют в игру: они по очереди берут из колоды карточки, на которых написаны целые неповторяющиеся положительные числа (первый карточку всегда берет Петя). Карточки игроки берут по одной сверху колоды. После этого они сравнивают значения, записанные на карточках: игрок, у которого меньше, тянет еще одну карточку и оставляет ее у себя. Когда все карточки заканчиваются, Петя и Вася считают сумму значений, написанных на этих карточках. Проигрывает тот, у кого сумма получается меньше, чем у другого игрока.
Им надоело вручную тянуть карточки и сравнивать значения. Они попросили вас написать программу, которая по исходному набору карточек будет определять победителя.
Гарантируется, что для любого теста победителя можно будет определить однозначно.


Ex.8 "All_except_one"

Даны k перестановок из n элементов, каждая из которых принадлежит к одному из m типов.
Посчитайте позицию первого элемента, если последовательно применить эти k перестановок, убрав одну из них.


Ex.9 "Nested rectangles"

На клетчатой плоскости отмечено n клеток.
Для раскрашивания этих клеток проводятся следующие операции. На каждом шаге выбирается прямоугольник минимальной площади, содержащий все отмеченные, но не окрашенные, клетки, и все клетки на его границе перекрашиваются в новый цвет.
Определите, через сколько шагов неокрашенных клеток не останется.










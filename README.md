Домашнее задание по теме "CSV файлы"
Цель задания:


Усвоить навык работы с CSV фалами, повторить основы работ с типами данных: list, tuple, set, dict.
Написать программу для определения города для путешествия.

Задание:


Как мы все знаем айтишники любят путешествовать, а география студентов Urban'а очень большая.
Все они были в разных городах и странах, но посетить осталось ещё не мало. Выпускники уже  планируют, куда поедут после окончания курсов отдохнуть.
Нужно помочь им определить, кто в каких городах был и в какие города они хотят поехать. Определите, какие города можно выбрать для путешествия, при условии, что никто из потока в них никогда не был.

Напишите функцию write_holiday_cities(first_letter), которая:
Принимает параметром первую букву имени человека - first_letter.
Функция должна:
Получить данные из travel_notes.csv и записать в holiday.csv:
В каких городах студенты с именем на first_letter уже были.
Какие города студенты с именем на first_letter хотят посетить.
В каких городах студенты с именем на first_letter ещё не были.
Какой первый город эти студенты посетят (в алфавитном порядке)

Файлы для задачи - https://github.com/yanchuki/StudentsHoliday.git

Пример работы:

Входные данные:

Текстовый файл travel_notes.csv, содержит данные о студентах и городах, в которых они были и хотят посетить.

Например:
"Lyuba,Beijing;Dushanbe;Tbilisi;Aktau,Cairo;Minsk"
"Lyuba" — это имя человека
"Beijing;Dushanbe;Tbilisi;Aktau" — города, в которых она была;
"Cairo;Minsk" — города, которые она еще хочет посетить.
Ввод: L


Выходные данные

Все города, записанные в holiday.csv должны быть предварительно отсортированы в алфавитном порядке.

Например (информация о городах людей, имена которых начинаются на 'L'):
Посетили: Aktau, Beijing, Dushanbe, Irkutsk, Kiev, Luxembourg, Minsk, Moscow, New York, Saint Petersburg, Tbilisi, Vladikavkaz
Хотят посетить: Almaty, Cairo, Kursk, Levan, Minsk, Nizhny Tagil, Orel, Tokyo
Никогда не были в: Almaty, Cairo, Kursk,Хотят посетить Tagil, Orel, Tokyo
Следующим городом будет: Almaty

Примечание:

Кроме буквы "L" достаточным будет проверка результата с буквой "R":

Посетили: Lyubertsy, Nizhny Tagil, Odintsovo
Хотят посетить: Kiev, Perm
Никогда не были в: Kiev, Perm
Следующим городом будет: Kiev

Файл с кодом функции прикрепите к домашнему заданию.

Успеха!
# Исследование тарифов компании «Мегалайн»

>Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.
>Нам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

**Статус проекта** - завершён ✅

**Использованые инструменты**

Основной инструмент  — `pandas`, `python`, `numpy`,  для визуализации данных -  `matplotlib`, `seaborn`, `SciPy` - для статистического анализа

**Шаги исследования**

1. Изучение данных из файлов
2. Предобработка данных
3. Расчёты и добавление результатов в таблицу
4. Исследовательский анализ данных
5. Проверка гипотез с помощью t-теста

**Цель исследования** - подтвердить или опровергнуть 2 выдыинутые гипотезы

Гипотезы:

Средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются

Средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов


**Использованые инструменты**

Основной инструмент  — `pandas`, `python`, `numpy`,  для визуализации данных -  `matplotlib`, `seaborn`, `SciPy` - для статистического анализа

**Выводы:**

>Нулевая гипотеза №1: Средняя выручка пользователей тарифов «Ультра» и «Смарт» одинаковы - средняя выручка тарифа Ультра больше выручки тарифа Смарт - оправержена
>
>Альтернативная гипотеза №1: Средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются - подтверждена

>Нулевая гипотеза №2: - Средняя выручка пользователей из Москвы такая же как выручка пользователей из других регионов - подтверждена
>
>Альтернативная гипотеза №2: Средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов - опровержена

>Нулевая гипотеза №1 - была опровергнута, №2 - не удалось опровергнуть, поэтому в первом случае стоит продолжать исследования в пользу альтернативной гипотезы, а во втором - стоит продолжать изучать нулевую гипотезу, ведь то, что она не опровергнута - не значит, что она подтверждена

>Так как наша первая нулевая гипотеза была отвергнута - мы будем исходить из того, что верна альтернативная гипотеза
>
>Она гласит, что средняя выручка тарифа Ультра больше, следовательно и наиболее выгодный тариф по выручуке - Ультра, но для того, чтобы определить какой тариф выгоднее, нужно понимпть из чего складывается прибыль компании
>
>>Если прибыль зависит от того как много людей вышло за рамки тарифа, то из анализа поведения клиентов можно заметить, что тариф Смарт был бы наиболее выгодным для компании
>
>>Если же наша компания имеет какие-то льготы на использование интернета, кол-ва смс или длину звонков или же они наоборот платят за это большой налог или имеют наложеную максимальную квоту, выйдя за пределы которой, тратят на это много денег,то им будет более выгоден тариф Ультра в первом случае и Смарт во втором

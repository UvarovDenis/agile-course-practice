# Игра "Жизнь" Джона Конвея

Выполнил:

- Уваров Денис
- ННГУ, ф-т ИТММ, каф. МОСТ, группа 381603м4

## Задание

Разработать программу для вычисления следующего поколения [игры "Жизнь" Джона Конвея][game_of_life] на основе стартового состояния.
В качестве начальных данных подается двумерная сетка клеток, где каждая клетка либо жива, либо мертва. Клетка имеет восемь соседей ([Oкрестность Мура][moore_neighborhood]), окружающих её. Сетка конечна и никакая жизнь не может существовать по краям.
Расчет следующего поколения выполняется согласно четырем [правилам][rules]:

1. Любая живая клетка с менее чем двумя живыми соседям умирает «от одиночества»;
2. Любая живая клетка с более чем тремя живыми соседям умирает «от перенаселённости»;
3. Любая живая клетка с двумя или тремя живыми соседями живет и в следующем поколении;
4. В любой мёртвой клетке, рядом с которой ровно три живые клетки, зарождается жизнь.

## Пример работы программы
Обозначения: \* - указывает на живую ячейку, \. - указывает на мертвую клетку
<br/>
***Пример ввода:*** (сетка 4 x 8) <br/>
```
    4 8
    ........
    ....*...
    ...**...
    ........
```
***Пример вывода:*** <br/>

```
    4 8
    ........
    ...**...
    ...**...
    ........
```

<!-- LINKS -->
[game_of_life]: https://ru.wikipedia.org/wiki/%D0%96%D0%B8%D0%B7%D0%BD%D1%8C_(%D0%B8%D0%B3%D1%80%D0%B0) "wikipedia.org"
[moore_neighborhood]: https://ru.wikipedia.org/wiki/%D0%9E%D0%BA%D1%80%D0%B5%D1%81%D1%82%D0%BD%D0%BE%D1%81%D1%82%D1%8C_%D0%9C%D1%83%D1%80%D0%B0 "wikipedia.org"
[rules]: https://ru.wikipedia.org/wiki/%D0%96%D0%B8%D0%B7%D0%BD%D1%8C_(%D0%B8%D0%B3%D1%80%D0%B0)#%D0%9F%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0 "wikipedia.org"

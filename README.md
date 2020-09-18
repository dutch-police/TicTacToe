# TicTacToe
Реализация игры крестики-нолики (обучение с подкреплением + Агенты)
# Задача
Написать класс, который берет два экземпляра классов агентов и играет.
Реализовать игроков на на основе обучения с подкреплением и эволюционного подхода.
Проведём состязание.
Проверить: как лучше – корректировать ценности после всех ходов или только "жадных".
# Решение
Реализация в файле **tictactoe.ipynb**<br>
Первая часть - реализация основных классов + консольная версия, с помощью которой можно запустить игру<br>
Вторая часть - Агенты, являющиеся оберткой к основным объектам (AIPlayer и Game) которые можно использовать во внешней программе для тестирования.
В функции makeStep класса AIPlayer есть опция выбора типа хода - при помощи таблицы ценности (жадный ход) или случайный ход, оба агента используют соответствующий тип хода.
Таблица ценности хранится в файле **rewards.json** который нужно загрузить в тот же каталог в котором находится код игры, так как в этот файл загружаются ценности состояний, которые потом используются в игре.<br>
При разработке использовались следующие источники:
- https://alex-yashin.ru/blog/20171215-tictactoe-simple-ai.html
- https://github.com/alex-yashin/tictactoe-ai

Кирилл Прохоров<br>
Павел Смирнов<br>
Раиль Чабдаров<br>


# Игра на угадывание чисел
Добро пожаловать в игру на угадывание чисел! Эта игра представляет собой простую игру на основе командной строки, в которой компьютер случайным образом выбирает число, а пользователь должен его угадать.

Данная игра была написана с целью выпонения задания [Number_Guessing_Game](https://roadmap.sh/projects/number-guessing-game) проекта [roadmap.sh](https://roadmap.sh/).

## Требования
- Python 3.x
- Кодовый редактор или IDE (например, VSCode, PyCharm)
- Git (для управления версиями проекта)

## Установка
1) Клонируйте репозиторий:
```bash
 git clone git@github.com:AlexaKrut/Number_Guessing_Game.git  
```
2) Перейдите в папку с игрой:
```bash
cd Number_Guessing_Game
```
3) Запустите игру:
```bash
python3 number_guessing_game.py 
```

## Игра

### Правила игры
1) Компьютер случайным образом выбирает число от 1 до 100.
2) Пользователь выбирает уровень сложности (лёгкий, средний, сложный), который определяет количество попыток угадать число.
3) Пользователь вводит свое предположение.
4) Если пользователь угадал правильно, игра отображает поздравительное сообщение вместе с количеством попыток и временем, которые потребовались для угадывания числа.
5) Если предположение пользователя неверно, игра отображает сообщение, указывающее, больше или меньше число, чем предположение пользователя.
6) Игра предлагает пользователю повторить раунд.
7) Игра заканчивается, когда пользователь решает выйти.

### Уровни сложности

- Лёгкий: 10 попыток
- Средний: 5 попыток
- Сложный: 3 попытки











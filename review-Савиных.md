## Визуал
* Плюсы
Всё супер. Красивый минималистичный главный экран, приятная анимация появления циферок,
все элементы хорошо видны и выставлены как по линеечке, не забыли менять цвет границ квадратика при переходе на клетку другого цвета (отдельное уважение).
* Минусы
Всё чёрно-белое. Хотелось бы цветные японские кроссворды на чёрно-белом экране эмулятора)

## Геймплей
* Плюсы
    - Жёсткая ностальгия по детству и челленджу (p.s. тыкался часа 2 ночью, а мог бы спать :) )
    - Никаких лагов и миганий. Всё максимально плавно. Хотя там вроде и нечему особо лагать, но тем не менее
    - Возможность отменить закраску и отменить отмену
    - Разные уровни (кстати было бы круто на экране выбора под уровнями написать их размер типа m x n)
    - Удобное управление (хотя мне бы наверное больше понравилось перемещение указателя на WASD и закрашивание на Enter, но это уже вкусовщина геймерская)
* Минусы
    - Глючная проверка
    - Очень надо (прям пипец как) добавить возможность ставить какие-то символы в те места, где ты уверен, что не надо закрашивать (например точки),
    потому что уже с 3 уровня мозг не вывозит в память и приходится доставать листочек, а чтобы последние решать без него - надо быть как минимум МСМК по мнемонике...
    - Неприятно, что когда "отправляешь на проверку", то при неправильном ответе тебя не возвращает обратно к кроссворду, а выкидывает в главное меню, обнуляя прогресс
    - Часто приходится перезапускать игру из-за кривоватых загрузок уровней
    - Предложение: чуть ускорить прыжки указателя по клеточкам. Не думаю, что от этого начнет подлагивать

## Прости господи код, сохрани и помилуй нолики и единички
* Плюсы
    - Хорошее разбиение на классы
    - Даже с учётом километров кода для отрисовки всего и вся читается относительно легко (не считая длиннющих формул, которые я не раскурил. правда не сказать, чтобы сильно пытался...)
    - Огромная благодарность за комментарии
    - Очень прикольно реализован класс ArrayExtension
    - Человек, который вбивал нолики и единички в классе Level, жив и не в психушке
* Предложения (всё имхо и везде надо поставить "Товарищ разработчик, а может будет лучше, если <...>?",
т.к. сложно для кода, который писал не сам оценивать эффективность, трудозатраты и полезность внедрения в проект той или иной фичи. Ещё и учитывая что это Jack...)
    - Сделать глобальные статические переменные для всех кнопок клавиатуры, которые используются в проверках
    - Написать кастомный двумерный массив (по факту бесполезно, но было бы прикольно и хотелось бы глянуть ваш вариант реализации)
    - Передавать в функцию drawLewel (UI) параметром только level, ибо внутри функции всё равно переназначаются переменные; выделить в ней несколько вспомогательных методов, а то очень длинно
    - Выделить отдельный класс (например Pointer или типа того) и запихать туда всю логику перемещения по клеткам (типа move и что-то ещё вроде было)
    - Выделить из move метод проверки на выход за границы поля
    - Сделать чуть более информативными названия параметров у функций. Например function void drawSquareofSymbol(int i, int j, int n, boolean color) и т.д.
    - Избавиться от тысяч ноликов и единичек (нет предложений как это сделать, но пока что это боль)
    - Я не совсем понял, зачем нужен кастомный clearScreen, который глобально ничем не отличается от встроенного

## Итого
Девочки, вы очень крутые.
Нереально огромная работа с потрясной идеей. Мне, как любителю таких штук, прям очень зашло.
Да, есть косяки, но во-первых - это блин Jack, во-вторых - всё было против нас (шарпы, дкр, кп, пары, сон...), а самое важное - все мы человеки.
Поэтому главное - это не ругать себя за то, что что-то не получилось сегодня, и каждый день стремиться стать лучше завтра) Вы большие молодцы
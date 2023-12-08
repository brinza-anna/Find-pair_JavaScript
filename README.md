# Тестовое задание от Skillbox

## Задание
Напишите игру в пары в браузере.
В этом задании нужно будет разработать простую игру в "пары". Вы, вполне вероятно, с ней уже сталкивались в том или ином виде в настольных или видеоиграх. Игрок видит квадратное поле из карточек, расположенных "рубашкой" вверх, и находит пары одинаковых карточек, открывая их в произвольном порядке. На открытых карточках могут быть картинки, буквы, цифры, пиктограммы и что угодно ещё. Игрок открывает сначала одну карточку, затем вторую. Если обе открытые карточки одинаковы, они остаются открытыми до конца партии. В противном случае они переворачиваются обратно.

### Начальное состояние игры при открытии в браузере.
На странице рисуется с помощью HTML элементов выводится поле 4 на 4 из квадратных карточек. Каждая карточка содержит цифру от 1 до 8. Пользователь не видит цифры на карточках, то есть карточки расположены "рубашкой" вверх. На поле должно быть строго по 2 карточки с одинаковой цифрой, именно так образуются пары. Все карточки расположены в случайном порядке.

### Ход игры.
Игрок может нажать на любую карточку. После нажатия карточка открывается, то есть на ней пишется её цифра (карточка "переворачивается"). Далее игрок может открыть вторую карточку. Если обе открытые карточки содержат одинаковую цифру, они остаются открытыми до конца игры. Если же вторая карточка содержит отличную от первой цифру, обе они закрываются, как только игрок откроет следующую карточку. Таким образом на поле остаются открытыми только найденные пары или 1-2 карточки, открытые игроком.

### Конец игры.
Как только игрок открыл все пары на поле, игра считается завершённой. Под полем с открытыми карточками появляется кнопка "Сыграть ещё раз", при нажатии на которую игра сбрасывается до начального состояния с заново перемешанными карточками.

### Дополнительные задания*.
Эти задания необязательны для выполнения, но дают вам больше практики:
- Сделайте так, чтобы перед игрой можно было настроить количество карточек на поле. Для этого сначала показывайте игроку форму с полем "Кол-во карточек по вертикали/горизонтали" и кнопкой "Начать игру". В поле можно ввести чётное число от 2 до 10. Если значение некорректное (то есть нечётное или не в пределах 2-10), то при нажатии на кнопку оно сбрасывается до значения по умолчанию (4).
- Добавьте таймер в 1 минуту, по истечению которого игра сразу завершается, даже если ещё не открыты все карточки.

### Как к нам попасть

#### На что обратить внимание

При проведении собеседований мы в первую очередь смотрим на то, насколько человек разделяет наши ценности. Технические навыки здесь встают на второй план, ведь при наличии достаточного желания освоить весь стек применяемых нами методик и технологий достаточно несложно. На какие личностные качества мы смотрим:

- **Умение добиваться результатов**. Пусть и небольшой, но законченный проект ценнее вороха крутых идей и предложений.
- **Способность идти на компромиссы**. Упрямство - тормозящий фактор при работе в команде. Нужно уметь прислушиваться к чужой точке зрения, понимать и принимать ее.
- **Вдумчивость**. Если задача или вопрос не решаются с наскока - нельзя бросать все попытки решить их. Ход рассуждений, даже если он ни к чему не приведет, для нас интереснее короткого правильного ответа. Для нас важны умение рассматривать задачи и проблемы с разных сторон и уровней абстракции, последовательность и логичность при их решении.
- **Интерес и внимание к деталям**. Мы спрашиваем не только о том, как что-то работает, а и о том - почему именно так происходит.

Большую часть времени мы все-таки общаемся о технических вопросах, и для успешного прохождения интервью нужно в них ориентироваться. Основные области, о которых мы общаемся:

##### Общие вопросы

- Структуры данных, их отличие и области применения.
- Параллельное программирование. Основные понятия и простые задачи.
- Классические паттерны, определения и область применения.
- Принципы проектировния. SOLID, YAGNI, KISS, DRY.
- Основные подходы к архитектуре мобильных приложений.
- Unit-тестирование, TDD.

##### iOS

- Работа с памятью. ARC, MRC, weak/strong/assign/retain.
- Техники работы с многопоточностью. GCD, NSOperation.
- CoreData. Устройство, особенности и проблемы.
- Работа с runtime. Method swizzling, категории, dispatch tables.
- Работа с UI. Анимации, autolayout.

Этими областями мы, конечно, не ограничиваемся. Если человек в чем-то особенно хорошо разбирается, или ему есть о чем рассказать - мы рады побеседовать. Сильные стороны для нас важнее, чем слабые.

#### Тестовые задания

В большинстве случаев помимо собеседования мы просим кандидатов выполнить тестовое задание. Никаких искусственных ограничений, вроде жестких сроков мы не накладываем.

##### Задание 1: RSS-reader
Приложение должно отображать новости в одном списке, отсортированном по дате публикации, из двух источников:

- http://lenta.ru/rss
- http://www.gazeta.ru/export/rss/lenta.xml

Приложение должно указывать в новости ее источник (lenta.ru или gazeta.ru). Новость должна иметь два режима отображения – обычный и расширенный.
В обычном выводятся элементы: картинка, заголовок. В расширенном добавляется краткое описание новости. Режим отображения должен меняться по тапу на новость.

При выполнении задания необходимо продемонстрировать навыки работы по git flow, TDD и VIPER. Можно использовать сторонние библиотеки.

##### Задание 2: Графики
Реализовать приложение, отображающее график функции. Сверху поле ввода, кнопка перерисовки графика, снизу - сам график. В поле ввода могут быть введены только положительные числа, операции "+", "-", "*", символ "x", символ пробел. Если встречается некорректный символ, нужно показывать алерт с ошибкой. Выражение вводится со скобками, считается, что скобки расставлены верно.

**Примеры:**

- (3 * (2 + x))
- (x*x)
 
При выполнении задачи можно использовать только стандартные фреймворки.
# BinomialHeap
Binomial heap on functional lists written in Kotlin

BinomialHeap - реализация биномиальной кучи

https://en.wikipedia.org/wiki/Binomial_heap

Запрещено использовать
- `var`
- циклы
- стандартные коллекции

Детали внутренней реазации должны быть спрятаны
Создание - только через `single()` и `plus()`

Куча совсем без элементов не предусмотрена

Операции

- `plus` с кучей
- `plus` с элементом
- `top` - взятие минимального элемента
- `drop` - удаление минимального элемента
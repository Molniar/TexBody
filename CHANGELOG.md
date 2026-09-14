# Changelog

## [1.1] - 2026-09-14

### Добавлено
- HTTP-запросы: GET, POST, PUT, DELETE
- Работа с файлами: file.read, file.write, file.append, file.copy, file.move
- Работа с папками: folder.create, folder.list, folder.delete
- Дата и время: time.now!, time.format(...)
- Картинки: http.image + Tex img> + ASCII-арт (ч/б и цветной)
- JSON: json.parse, json.create
- Модули: import "file.tb^^" use name
- JS-модули: import js "url" use name
- Встроенная консоль ввода (замена prompt)
- Справочник на 9 вкладок
- Автодополнение в редакторе
- Панель переменных в реальном времени
- Встроенные функции: max, min, sum, abs, random
- Тернарный оператор: условие ? да ! нет
- Нечёткое сравнение: @a ~==:5 @b
- Возврат из функций: give @result
- Ссылки на функции: res = sum.4.5

### Изменено
- Ввод через встроенную консоль вместо prompt()
- Подсветка синтаксиса через CodeMirror

## [1.0] - 2026-06-XX

### Добавлено
- Базовый синтаксис Tex>
- Переменные и константы
- Условия ? !? !
- Циклы ??
- Пакеты Pack<>
- Многострочный вывод Tex>>...<<
- Экранирование \> и \>>
- Многострочные комментарии \...\
- yes/no

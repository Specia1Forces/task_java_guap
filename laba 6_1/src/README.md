# Задание 6.1 Ввод-вывод.

Реализовать класс FormattedInput с двумя статическими функциями:

```text
Object[] scanf(String format). Читает с System.in.
Object[] sscanf(String format, String in). Читает из строки in.

format --- строка со спецификацией формата ввода (может быть несколько спецификаторов в одной строке, например, «%d %d %f»). Список спецификаторов:
%d --- целое int
%f --- дробное double
%s --- строка
%c --- символ

Если ввод пользователя не соответствует спецификации, то функция запрашивает ввод повторно.
Пример:
main(..) {
…………………...
    Object vals[] = scanf(“%d %s %c”);
…………………..
}
Ввод пользователя: 10 ten v
```



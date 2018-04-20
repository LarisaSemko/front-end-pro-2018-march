# Изучить материал

* https://git-scm.com/book/ru/v1/
* https://events.yandex.ru/lib/talks/671/
* https://proglib.io/p/git-workflow/
* https://proglib.io/p/git-tips/

# Практика

1) создать репозиторий, воспроизвести историю:

![Alt Text](/src/images/img_2.png)

2) заполнить файл names.txt следующим образом:
```
1) Сычёв Савелий
2) Иванов Иван
...
```

Добавление своего имено должно происходить через ветку, например: `HW_10_Sychov`,
далее нужно использовать подход `merge` с флагом `--no-ff`

Ветка в которой файл будет доступен `HW_10_target`
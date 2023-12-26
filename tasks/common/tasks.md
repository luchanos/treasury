## Задача на временные метки
Есть список событий:
```
[
            {
                "dt": "2022-02-23 04:35:27.353366",
                "event": "start"
            },
            {
                "dt": "2022-02-23 04:35:34.654153",
                "event": "stop"
            },
            {
                "dt": "2022-02-23 04:38:34.382548",
                "event": "start"
            },
            {
                "dt": "2022-02-23 04:38:39.637583",
                "event": "stop"
            }
]
```
В этом списке последовательно лежат события типа START и STOP, а также их временные метки. События лежат
последовательно: после START всегда идёт STOP и наоборот. Задача:

1. Написать функцию, которая возвращает количество часов, выпадающее на промежуток соответствующих событий 
START - STOP за указанную дату.
2. Возвращать количество часов за диапазон дат.
3. Возвращать количество часов за текущий день, неделю, месяц, год.
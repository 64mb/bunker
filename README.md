# bunker companion

Приложение компаньон для настольной игры "Бункер"

Приложение было создано в целях сохранения аудиозаписей из официальных QR кодов внутри приложения, т.к. хранение записей на площадке Dropbox, куда ведут QR коды на корточках является крайне не надежным решением

В приложении сохранен элемент интерактивности, при наведении на QR код на карточке катастрофы, он будет корректно распознан, однако аудиозапись будет воспроизведена из ресурсов приложения

Приложения не является официальным, создано исключительно в личных целях

- Распространяются только исходные коды приложения, все изображения внутри репозитория не позволяют воспроизвести набор и необходимы лишь для обработки и получения ссылок из QR кодов

- Приложение нигде не публикуется

- Все права на игру принадлежат издательству "Экономикус"

[Официальный сайт издательства игры](https://www.economicusgame.com/bunker)

[Ссылка на правила игры](https://www.dropbox.com/s/e2n7e9m2rgkyhid/Bunker_3_Rules.pdf)

---

Структура репозитория:

- `app` - исходный код мобильного приложения на `flutter`

- `icon` - исходные ресурсы для генерации иконки приложения

- `resources` - ресурсы для формирования приложения, полученные путем обработки фотографий карточек игры

- `parser.py` - скрипт обработки фотографий карточки для получения ресурсов на `Python 3`


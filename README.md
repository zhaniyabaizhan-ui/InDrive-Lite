# inDrive Lite (EXPO Astana)

Demo репозиторий: экспорт из Base44 + мок-данные.

## Что есть
- `/prompt/master_prompt.md` — полный промпт, по которому генерировали приложение.
- `/base44_export/*.txt` — сырой экспорт страниц/модулей из Base44 (без правок).
- `/src/*` — если Base44 сгенерировал HTML/JS/CSS — здесь.
- `/data/mock_data.json` — POI, events, ripening, heatmap points.
- `/screenshots/*` — скрины Passenger/Driver.

## Как смотреть
1. Открой `/screenshots` для визуального вида.
2. Пролистай `/base44_export/*.txt` чтобы увидеть бизнес-логику/настройки.
3. Если есть `/src/index.html` — просто открой его в браузере (двойной клик).

## Примечания
- Карта — нижний слой; UI — бело-зелёные панели поверх (как inDrive).
- Маршрутизация должна работать по дорогам (2GIS / OSRM / ORS).
- Сценарии: Morning Peak, Evening Concert, Custom (Bakery).

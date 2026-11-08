# Дюна: Битва за Арракис

Главная страница `index.html` — HTML-файл концепта, предоставленный пользователем. Откройте его в браузере или запустите `python3 -m http.server 8000 --bind 0.0.0.0`. Предыдущий неофициальный прототип сохранён в `prototype.html` (использует `game.js`, `style.css` и `assets/`).

В предыдущем прототипе выберите юнит левой кнопкой мыши, отдайте приказ на движение или атаку правой. На сенсорном экране выберите юнит и коснитесь цели. Харвестер автоматически добывает пряность; за неё можно производить войска. Цель — уничтожить базу противника, защитив свою. Это не точная реконструкция оригинальной игры; графика нарисована средствами canvas.

## Визуальные референсы и состояние графики

- [Каталог спрайтов Sega-версии на The Spriters Resource](https://www.spriters-resource.com/sega_genesis/duneiithebattleforarrakis/) — юниты, здания и тайлы.
- [Здания](https://www.spriters-resource.com/sega_genesis/duneiithebattleforarrakis/asset/239094/), [боевой танк](https://www.spriters-resource.com/sega_genesis/duneiithebattleforarrakis/asset/550029/), [харвестер](https://www.spriters-resource.com/sega_genesis/duneiithebattleforarrakis/asset/141659/), [трицикл](https://www.spriters-resource.com/sega_genesis/duneiithebattleforarrakis/asset/169129/).
- Для созданных в этом прототипе изображений дополнительно использованы как визуальные референсы скриншоты Sega-версии из [обзора Skullduggery](https://skullduggery.us/rants/dune-ii-the-building-of-a-dynasty/). Изображения в `assets/` сгенерированы ИИ, это не оригинальные игровые спрайты и не точная перерисовка каждого объекта.
- Внедрены пять новых изображений: строительный двор, танк, трицикл, харвестер и звуковой танк. Пехота остаётся условной графикой; остальные юниты и здания пока не реализованы. Для публикации необходимо отдельно выяснить права на Dune и материалы игры.

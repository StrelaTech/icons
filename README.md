# StrelaTech Icons

Единый набор SVG-иконок в двух стилистках: **outline** (контур) и **filled** (заливка).

- 84 иконки в каждой вариации — `filled/` и `outline/`
- Сетка 24×24, обводка 2.5 px, скруглённые концы и стыки
- Цвет задан чёрным — легко перекрашивается через CSS (`fill` / `stroke`)

## Просмотр

Локально:

```bash
python3 -m http.server 8000
# откройте http://localhost:8000
```

Или онлайн: [github.com/StrelaTech/icons](https://github.com/StrelaTech/icons) (GitHub Pages, если включён).

Превью поддерживает поиск, переключение Outline/Filled, тёмную тему и RU/EN.

## Использование

Скачайте нужный файл из `filled/` или `outline/` с [страницы превью](https://github.com/StrelaTech/icons) либо напрямую из репозитория.

Встраивание (`<img>`):

```html
<img src="filled/shield.svg" width="24" height="24" alt="Shield">
```

Инлайн-виджет с перекраской (для outline достаточно `stroke`):

```html
<span style="color:#4f7cff">
  <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
    <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
  </svg>
</span>
```

## Категории

| Категория | Иконки |
|---|---|
| Базовые UI | alert, menu, close, plus, minus, check, search, settings, edit, refresh, more |
| Навигация | arrow-left, arrow-right, arrow-up, arrow-down, home, send, share, link |
| Медиа | play, pause, image, video, music, headphones, camera, mic, volume |
| Связь | phone, mail, chat, bell, bell-off, wifi, bluetooth, smartphone, globe |
| Безопасность / VPN | shield, key, lock, fingerprint, server, power, activity, cloud, cloud-off |
| Файлы | file, folder, database, download, upload, trash, bookmark, tag, printer, credit-card, shopping-cart, gift |
| Измерения | ruler, gauge, scale, timer, resize, filter |
| Время | clock, calendar, timer, sun, moon |
| Пользователь | user, eye, heart, star, bookmark, zap |
| Код | terminal, code, c, cpp, python, github, monitor, database |
| Бренды | strela-logo, SXvpn-logo |

## Правила набора

1. `viewBox="0 0 24 24"`, обводка `2.5`, `stroke-linecap/linejoin: round`.
2. `outline/` — только обводка `#000000`, без заливки; в шапке файла комментарий с именем.
3. `filled/` — фигура залита `fill="black"` + та же обводка; внутренние прорези рисуются белым.
4. Имена файлов — в `kebab-case`, на английском.
5. Каждая иконка присутствует в обеих папках (`filled` и `outline`).

## Лицензия

См. [LICENSE](LICENSE).

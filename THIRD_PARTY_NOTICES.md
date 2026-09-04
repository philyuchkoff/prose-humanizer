# Third-Party Notices

`prose-humanizer` — независимый скилл-редактор. Собран как объединение лучшего из двух open-source проектов под лицензией MIT. Благодарим авторов за открытый код и ясную методологию.

## Включённые материалы

### 1. `thevseprod/humanizer-ru` (MIT)

- **Репозиторий:** https://github.com/thevseprod/humanizer-ru
- **Автор:** @thevseprod (Telegram: [@buyonhigh](https://t.me/buyonhigh), YouTube: [@thevseproduction](https://www.youtube.com/@thevseproduction))
- **Лицензия:** MIT
- **Что взято:** двуязычный (RU + EN) набор правил; двухпроходный процесс переписывания; правило «анонс вместо содержания» как структурный приём; «золотое правило» свежести формулировок; английский блок правил с конкретными формулировками (`delve`, `tapestry`, `leverage`, `It depends`, `Not only… but also…`).
- **Файл-источник:** [`thevseprod-humanizer-ru/SKILL.md`](https://github.com/thevseprod/humanizer-ru/blob/main/SKILL.md)

### 2. `comol/Humanizer_RU` (MIT)

- **Репозиторий:** https://github.com/comol/Humanizer_RU
- **Автор:** @comol85 (Telegram-канал [It Does Matter](https://t.me/comol_it_does_matter), проект [VibeCoding1C](https://vibecoding1c.ru/))
- **Лицензия:** MIT
- **Что взято:** методология «редактор, а не детектор»; три принципа (объективное правлю — вкусовое предлагаю; голос автора неприкосновенен; минимальная достаточная правка); **факт-замок** (сильнее любого правила); жанры (`doc`, `article`, `post`, `letter`, `spec`, `legal`, `academic`, `fiction`) и режимы (`careful` / `deep` / `audit`); каталог паттернов с severity-уровнями (`error` / `high` / `low` / `note`); защита от стерилизации; словарь «что НЕ трогать» (false-positives); инструкция «как снять паспорт голоса с образцов автора»; структурированный формат вывода (текст → `---` → «что изменено» → «на решение автора» → «нужны данные»).
- **Файл-источник:** [`comol-Humanizer_RU/skills/humanizer-ru/SKILL.md`](https://github.com/comol/Humanizer_RU/blob/main/skills/humanizer-ru/SKILL.md) и вложенные `references/*.md`, `knowledge/*.md`.

## Что изменено по сравнению с исходниками

- Убрана 1С-специфика (терминология 1С, словарь `terms-it-1c.md`, линтер `humanizer_ru`) — скилл сделан универсальным для любой русской и английской прозы.
- Паспорт конкретного автора (`comol` → `knowledge/voice-author.md`) заменён инструкцией «как снять свой» (`references/voice.md`).
- Правила автора (`comol` → `knowledge/corrections.md`) исключены — это частные предпочтения, которые не должны быть жёстко вшиты.
- Каталог паттернов объединён: A–I разделы, добавлены английские аналоги паттернов и пометки `[ru]`, `[en]`, `[ru|en]`.

## Лицензия производного скилла

`prose-humanizer` распространяется под [MIT License](./LICENSE). Условия лицензий исходных проектов соблюдены: уведомления о копирайте и разрешениях сохранены в этом файле.

## Благодарности

Спасибо @thevseprod за двуязычный набор правил с фокусом на практику, и @comol85 за методологическую глубину и калибровку на реальных текстах. Без их работы этот скилл не появился бы.

# claude-open

Сторінка-перехід для кнопок Telegram: `?s=local_<uuid>` → `claude://claude.ai/epitaxy/local_<uuid>`.
Telegram пускає в кнопки лише http(s), тому потрібен цей проміжок. Перекидає тільки на сесію Claude з перевіреним форматом ID — інших адрес не приймає. Без секретів, без зовнішніх ресурсів.
Джерело — `adops/web/claude-open/` (приватний репо adops).

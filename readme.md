html {
  cursor: default; /* 1 */
  font-family:
    system-ui,
    /* macOS 10.11-10.12 */ -apple-system,
    /* Windows 6+ */ Segoe UI,
    /* Android 4+ */ Roboto,
    /* Ubuntu 10.10+ */ Ubuntu,
    /* Gnome 3+ */ Cantarell,
    /* KDE Plasma 5+ */ Noto Sans,
    /* fallback */ sans-serif,
    /* macOS emoji */ "Apple Color Emoji",
    /* Windows emoji */ "Segoe UI Emoji",
    /* Windows emoji */ "Segoe UI Symbol",
    /* Linux emoji */ "Noto Color Emoji"; /* 2 */

  line-height: 1.15; /* 3 */
  -moz-tab-size: 4; /* 4 */
  tab-size: 4; /* 4 */
  -ms-text-size-adjust: 100%; /* 5 */
  -webkit-text-size-adjust: 100%; /* 5 */
  word-break: break-word; /* 6 */
}

Это из современного:

1. Используется курсор по умолчанию во всех браузерах 
2. Используется шрифт пользовательского интерфейса по умолчанию во всех браузерах
3. Исправляет высоту строки во всех браузерах.
4. Используется табуляция с 4 пробелами во всех браузерах.
5. Запрет корректировки размера шрифта после изменения ориентации в * IE на Windows Phone и iOS.
6. Разбивает слова для предотвращения переполнения во всех браузерах
   
---------------------------------------------------------------------------------   
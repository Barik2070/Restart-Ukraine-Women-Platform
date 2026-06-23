# Acceptance audit — Restart Ukraine Women MVP

Дата аудиту: 23 червня 2026.

## Доведено локальними артефактами

| Вимога | Авторитетний доказ | Статус |
|---|---|---|
| Moodboard і бренд-концепція | `moodboard.html`, `assets/brand-concept.png` | Виконано |
| Логотип і палітра | `assets/logo.png`, `ui-kit.html` | Виконано |
| Типографіка і компоненти | `styles.css`, `ui-kit.html`, `DESIGN-GUIDE.md` | Виконано |
| Головна сторінка з усіма обов’язковими блоками | `index.html` | Виконано |
| Про платформу | `about.html` | Виконано |
| Сторінка програм | `programs.html` | Виконано |
| Три окремі навчальні треки | `track-auto.html`, `track-business.html`, `track-agro.html` | Виконано |
| AI-модуль | `ai.html` | Виконано |
| Партнерам і донорам, KPI | `partners.html` | Виконано |
| Анкета з 14 групами полів і success state | `application.html`, `app.js` | Виконано |
| Особистий кабінет / навчальна зона | `dashboard.html` | Виконано |
| UX Telegram-бота | `telegram.html` | Виконано |
| Контакти | `contacts.html` | Виконано |
| UI-kit і design guide | `ui-kit.html`, `DESIGN-GUIDE.md` | Виконано |
| Адаптивні правила | `styles.css`: breakpoints 980/640 px, fluid desktop container | Реалізовано в коді |
| Reduced motion та клавіатурний skip-link | `styles.css`, `index.html` | Реалізовано в коді |
| Внутрішня цілісність | автоматична перевірка всіх локальних `href/src` | Виконано |

## Не доведено

| Вимога | Чому доказ недостатній | Що потрібно |
|---|---|---|
| Візуальна якість desktop 1440/1280, tablet 768, mobile 375 | Вбудований Browser не має мережевого доступу до локального сервера в цьому середовищі; `file://` заблоковано політикою Browser Use | Відкрити локальний проєкт у доступному browser-render середовищі та зробити viewport QA |
| Функціональна browser-перевірка анкети, меню й modal | Статичний код і синтаксис не є доказом фактичної поведінки DOM | Виконати інтерактивні browser-тести |
| Figma-файл з компонентами | У робочій області немає Figma-файлу/URL і доступного Figma-конектора | Надати Figma URL або дозволити імпорт у Figma |
| Реальні контактні адреси | Поточні `@restartwomen.org` є продуктовими placeholder-адресами | Надати підтверджені email/Telegram |
| Фактичне надсилання анкети | MVP реалізує UX і success state без backend/CRM | Надати endpoint або CRM-інтеграцію |

## Висновок

Локальний UX/UI-прототип і всі названі MVP-екрани створені. Остаточне приймання не можна підтвердити без візуального browser QA, Figma-артефакту та зовнішніх інтеграцій/контактів.

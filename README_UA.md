# Сторінки для публікації Planer / PostPilot у Meta

## 1. Заміни контактний email

Відкрий по черзі `index.html`, `privacy.html`, `data-deletion.html` і `terms.html` через Блокнот.

У кожному файлі заміни:

`YOUR_EMAIL@example.com`

на контактну адресу, яку можна показувати публічно. Не вставляй паролі, App Secret, Meta-токени або резервні коди.

## 2. Створи репозиторій GitHub

1. Увійди на `https://github.com`.
2. Натисни **New repository**.
3. Назва: `postpilot-legal`.
4. Вибери **Public**.
5. Натисни **Create repository**.
6. Натисни **uploading an existing file**.
7. Перетягни всі п'ять файлів: чотири HTML-файли та `styles.css`.
8. Натисни **Commit changes**.

`README_UA.md` завантажувати необов'язково.

## 3. Увімкни GitHub Pages

1. У репозиторії відкрий **Settings → Pages**.
2. У розділі **Build and deployment** вибери **Deploy from a branch**.
3. Branch: `main`, папка: `/(root)`.
4. Натисни **Save** і зачекай кілька хвилин.

Адреса буде приблизно такою:

`https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/`

Перевір у режимі інкогніто, що відкриваються:

- `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/privacy.html`
- `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/data-deletion.html`
- `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/terms.html`

## 4. Заповни Meta App

У **Настройки приложения → Основные** встав:

- **Домены приложений:** `ТВІЙ_ЛОГІН.github.io`
- **URL Политики конфиденциальности:** `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/privacy.html`
- **URL-адрес Пользовательского соглашения:** `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/terms.html`
- **Удаление данных пользователей → URL инструкций:** `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/data-deletion.html`
- **URL-адрес сайта:** `https://ТВІЙ_ЛОГІН.github.io/postpilot-legal/`

Натисни **Сохранить изменения**, повернися до розділу **Публикация** й онови сторінку.

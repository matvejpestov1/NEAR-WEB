NEAR Online — Neon Glass

Функции:
- регистрация и вход по email/паролю;
- поиск пользователя по username;
- личные сообщения в реальном времени с периодическим обновлением;
- отправка изображений до 8 МБ через приватный Supabase Storage;
- адаптивный интерфейс.

Настройка:
1. Создай проект Supabase.
2. Открой SQL Editor, вставь весь setup.sql и нажми Run.
3. Открой Project Settings → API. Скопируй Project URL и anon/public key.
4. Вставь их в supabase-config.js вместо PASTE_...
   Никогда не вставляй service_role/secret key в браузер.
5. Опубликуй содержимое папки в GitHub Pages (Settings → Pages → Deploy from branch → main / root).

Важно:
- Регистрация может требовать подтверждения email — настрой Auth → URL Configuration с адресом сайта.
- Это стартовая версия. Нет групповых чатов, звонков, push-уведомлений и сквозного шифрования.
- Не отправляй чувствительные личные данные. Не публикуй anon key вместе с отключёнными RLS-политиками.

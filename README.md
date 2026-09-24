# BP Строй Оферти v2

## Инсталация
1. Разархивирайте съдържанието директно в web директорията `/oferti`.
2. Използвайте PHP 8.1+ с `PDO`, `pdo_sqlite` и `mbstring`.
3. Дайте права за запис на `storage`: `chmod -R 770 storage`.
4. Отворете `/oferti/index.php?action=health` и проверете `ok`, `pdo_sqlite` и `storage_writable`.
5. Влезте с `admin` / `admin123`.
6. Направете Ctrl+F5 след обновяване.

Файловете са в `storage/offers/YYYY/MM/client/`, а SQLite базата е `storage/db/app.sqlite`.
Excel редакторът зарежда SheetJS от jsDelivr с fallback към unpkg.


## Управление на потребители
Влезте като администратор и използвайте бутона „Потребители“ в горния десен ъгъл. Модулът поддържа създаване, промяна на парола и изтриване. Паролите се записват като PHP password hash.
"# bpstroy_oferti" 

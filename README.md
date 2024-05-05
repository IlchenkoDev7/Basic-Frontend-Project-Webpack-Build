## Базовая сборка проекта

💡 Webpack уже настроен для работы с JavaScript, SCSS, шрифтами и изображениями.  
💡 Работа проекта осуществляется без использования Live Server, при этом все изменения в вёрстке сохраняются автоматически.

### Алгоритм настройки

1. Загрузите базовую сборку с конфигурацией Webpack.
2. Установите все файлы из текущего репозитория.
3. Выполните команду `npm install`.

### Разработка проекта
Осуществляется с помощью Webpack Dev Server, для его запуска надо просто использовать команду `npm start`

### Сборка и её режимы

#### Для сборки проекта в режиме разработки:

- Выполните базовую сборку командой `npm run build-dev`.

#### Для сборки продакшн версии:

- Очистите папку dist командой `npm run clear-dist`.
- Соберите проект командой `npm run build-prod`.

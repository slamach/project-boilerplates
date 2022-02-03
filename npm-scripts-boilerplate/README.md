# Universal Npm Scripts Boilerplate

## О проекте

Шаблон для сборки небольших проектов, где используется JS и Sass.

### Особенности проекта
- **Browsersync:** Локальный сервер с HMR
- **Imagemin:** Сжатие изображений с помощью Imagemin
- **EditorConfig и Prettier:** Автоматическое форматирование исходных файлов при коммите

### Структура проекта
Вся разработка происходит в директории `src`.
- `fonts` -- шрифты
- `img` -- медиафайлы
- `js` -- JS-скрипты
- `scss` -- SCSS-стили

## Сборка и запуск
```
npm install
```

Чтобы заработал pre-commit хук, нужно выполнять `npm install`, когда проект уже инициализирован как Git-репозиторий.

Если проект инициализируется как репозиторий позже, нужно дополнительно выполнить `npm run prepare`.

### Development
```
npm start
```

### Production
```
npm build
```

## Контакты
Дмитрий Свиридов  
Telegram: [slamach](https://t.me/slamach)  
Email: sviridov.dvv@gmail.com

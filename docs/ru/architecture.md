```
root/
├── tests/
│    ├── actions/             <- Тесты на обработку запросов
│    ├── components/          <- Тесты на рендер компонентов
│    ├── mocks/               <- Захардокженная инофрмация об устройстве
│    ├── reducers/            <- Тесты для менеджера состояний
│    └── screens/             <- Тесты на рендер страниц
├── docs/
│    ├── en/                  <- Англоязычная документация
│    └── ru/                  <- Русскоязычная документация
├── src/
│    ├── actions/             <- Обработка запросов
│    ├── assets/              <- Изображения
│    ├── components/          <- Переиспользуемые компоненты
│    ├── config/              <- Языковые, стилистические кофигурации и общие настройки 
│    ├── constants/           <- Константы
│    ├── reducers/            <- Управление состояниями
│    ├── screens/             <- Компоненты экранов
│    ├── services/            <- Настройки axios, добавление 
│    ├── utils/               <- Утилиты
│    ├── index.js             <- Настройки навигации
│    ├── screns.js            <- Навигация
│    └── store.js             <- Настройка redux
├── app.json                  <- Описание приложения
├── babel.config.js           <- Интсрукции для babel
├── index.js                  <- Файл запуска приложения
├── index.android.js          <- Файл запуска приложения
├── metro.config.js           <- Инструкции для metro
└── postinstall.sh            <- Скрипт для удаления старых зависимостей из node_modules
```
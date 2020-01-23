# Pug Stylus Webpack Simple Starter Kit

Шаблон проекта для старта. Используется препроцессор Pug для структуры, Stylus для стилей. Сборка производится с помощью Webpack в конечную папку /public. Исходные файлы для разработки лежат в папке source. С помощью препроцессора Pug можно организовать компонентную верстку с древовидной структурой, например создавая папку source/components и реализуя в ней компоненты в виде миксинов с помощью возможностей Pug и придерживаясь методологии БЭМ. Конфигурация webpack в файле webpack.config.js

Клонирование репозитория:
git clone https://github.com/Sergio-Ka/PugStylusWebpackSimpleStarterKit.git

Установка модулей для сборки:
npm i (или npm install)

Команды:
- разовая сборка для production: npm run build,
- сборка для разработки (с опцией -watch и без минификации js-файла сборки): npm run dev,
- сервер с live reload: npm run server, http://localhost:8080/.

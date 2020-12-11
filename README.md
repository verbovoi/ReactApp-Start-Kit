//Создаем приложение ReactApp в текущей папке и загружаем библиотеки

npx create-react-app . 

npm install gh-pages

npm install --save prop-types

npm install --save-dev prettier husky lint-staged

npm install --save normalize.css


//Добавляем scripts в package.json

"predeploy": "npm run build",
"deploy": "gh-pages -d build"


//Добавляем домашнюю страницу для деплоя на Гит

"homepage": "http://verbovoi.github.io/goit-react-hw-02-feedback",
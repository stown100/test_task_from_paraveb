Тестовый лендинг написанный на React.js.
Слайдер подключен с помощью библиотеки Swiper.
Данный для карточек взяты с сервера с помощью fetch - get запрос.
Фильтрация карточек в соответствии с условием производится на клиенте.
Вся логика описана в App.js

Технологии: React.js, HTML, CSS, Flex, Grid, ООП, React Hooks, Fetch, 

Проект запускается с помощью команды:

npm start
Запускает приложение в режиме разработки.
Откройте http://localhost:3000, чтобы просмотреть его в браузере.

Страница перезагрузится, если вы внесете изменения.
Вы также можете увидеть любые ошибки lint в консоли при помощи команды:

npm test
Запускает тестовый запуск в режиме интерактивного просмотра.
См. Раздел о running tests для получения дополнительной информации.

npm run build
Создает приложение для производства в папке "сборка".
Он правильно связывает реакцию в производственном режиме и оптимизирует сборку для достижения наилучшей производительности.

Сборка уменьшена, а имена файлов включают хэши.
Ваше приложение готово к развертыванию!

См. Раздел о deployment для получения дополнительной информации.

npm run eject
** Примечание: это односторонняя операция. Как только вы "катапультируетесь", вы не сможете вернуться!**

Если вас не устраивает инструмент сборки и выбор конфигурации, вы можете "извлечь` его в любое время. Эта команда удалит зависимость от одной сборки из вашего проекта.

Вместо этого он скопирует все файлы конфигурации и транзитивные зависимости (webpack, Babel, ESLint и т.д.) Прямо в ваш проект, чтобы у вас был полный контроль над ними. Все команды, кроме "извлечь", будут по-прежнему работать, но они будут указывать на скопированные сценарии, чтобы вы могли их настроить. На данный момент вы предоставлены сами себе.

Вам никогда не нужно использовать "извлечение`. Кураторский набор функций подходит для небольших и средних развертываний, и вы не должны чувствовать себя обязанным использовать эту функцию. Однако мы понимаем, что этот инструмент не был бы полезен, если бы вы не могли настроить его, когда будете готовы к этому.
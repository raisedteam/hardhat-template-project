# hardhat-project-template-js
Hardhat project template for JS

В данном репо хранится образец проекта на Hardhat, с настроенным hardhat.config.js и подключенными полезными плагинами.

Чтобы начать работать, нужно:
- склонить проект
- выполнить npm i
- переименовать .env.example в .env
- переименовать .secret.example в .secret

По умолчанию, при запуске тестов (npx hardhat test), активируется плагин gas-reporter, показывающий отчёт по расходу газа в контракте. При желании, его можно отключить в .env

Для запуска проверки покрытия достаточно выполнить npx hardhat coverage

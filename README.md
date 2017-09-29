# Школа Node.js: Инструменты на Node.js для разработки и сборки приложения

Репозиторий содержит итоговый проект по воркшопу лекции «Инструменты на Node.js для разработки и сборки приложения» в рамках [Школы Node.js](https://academy.yandex.ru/events/frontend/spb-2017/).

## Установка

```bash
npm i
```
## Задачи

Продолжить воркшоп можно, прислав пулл-реквест с *любым* улучшением, развитием проекта. Каждый пулл-реквест будет просматриваться и обсуждаться. Возможные направления для мысли:

* Реализовать в Babel любой нереализованный пропозал в ECMAScript (https://github.com/tc39/proposals) - выполнившие, присылайте ссылку на соответствующий репозиторий
* Автоматизировать процессы линтинга (помимо уже реализованных; например, npm-скриптами)
* Формировать html-файл динамический с помощью Gulp (Webpack реализация в наличии)
* При сборке с помощью Webpack вынести стили в отдельный бандл
* Прокачать сборку Webpack: dev-server, tree shaking, минификация и другое

**!**: Обратите внимание, что финальная версия воркшопа настроена в первую очередь под сборку Webpack. Ранее в проекте не было импортов стилей и динамического создания html-файла. Засинхронить сборку Gulp и сборку Webpack также может быть одно из интересных задач.

# auto-notes
Простое HTML5 приложение (WebApp) заметок для iPhone 5s

![](https://user-images.githubusercontent.com/87068231/124927349-372cae00-e007-11eb-8574-40fcdac7f3fb.png)
# Демо
[auto-notes](https://by-arriva.github.io/auto-notes/)
# Зачем
Я люблю все в своей жизни упорядочивать - списки задач, заметки - это прям моё. Имея во владении древнее ведро с болтами, приходится записывать все проблемы с машиной, т.к. озвученая проблема - это половина пути к её решению. Стандартная программа заметок в моём iPhone 5s слишком громоздкая, пришлось делать свою. Не затрагивая iOS разработку, простейший способ создания приложений - PWA (прогрессивное веб-приложение). На iPhone это дело поддерживается весьма скверно, но всё еще работает так называемое WebApp + appcache manifest.
# Как установить
- В своем iPhone в Safari перейти по [адресу](https://by-arriva.github.io/auto-notes/)
- Нажать "Поделиться" снизу
- На экран Домой
- Добавить.
# Как пользоваться
При использовании приложения, сетевое подключение не нужно
- Чтобы добавить заметку:
    - нажать "Новая заметка" сверху справа
    - написать текст заметки
    - Готово
- Чтобы удалить заметку:
    - смахнуть заметку влево
    - ОК
- Чтобы выделить заметку:
     - смахнуть заметку вправо
- Чтобы переместить заметку:
    - долгий тап по нужной заметке
    - заметка выделилась серым
    - выбрать заметку, перед которой надо вставить нужную
- Чтобы экспортировать все заметки в текстовый файл:
    - нажать "Новая заметка" сверху справа
    - написать "arriva"
    - Готово
    - нажать "экспорт"
    - выделить текст
    - нажать "Поделиться..."
    - Скопировать в Documents/Сохранить в Файлы
- Чтобы импортировать заметки из этого текстового файла:
    - нажать "Новая заметка" сверху справа
    - написать "arriva"
    - Готово
    - нажать "Выбрать файл"
# Как работает программа
От обычного сайта, ссылку на который можно сохранить на рабочий стол iPhone, Web App отличается несколькими тегами в html (чтобы скрыть интерфейс браузера) и наличием манифеста, который заставляет браузер сохранить в кэше все файлы для работы офлайн. То есть, по сути, это недоPWA.
